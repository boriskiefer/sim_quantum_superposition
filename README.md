# Superposition Demo (Single-Qubit Unitary)

Interactive Jupyter notebook with sliders for **theta**, **phi**, and **lambda**.  
Displays pre-built/custom unitary matrices, eigenvalues/eigenvectors, and histogram outputs (`p_theo`, `p_samp`, counts).

**Version:** v1.1  
**Date:** 2026-02-11

---

## Requirements

- Python >= 3.12
- numpy >= 1.26.4
- matplotlib >= 3.10.0
- ipywidgets >= 8.1.5
- jupyterlab

---

## Package contents

- `sim_superposition.ipynb`
- `requirements.txt`
- `README.md`

---

## Run (Jupyter-only)

1. Start JupyterLab.
2. Open `sim_superposition.ipynb`.
3. In the first code cell, run:

    %pip install -r requirements.txt  
    %pip install ipywidgets

4. In JupyterLab, click Kernel -> Restart Kernel.
5. In JupyterLab, click Run -> Run All Cells.
6. Execute all cells in sequence.

---

## Expected successful run

- Slider widgets appear for theta, phi, and lambda.
- Unitary matrix and eigensystem outputs are shown.
- Histogram updates with theoretical and sampled probabilities plus counts.

---

## Usage

Interactive sliders control single-qubit unitary parameters (θ, φ, λ). The simulator displays:
- Theoretical and sampled measurement probabilities
- Outcome histogram with counts
- Analyzer basis states

Pedagogical activities and assessment rubric are provided in the manuscript.
