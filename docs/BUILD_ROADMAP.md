# BlueGrid independent build roadmap

## Phase 1 — Establish reproducible baseline
- Define system boundary, demand profile, energy units and hourly timebase
- Select publicly licensed resource data and trace each source
- Implement fresh solar, wind and battery calculations
- Create numerical test cases and cross-check energy conservation

## Phase 2 — Planning and optimization
- Formulate decision variables and constraints independently
- Choose a solver based on newly documented requirements
- Compare at least two alternatives and report feasibility
- Check reliability, costs and sensitivity to assumptions

## Phase 3 — Experience and reporting
- React + TypeScript planning workspace
- FastAPI service contract and validation
- Exportable, evidence-linked reports

## Phase 4 — Ocean energy and regional expansion
- Add OTEC, wave, tidal, offshore wind only where data and physics are suitable
- Implement a geospatial selector with transparent coverage
- Extend scenarios to policy evaluation and multiyear pathways

## Proof required before calling the build functional
- Working code committed
- Reproducible install and run commands
- Automated tests and a real execution record
- Actual screenshots or a screen recording of this new build
- Input datasets and modeling assumptions documented
