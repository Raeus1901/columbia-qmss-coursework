# Columbia QMSS — Coursework

M.A. Quantitative Methods in the Social Sciences, Columbia University (GPA 3.92, 2024)

## Modules

| Folder | Topics |
|--------|--------|
| `Bayesian Statistics` | Normal/Gaussian density · Beta-Binomial · Zero-Inflated Poisson · Hierarchical models |
| `Data Science` | Visualisation · Regression · Double-interaction variables · Logistic models · Pooled OLS |
| `Machine Learning` | Penalized regression · Classifiers · K-Means/PCA · Neural networks (Keras) |
| `Natural Language Processing` | VADER · NLTK classifiers · Scikit-learn Reddit classifier |
| `Social Network Analysis` | Ego-network measures · Centrality · Community detection |
| `Time Series Analysis` | Panel data · Survival analysis (Cox) · ARIMA |

---

## Featured labs

### NLP — STEM/Non-STEM classifier (RateMyProfessor, 1M+ comments)
TF-IDF vectorisation → Chi² feature selection → Random Forest.
Stemmed pipeline: **76.4% accuracy / 0.762 ROC-AUC** — best of 3 preprocessing strategies (clean / stem / lemma).
Stack: `sklearn` · `VADER` · `nltk` · `pickle`

### Bayesian Statistics — Defective grenades (Monte Carlo, N=10M draws)
Beta-Binomial prior (α=6, β=94) on a lot of 100 grenades, n=31 sampled.
P(k=2 defective) = **18%** · P(≤3 safe remaining from 69) = **63%**.
Stack: `R` · `extraDistr` · `dplyr`

### Machine Learning — Full curriculum final
MLP vs CNN (Keras/TensorFlow), Ridge/Lasso, Random Forest, PCA, K-Means, TF-IDF.
Key finding: unsupervised = "debug mode" — removes multicollinearity before supervised training.
Stack: `TensorFlow` · `sklearn` · `numpy`

---

**Jean Treves** — [LinkedIn](https://www.linkedin.com/in/jean-treves-bbaa91257/) · [GitHub](https://github.com/Raeus1901)

> Master thesis (FinBERT × SARIMAX): [finbert-sarimax-energy-forecasting](https://github.com/Raeus1901/finbert-sarimax-energy-forecasting)
