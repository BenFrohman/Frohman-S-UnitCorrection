# Workflows

Author: Benjamin Stanley Frohman  
Copyright (c) 2026 Benjamin Stanley Frohman  
License: Apache-2.0  
Public.

New files under `.github/workflows/`. No overwrite of the parent problem repo.

| File | Trigger | What a green check means |
|---|---|---|
| `docs.yml` | push / PR / manual | LICENSE, README, UNIT_CORRECTION, seed tables exist; `tables/seeds.csv` does not contain dummy fills 0, 1, 6, 1/6 |
| `release.yml` | tag `v*` or `priority-*` | a GitHub Release is published from that tag |

What it does **not** mean: S is evaluated, mixed BBN/BNN numbers exist, or Hodge Term B is closed.

No Lean toolchain on this repo. The Lean recipe lives on NS_Millennium_Proof and HODGE.
