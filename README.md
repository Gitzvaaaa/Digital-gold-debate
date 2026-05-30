# 🪙 Digital Gold Debate

A data analysis project investigating whether **Bitcoin is "digital gold"** — examining its statistical properties, correlations with traditional assets, and behavior as an inflation hedge or safe-haven asset.

---

## 📁 Folder Structure

```
Digital-gold-debate/
├── Notebooks/                  # Jupyter notebooks for analysis & visualization
├── data/                       # Raw and processed datasets
├── report/                     # Final report / figures / outputs
├── .gitignore
├── .python-version             # Python 3.11
├── pyproject.toml              # Project metadata & dependencies (managed by uv)
├── uv.lock                     # Locked dependency versions
└── README.md
```

---

## ⚙️ Requirements

- **Python** ≥ 3.11
- **[uv](https://github.com/astral-sh/uv)** — fast Python package manager (recommended)

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Gitzvaaaa/Digital-gold-debate.git
cd Digital-gold-debate
```

### 2. Install dependencies

Using **uv** (recommended):

```bash
uv sync
```

Or using **pip**:

```bash
pip install -e .
```

### 3. Launch Jupyter

```bash
uv run jupyter notebook
# or
jupyter notebook
```

Then open any notebook inside the `Notebooks/` folder.

---

## 📦 Dependencies

| Package | Purpose |
|---|---|
| `pandas` | Data manipulation & time series |
| `numpy` | Numerical computing |
| `matplotlib` / `seaborn` | Data visualization |
| `statsmodels` | Statistical tests & models |
| `scikit-learn` | Machine learning utilities |
| `arch` | GARCH / volatility modeling |
| `ipykernel` | Jupyter kernel support |

---

## 📝 License

This project is for academic / research purposes.
