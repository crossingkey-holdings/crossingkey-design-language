# Interaction Standard

## Authority before capability

A system being technically able to perform an action does not mean it has authority to perform it.

CrossingKey interfaces should make the following legible where relevant:

- what the system can do;
- what the user authorized;
- what has actually happened;
- what remains pending;
- what failed;
- what can be reversed.

## Failure is a designed state

Errors should identify the failed operation, preserve useful progress when possible, and give the user the smallest next action that can resolve the issue.

## High-agency interface behavior

A high-agency interface reduces supervision without hiding consequential actions. It should automate routine work, surface evidence, preserve reversibility, and avoid fake completion states.

## Commercial clarity

Price, deliverable, execution status, dependencies, and support boundaries should be explicit whenever they affect a buyer or operator decision.
