# MATLAB-SIMULINK- — superseded predecessor

**Status: archived reference. Superseded. The numbers here are not current.**

This repository holds the early Simulink prototype of a site-level EV charging
grid-behavior model, built for a George Mason University Future City Fellowship
project. It is kept public as the historical record of what the later model was
built from — not as a source of planning figures.

## What this is

- `build_and_run_site_grid_behavior_model.m` — the original script that constructs
  and runs the model
- `site_grid_behavior_ev_charging.slx` — the Simulink model it produces
- `site_year_scenarios*.csv` — the scenario inputs it reads
- two rendered figures

## What it is not

- **Not the current model.** A later rewrite replaced this pipeline entirely. That
  work introduced a capacity-provenance guard, session-based demand profiles, an
  energy-aware managed-charging scheduler, and a validated cross-model data contract.
  None of that exists here.
- **Not the current horizons.** This prototype uses a `Now / 2035 / 2050` convention
  that the later work retired in favour of a 2026 baseline with 2036 / 2046 / 2056
  horizons. Any year label in this repository should be read as historical.
- **Not planning-grade output.** Electrical capacity values here are unconfirmed
  planning placeholders. Nothing in this repository is an engineering, permitting,
  utility, or procurement determination, and no figure here should be quoted as a
  current project result.

## Why it is still here

The later model's `matlab/legacy_archive/` refers back to this work, and the file
`build_and_run_site_grid_behavior_model.m` in this repository is byte-identical to
the copy archived there. Deleting this repository would remove the only public
evidence of that lineage. Provenance is worth more than tidiness.

---

*No license has been selected; all rights reserved by the team.*
