

---

```markdown
# GNN-Based Prediction of Lattice Material Isotropy

This project explores the use of **Graph Neural Networks (GNNs)** for predicting the mechanical isotropy of 2D lattice metamaterials using graph-based representations. It compares baseline models (MLP, XGBoost) and implements a two-phase GNN pipeline combining classification and regression.



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


## 📊 Results

Best model performance on the test set:

* **MAE**: 843.7
* **R²**: 0.856

Visualizations are saved to `figures/` and included in the LaTeX report.

## 📄 Report

The technical report summarizing methodology, results, and analysis is provided in `report/final_report.tex`.



## 📬 Contact

For questions or feedback, feel free to open an issue or email: `Jzhan715@gmail.com`

```


```
