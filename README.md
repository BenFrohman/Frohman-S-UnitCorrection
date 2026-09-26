# Frohman-S-UnitCorrection

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
