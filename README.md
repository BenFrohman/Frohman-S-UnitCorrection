# Frohman-S-UnitCorrection

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23652986.svg)](https://doi.org/10.5281/zenodo.23652986) [![License: Apache-2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

Author: Benjamin Stanley Frohman  
Copyright (c) 2026 Benjamin Stanley Frohman  
License: Apache-2.0  
Public.

Latest pass of the seed-family work. **Does not overwrite**
[BenFrohman/Frohman-MixedCorrelators-FJ](https://github.com/BenFrohman/Frohman-MixedCorrelators-FJ).
That repo stays the problem statement and the 216-cell ledger.

## What this pass records

The CohFT unit is the generator of the **narrow** \(J\)-sector:

$$
\mathbf{1}_J\in H_J,\qquad \mathrm{Fix}(J)=\{0\},\qquad \deg(\mathbf{1}_J)=0.
$$

It is **not** the Jacobian degree-0 line \(R_0\simeq H^{4,0}\) in the identity sector.

The broad space is exactly

$$
\mathrm{Jac}(F)^{\langle J\rangle},\qquad \dim=2605,
$$

Hilbert \((1,426,1751,426,1)\). There is no \(2604\) complement.

Seed family, still OPEN:

$$
S=\bigl\{
X_{001}(\alpha,\beta,\mathbf{1}_J),\;
X_{010}(\alpha,\mathbf{1}_J,\beta),\;
X_{100}(\mathbf{1}_J,\alpha,\beta)
\bigr\}.
$$

If the CohFT unit axiom applies to broad markings, \(S=\eta\) on the \(2605\)
(blocks \(1\times 1\), \(426\times 426\), \(1751\times 1751\)). That is a pairing
matrix, not \(0\), \(1\), \(6\), or \(1/6\). Until that axiom is cited for this
host, \(S\) stays OPEN. The \(12\) BNN rooms stay OPEN.

Locked ranks: \(25\), \(26\), \(30\).  
Score: \(180\) empty-stack zeros.

## Files

- `docs/UNIT_CORRECTION.md` — dummy withdrawn
- `tables/seeds.csv` — corrected list
- `tables/not_seeds.csv` — dummy fills out
- `tables/broad_grading.csv` — aligned \(181\) + off-diagonal \(2424\) = \(2605\)
- `tables/lefschetz_orthogonality.csv` — two-point, not \(X_{001}\)
- `PARENT.md` — pointer to the problem repo

---
## Archival DOI & Cryptographic Provenance

- **Dedicated 1-to-1 Zenodo DOI:** [10.5281/zenodo.23652986](https://doi.org/10.5281/zenodo.23652986)
- **Author:** Benjamin Stanley Frohman (ORCID: [0009-0006-7068-3718](https://orcid.org/0009-0006-7068-3718))
- **License:** Apache License, Version 2.0 (`Copyright (c) 2026 Benjamin Stanley Frohman`)
- **Earliest Commit Provenance:** `daf1c4ef200de90fa6140eb2bbe6e83081b82ecc` (2026-09-26 03:29:41 AM CDT (UTC-5))
- **SealGuard SHA-256 Merkle Root:** `99e47622c7f2b6ae967252efda873fe68d854649418dd1d0b6053473652b27d2` (`PROVENANCE_MERKLE_ROOT.json`)
- **Titan Audit Certificate:** `audit/TITAN_AUDIT_CERTIFICATE.json` (Ed25519 key `b428fb72676f1c52`)
- **Scope & Scientific Boundary:** Records verified selection-rule and grading corrections for the seed list S and narrow unit insertions; explicitly distinguishes closed seed tables from open Hodge/CohFT conjectures.
