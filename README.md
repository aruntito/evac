# EVAC

**Evacuation simulation and resilience research.**

> How does a system respond under pressure?

EVAC explores evacuation scenarios, constraints, routing strategies, capacity limits, and response behavior through simulation rather than live operational control.

## What it studies

- population and capacity models
- route and network constraints
- congestion and bottlenecks
- scenario simulation
- response strategies
- comparative outcomes and assumptions

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

## Status

Research prototype and simulation architecture.

- [Architecture](docs/architecture.md)
- [Roadmap](docs/roadmap.md)

## Scope boundary

EVAC is for research and simulation. It is not a substitute for emergency authorities, official evacuation orders, or professional emergency planning.

## License

MIT.