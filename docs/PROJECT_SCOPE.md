# BlueGrid — project scope and success criteria

## Objective
Rebuild a hybrid renewable-energy planning platform with freshly written source code, reusing permitted engineering ideas and architecture, and improving the interface, coverage, validation and policy relevance.

## MVP scope
- Documented input load profiles, location selection, resource sources and technology assumptions.
- New Flask API implementation, React planning UI and data-processing modules.
- Solar, wind and battery models, followed by OTEC and wave models where physically appropriate.
- Deterministic mathematical optimization, capacity configuration comparisons and chronological battery simulation.
- Reproducible CAPEX, OPEX, LCOE, LPSP and emissions estimates with clear units, limitations and synthetic-data labels.

## Planned expansion
- Location-aware resource adaptation, including approved and scientifically supported marine energy technology.
- 3D Earth location exploration.
- Residential, industrial, island, utility and policymaker scenarios.
- Multi-year capacity pathways and uncertainty-aware comparisons.

## Claims and validation
The prior code was handed over and is not part of this repository; the team reports that architecture and ideas may be independently reimplemented. Every feature is labeled implemented only after fresh code and tests are present. Avoid unverified global coverage, source-data accuracy or guaranteed savings.
