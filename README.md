

---

```markdown
# GNN-Based Prediction of Lattice Material Isotropy

This project explores the use of **Graph Neural Networks (GNNs)** for predicting the mechanical isotropy of 2D lattice metamaterials using graph-based representations. It compares baseline models (MLP, XGBoost) and implements a two-phase GNN pipeline combining classification and regression.

## 📁 Project Structure

```

.
├── data/
│   ├── cm-features.csv               # Geometric and topological features
│   └── cm-mechanical property.csv    # Ground truth mechanical property (isotropy)
├── scripts/
│   └── main.py                       # Training + evaluation pipeline
├── figures/
│   ├── fig\_scatter.png               # Scatter plot: predicted vs actual
│   └── fig\_residuals.png             # Residual histogram
├── report/
│   └── final\_report.tex              # Project report (LaTeX source)
├── requirements.txt                  # Python dependencies
└── README.md                         # This file

````

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/lattice-isotropy-gnn.git
cd lattice-isotropy-gnn
````

### 2. Install Dependencies

We recommend using a virtual environment:

```bash
pip install -r requirements.txt
```

### 3. Add the Dataset

Due to GitHub file size limits, please manually place the following two CSV files in the `data/` directory:

* `cm-features.csv`
* `cm-mechanical property.csv`

These files should match the schema used in the report.

### 4. Run the Pipeline

```bash
python scripts/main.py
```

This will:

* Load data and construct graph objects;
* Train a two-phase GNN (classifier + regressor);
* Evaluate performance on the test set;
* Generate prediction scatter plots and residual histograms in `figures/`.

## 📊 Results

Best model performance on the test set:

* **MAE**: 843.7
* **R²**: 0.856

Visualizations are saved to `figures/` and included in the LaTeX report.

## 📄 Report

The technical report summarizing methodology, results, and analysis is provided in `report/final_report.tex`.

## 📚 References

If you use this codebase, please cite the following relevant references:

* \[1] Xu et al., “How Powerful Are Graph Neural Networks?”, ICLR 2019.
* \[2] Chen & Guestrin, “XGBoost: A Scalable Tree Boosting System”, KDD 2016.
* \[3] Fey & Lenssen, “Fast Graph Representation Learning with PyTorch Geometric”, ICLR Workshop 2019.

## 📬 Contact

For questions or feedback, feel free to open an issue or email: `Jzhan715@gmail.com`

```


```
