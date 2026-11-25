# BlueGrid — fresh-source rebuild roadmap

## Phase 1 — Rebuild scientific foundation
- Define inputs, hourly load profile, units, constraints, environmental data provenance.
- Write **new** implementations of generation and battery models based on appropriate references.
- Use Flask backend and independently authored interfaces.
- Establish tests for energy balance, state of charge, and reliability calculations.

## Phase 2 — Reimplement optimization
- Formulate capacity decisions and reliability constraints from permitted architecture and public references.
- Integrate SciPy HiGHS LP, configuration enumeration and feasibility pruning in independently authored code.
- Build a chronological 8,760-hour evaluation path and reconcile annual versus hourly metrics.
- Validate consistency of CAPEX, OPEX, LCOE and LPSP outputs.

## Phase 3 — Build modern interface
- React + TypeScript frontend: location selection, configurable renewable mix, result KPIs, plots and ranked configurations.
- Flask API connecting UI to independently implemented scientific modules.
- Model disclosures and CSV/PDF reports.

## Phase 4 — Broaden geographical and policy scope
- Add supported sites beyond the initial island set; validate Brest France using appropriate local resource assumptions.
- Add terrestrial and marine technologies only with scientifically valid local datasets.
- Introduce 3D globe, scenario comparison, policymaker-oriented planning and multi-year analysis.

## Publication quality bar
- Only publish new source code that the team has rights to release.
- Demonstrate installation, tests and repeatable runtime examples.
- Document synthetic versus authoritative data.
- Do not claim all planned features are working until tested.
