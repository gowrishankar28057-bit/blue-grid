# BlueGrid

**Renewable energy and Blue Economy decision-support platform — independently reimplemented from a previously explored technical concept.**

> **Status:** The earlier prototype source code has been handed over and is **not included** in this repository. This repository is a fresh implementation workstream. Technical methodology and architecture can be reconstructed from scratch, subject to the team's stated permission and any applicable agreements. Executable code has not yet been published here.

## Problem
Renewable-energy planning requires evaluating local resources, technology capacity, battery storage, investment cost, electrical reliability, emissions, and seasonal variability. Island and coastal environments also offer potentially useful ocean-energy resources.

## BlueGrid approach
1. Select a supported location, define load and environmental inputs.
2. Evaluate physics-informed renewable generation and battery performance.
3. Explore hybrid configurations using deterministic, reproducible mathematical optimization.
4. Run chronological energy dispatch and calculate costs, unmet demand, and carbon estimates.
5. Compare alternatives for developers, policymakers, utilities, investors and communities.

## Engineering architecture — independent reimplementation
The **same general scientific workflow and architecture** explored in the earlier project may be used again; this is **not an import of the original source code**.

| Layer | Planned independently written implementation |
| --- | --- |
| Interface | React + TypeScript, site selection, resource and planning dashboard |
| Backend | Python + Flask, documented API endpoints |
| Data processing | NumPy and Pandas, source-provenance metadata |
| Resource models | Solar, wind, OTEC, wave, BESS and other validated renewable modules |
| Mathematical optimization | SciPy HiGHS linear programming, configuration search and feasibility checks |
| Operational evaluation | Hourly chronological storage dispatch and reliability analysis |
| Reporting | Costs (CAPEX, OPEX, LCOE), LPSP, emissions estimates and evidence-linked exports |
| Quality | Automated tests, physics/unit checks and transparent modeling assumptions |

These are implementation goals for this new repository, not a claim that all features are already present or verified.

## Geographic and technology expansion
The product vision includes island, coastal, industrial, residential and regional planning; Earth-based location selection, modular technology expansion, future policy scenarios and multi-year pathways require fresh implementation and validation for each geography.

## What's currently in this repository?
Project planning documents. **No runnable application has been committed yet.**

## Rights and provenance
The original project code was handed over to the relevant mentor/institution. We will write new code without copying or importing that handover. Architecture and scientific ideas may be independently implemented consistent with the permission reported by the team. External documentation, private data and third-party materials require their own reuse rights; source attribution and license review remain necessary.

## Documentation
- [Scope](docs/PROJECT_SCOPE.md)
- [Code and rights boundaries](docs/INDEPENDENT_DEVELOPMENT.md)
- [Build roadmap](docs/BUILD_ROADMAP.md)
