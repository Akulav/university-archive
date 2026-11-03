# Data Analysis Labs: Dimensionality Reduction

Experiments comparing linear and non-linear dimensionality reduction techniques with `scikit-learn`.

## Contents

| File | Description |
| --- | --- |
| `Lab2part1.py` | Swiss-roll dataset: PCA, Locally Linear Embedding (with an error-vs-neighbours sweep), MDS and t-SNE |
| `Lab2part2.py` | Handwritten digits dataset: LLE, Isomap, Spectral Embedding, t-SNE, LDA, random projections and a decision tree classifier |

## Running

```bash
pip install numpy matplotlib scikit-learn
python Lab2part1.py
python Lab2part2.py
```

Both scripts use datasets built into `scikit-learn`, so no extra files are needed.
