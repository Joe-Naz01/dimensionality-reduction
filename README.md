# Dimensionality Reduction — PCA & Truncated SVD

**Problem.** High-dimensional datasets are often hard to interpret or visualize. This project explores linear dimensionality reduction to compress data while retaining maximum variance.

**Data.** Numerical datasets containing multiple correlated features (e.g., images, sensor data, or tabular samples).

**Approach.**
- Applied **Principal Component Analysis (PCA)** for feature extraction and variance visualization.
- Used **Truncated SVD** for sparse or large-scale data where full PCA is computationally heavy.
- Visualized explained variance ratios to select optimal component counts.
- Demonstrated 2D/3D projections for intuitive pattern recognition.

**Results (qualitative).**
- Most information captured by first few principal components.
- PCA projections revealed structure hidden in high-dimensional space.
- Truncated SVD offered faster approximation with minimal performance loss.

**What I Learned.**
- How PCA decomposes variance via eigenvalues and eigenvectors.
- Practical trade-offs between full PCA and truncated variants.
- How dimensionality reduction aids visualization, noise removal, and feature engineering.

## Quick Start
```bash
git clone https://github.com/Joe-Naz01/dimensionality-reduction.git
cd dimensionality-reduction
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
