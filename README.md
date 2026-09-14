# EVAC

**Evacuation simulation and resilience research.**

> How does a system respond under pressure?

EVAC explores evacuation scenarios, constraints, routing strategies, capacity limits, and response behavior through simulation rather than live operational control.

## Why it exists

Resilience is easier to improve when failure and pressure can be studied before they happen.

EVAC provides a controlled research environment for comparing scenarios, identifying bottlenecks, and testing assumptions about movement, capacity, and network behavior.

## What it studies

- population and capacity models
- route and network constraints
- congestion and bottlenecks
- scenario simulation
- response strategies
- comparative outcomes and assumptions

## Use cases

| Use case | Question answered |
| --- | --- |
| Resilience research | Where does a system become constrained? |
| Route analysis | How do routing choices affect flow? |
| Bottleneck research | Which capacities become limiting? |
| Scenario comparison | What changes when assumptions change? |
| Network stress testing | How does the modeled system behave under pressure? |

## Architecture

```text
SCENARIO + MAP + POPULATION + CONSTRAINTS
                    │
                    ▼
              SIMULATION MODEL
                    │
                    ▼
              ROUTING / FLOW
                    │
                    ▼
              SCENARIO OUTCOME
                    │
                    ▼
             COMPARATIVE ANALYSIS
```

## Ecosystem

EVAC is the simulation and resilience-research branch of the TITO systems ecosystem. It can provide research context for GRID, GHOST, and RELIEF-OS.

## Scope boundary

EVAC is for research and simulation. It is not a substitute for emergency authorities, official evacuation orders, or professional emergency planning.

## Status

Research prototype and simulation architecture.

- [Architecture](docs/architecture.md)
- [Roadmap](docs/roadmap.md)

## License

MIT.