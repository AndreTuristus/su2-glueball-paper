# SU(2) Lattice Glueball Mass and String Tension

Reproducibility package for the Zenodo preprint by A. V. Turenko (2026).

## Main Result

m_0++ / sqrt(sigma) |_{a -> 0} = 3.77 +/- 0.40 (stat) +/- 0.16 (sys)

Agrees with Teper benchmark 3.78 +/- 0.16 (chi^2/dof = 0.45).

## Contents

- paper/ -- LaTeX source, compiled PDF, continuum extrapolation figure
- data/ -- raw configurations (.npz) and SHA-256 manifests (.json)
- code/ -- PyTorch implementation (Jupyter notebook)
- SHA256SUMS.txt -- cryptographic verification of all artifacts

## Reproducibility

All numerical experiments run on Kaggle GPU (NVIDIA T4)
in ~20 minutes per ensemble. See code/ for the full pipeline.

## Citation

Turenko, A. V. (2026). Continuum Extrapolation of the Scalar Glueball
Mass in Pure Gauge SU(2) Lattice Field Theory. Zenodo.
DOI: 10.5281/zenodo.XXXXXXX

## License

MIT