# MEML 75 (v5.2)

Phenomenological model of the fermion sector of the Standard Model
from T²/ℤ₃ geometry with modular A₄ symmetry.

[![arXiv](https://img.shields.io/badge/arXiv-XXXX.XXXXX-b31b1b.svg)](https://arxiv.org/abs/XXXX.XXXXX)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Key results

### Strictly derived from first principles
- Bulk coupling constant: **α_G = 2/(3π) = 0.212207**
- Six-dimensional scale: **M₆ = 2.965×10¹⁶ GeV** (= GUT scale)

### Reproduced
- PMNS parameters with accuracy <0.5%
- Quark sector: 11 parameters → 9 observables, χ² ~ 10⁻¹⁶

### Conditional predictions (given ε = 2.86×10⁻⁴)
- Axion mass: m_a = 28.22 μeV
- Axion frequency: ν_a = 6.824 GHz (ADMX range)
- Dark matter: Ω_a h² = 0.12 at θ_i = 1.112 (Planck 2018)

## Installation

### Requirements
- Python ≥ 3.10
- numpy, scipy

### Install dependencies
\`\`\`bash
pip install -r code/requirements.txt
\`\`\`

## Usage

### Run calculation
\`\`\`bash
python code/calc_honest_final.py
\`\`\`

Expected output:
\`\`\`
α_G   = 0.2122065908 = 2/(3π)
M_6   = 2.9646e+16 GeV  (= GUT)
m_a   = 28.2235 μeV
ν_a   = 6.8244 GHz  (ADMX)
θ_i   = 1.1120 → Ω_a h² = 0.12
\`\`\`

### Compile paper

**Russian version:**
\`\`\`bash
cd paper
xelatex MEML_75_honest_final.tex
xelatex MEML_75_honest_final.tex
\`\`\`

**English version:**
\`\`\`bash
cd paper
xelatex MEML_75_honest_EN.tex
xelatex MEML_75_honest_EN.tex
\`\`\`

## Repository structure

- `paper/` — LaTeX sources and PDFs of both versions
- `code/` — Python calculation scripts
- `submission/` — cover letter and referee response
- `docs/` — additional documentation

## Honest limitations

The model has the following limitations (explicitly stated in the paper):

1. **Only α_G is derived from first principles.**
2. **ε is not derived from geometry** (30+ combinations tested).
3. **Moduli τ_u, τ_d are not stabilized** (simple KKLT does not work).
4. **Quark sector is not predictive** (11 parameters / 9 observables).
5. **θ_i is not predicted by the model** (dark matter consistency
   at natural O(1) value).

## Citation

If you use this code or results, please cite:

\`\`\`bibtex
@article{Yurov2026MEML75,
  author = {Yurov, D. V.},
  title = {Model MEML 75: Phenomenological Model of the Fermion Sector
           of the Standard Model from T²/ℤ₃ Geometry},
  year = {2026},
  eprint = {arXiv:XXXX.XXXXX},
  archivePrefix = {arXiv},
  primaryClass = {hep-ph}
}
\`\`\`

## License

- Code: MIT License (see LICENSE)
- Paper: CC BY 4.0

## Contact

D. V. Yurov — [yurovdm@yandex.ru)