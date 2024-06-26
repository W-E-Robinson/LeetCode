# Leet Code Flow

This is my personal approach for getting the most out of solving Leet Code problems.

I have no set rules for deciding subsequent solutions to the problem, it could be one of:
- Trying out a different method to solve the problem (e.g. iterative vs recursive).
- Attempting to improve on runtime and/or memory performance.
- Trying to write a solution that is more readable/testable/etc.
- Trying a solution in a different language or without language specific features.
- A combination of the above reasons or any other reason.

```mermaid
flowchart TD
    A[Start] --> B[Solve]
    B --> C[Calculate time and
    space complexity]
    C--> D{First solve?}
    D -->|Yes| E[Start a different solution]
    D -->|No| F{Any other
    beneficial
    ways to solve?}
    F -->|Yes| E[Start a different solution]
    F -->|No| G[Finish]
    E --> B
```