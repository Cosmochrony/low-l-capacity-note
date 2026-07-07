# Low-Multipole Suppression from Distinguishable-History Capacity

Short result note of the Cosmochrony programme (bib key `Beau2026dhc`).

Replaces the phenomenological low-ell envelope of the white-paper appendix (two free parameters,
illustrative comparison) by a parameter-free distinguishable-history mechanism: the largest angular
modes probe the first admissibility ranks, which contain only 3, 7, 17 distinguishable projective
histories (canonical Pell count of the trajectory-branching note).
A 2x2 grid of no-fit envelopes {Bessel, capacity-ratio} x dictionaries {H-dict, Pell-rate},
anchored only by n=1 <-> ell=2, is tested against Planck 2018 TT/TE/EE with no fitting: every cell
improves TT (chi2 27.4 -> 17.3 for the theoretically preferred cell), TE neutral, EE mildly
disfavoured (open transfer treatment).
The 8/3 S3 fibre-to-base stiffness witness is re-audited (2.666993 +/- 0.001188 at 10^6 samples)
and carries its own observable, the modulation ratio sqrt(8/3) ~ 1.633.
Since v1.3.0 the entropy-to-power step is carried by the companion projection-kernel note
``Projection as Conditional Expectation and the Capacity Ceiling''
(concept DOI [10.5281/zenodo.21227547](https://doi.org/10.5281/zenodo.21227547)): the Bessel
envelope is the exact capacity ceiling (N-1)/N of a complex Gaussian mode on N distinguishable
histories, proved given the kernel hypotheses; open items are the TE/EE transfer treatment, the
1.633 modulation search, and the ceiling-saturation question.

## Build

```bash
bash compile.sh
# Output: out/LowLCapacity.pdf
```

## Numerical companion

`simulation/cosmology/lowl_capacity_grid.py` (grid + figures) and
`simulation/spectral/convergence_8_3.py` (S3 witness), same workspace.

## Status

Deposited on Zenodo, version 1.4.0.
Concept DOI: [10.5281/zenodo.21204352](https://doi.org/10.5281/zenodo.21204352).
