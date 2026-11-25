# BlueGrid

**An independently developed renewable-energy planning platform for coastal, island, residential, industrial, and regional applications.**

> **Project status:** Independent rebuild in progress. This repository is not a copy of any earlier project or its source code. Published files should be reviewed and tested before treating them as production-ready.

## The challenge

Planning renewable energy infrastructure means evaluating generation capacity, storage, seasonal resource variability, operating conditions, investment cost, reliability, and environmental effects. These trade-offs are especially demanding for island and coastal systems that may consider blue renewable energy alongside land-based technologies.

## Our direction

BlueGrid aims to provide a scientifically grounded decision-support workflow:

1. Choose a site or geographical area.
2. Define electricity-demand assumptions and planning constraints.
3. Select renewable technologies and energy storage options.
4. Evaluate energy-resource scenarios with independently written, documented physical models.
5. Compare alternative system configurations on investment cost, electricity cost, reliability, and emissions.
6. Explain model limitations, assumptions, uncertainties, and decision trade-offs.

## Intended users

Renewable energy developers and investors; policymakers and planning authorities; utilities and microgrid operators; industry; coastal and island communities; researchers and individual consumers.

## Independent implementation plan

This repository will use an original, modular design rather than reusing an earlier project's source or architecture.

| Layer | New design direction |
| --- | --- |
| User interface | React + TypeScript, interactive geographic exploration and scenario workspaces |
| Service API | Python FastAPI with explicit request/response schemas |
| Resource data | Independently sourced, attributable weather/ocean datasets and provenance records |
| Technology modules | Independently implemented, versioned generation/storage models |
| Scenario engine | Explicit scenario definitions, numerical simulation, sensitivity checks |
| Decision support | Cost, reliability, carbon and uncertainty-aware comparisons |
| Quality | Unit tests, input validation, dataset provenance, reproducibility checks |

These are development targets, **not a claim that every feature is already working in this repository**.

## Current repository scope

This initial commit documents the independently developed project direction and engineering boundaries. Application source, validated datasets, test evidence, and a runnable deployment will be added as they are built and verified.

## Scientific integrity and limitations

- The presence of a methodology description is not evidence that a functioning optimizer has been committed.
- Any sample inputs or results must be identified as synthetic unless traceable to validated data sources.
- Renewable resource availability and financial results have uncertainty.
- Technology modules require geography-appropriate physical validation.
- A deterministic result for fixed inputs is not a guarantee of predictive accuracy or global optimality.

## Development documents

- [Scope and success criteria](docs/PROJECT_SCOPE.md)
- [Independent-development boundaries](docs/INDEPENDENT_DEVELOPMENT.md)
- [Build roadmap](docs/BUILD_ROADMAP.md)

## License

License and reuse terms will be decided only after confirming rights to independently authored content and any external dependencies. No previously handed-over code or private project documentation is included here.
