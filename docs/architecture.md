# EVAC Architecture

EVAC is a simulation and research environment for evacuation behavior under defined scenarios.

## Flow

```text
SCENARIO
  │
  ├── MAP / NETWORK
  ├── POPULATION
  ├── CAPACITY
  └── CONSTRAINTS
        │
        ▼
   SIMULATION ENGINE
        │
        ▼
 ROUTE / FLOW OUTCOMES
        │
        ▼
 SCENARIO COMPARISON
```

## Design principles

1. Simulation assumptions are explicit.
2. Scenarios are reproducible.
3. Constraints are first-class inputs.
4. Results are separated from operational decisions.
5. Uncertainty and model limitations are documented.

EVAC is a research system, not an emergency-command system.