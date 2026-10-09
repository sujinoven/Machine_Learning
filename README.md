# Machine Learning Learning Journey

A collection of Python notebooks, datasets, and study materials documenting my hands-on learning in machine learning.

This repository covers data preprocessing, supervised learning, ensemble methods, model evaluation, feature selection, clustering, association rules, recommendation systems, and dimensionality reduction.

## Repository Guide

Folder names below match the repository, including their original spelling and numbering.

| Folder | Contents |
|---|---|
| `01_Intro To ML` | Introduction to machine learning with a car mileage prediction example |
| `02_Linear-Regression` | Linear regression, car mileage prediction, and regression evaluation |
| `03_Logistic_Regression` | Classification using the claimants dataset |
| `04_Decision_Tree` | Decision trees, tree visualization, and classifier experiments |
| `05_Evaluation metrics for Supervised ML Models` | Evaluation reference materials, including R² and adjusted R² |
| `06_Ensemble Techniques` | Random Forest, AdaBoost, and voting classifiers |
| `07_Model Evaluaion Techniques` | Train/test splitting, cross-validation, and grid search |
| `08_Data Preprocessing Techniques` | Preprocessing and categorical encoding using environmental data |
| `10_AdaBoosting Algo Theory` | AdaBoost notebook and supporting illustrations |
| `11_Handling Inbalanced Dataset` | Class imbalance experiments, including class weighting |
| `12_Gradient Boosting` | Gradient Boosting and XGBoost classification |
| `13_LGBM` | Comparison of AdaBoost, Gradient Boosting, XGBoost, and LightGBM |
| `15_K Nearest Neighbour` | KNN classification using the wine dataset |
| `16_Regularization Techniques` | Ridge, Lasso, and Elastic Net regression |
| `17_Feature Engineering` | Model-based feature selection and recursive feature elimination |
| `19.1_Hierarchial Clustering` | Hierarchical clustering using college data |
| `19.2_K-Means Clustering` | K-Means experiments using college and Iris data |
| `20_Association_Rules` | Apriori and association rules using online retail transactions |
| `21_Recommendation Engine` | Movie recommendation notebooks and supporting data |
| `22.1_PCA-Dimensionality Reduction` | PCA using breast cancer data |
| `22.2_t-SNE` | PCA and t-SNE visualization using handwritten digits |
| `Random_Forest` | Random Forest classification and Gradient Boosting regression |

The repository also includes practice notebooks, PDF and Word notes, and images supporting the lessons.

## Selected Examples

- **Car mileage prediction:** Explore relationships between vehicle features and mileage using linear regression.
- **Boosting comparison:** Compare multiple boosting classifiers using `credit_card_clean.csv`.
- **Feature selection:** Experiment with `SelectFromModel` and recursive feature elimination on breast cancer and credit card data.
- **College clustering:** Explore groups using hierarchical clustering and K-Means.
- **Market basket analysis:** Find frequent itemsets and association rules in online retail transactions.
- **Movie recommendations:** Explore user-based collaborative filtering and similarity-based recommendation code.
- **Dimensionality reduction:** Compare lower-dimensional representations using PCA and t-SNE.

## Tools and Libraries

- **Language:** Python
- **Environment:** Jupyter Notebook
- **Data processing:** pandas, NumPy
- **Visualization:** Matplotlib, seaborn
- **Machine learning:** scikit-learn
- **Additional libraries:** SciPy, statsmodels, XGBoost, LightGBM, mlxtend
- **Excel support:** openpyxl for reading the retail dataset

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/sujinoven/Machine_Learning.git
cd Machine_Learning
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

Or on macOS/Linux:

```bash
source .venv/bin/activate
```

### 3. Install the libraries

The repository does not currently include a pinned dependency file. The following commands provide a starting environment based on the notebook imports.

Core libraries:

```bash
python -m pip install notebook pandas numpy matplotlib seaborn scikit-learn scipy
```

Additional libraries for relevant notebooks:

```bash
python -m pip install statsmodels xgboost lightgbm mlxtend openpyxl
```

### 4. Open a notebook

```bash
jupyter notebook
```

Navigate to a topic folder, open its notebook, and run the cells in order.

## Working with the Data

Many notebooks load files using relative paths, such as `Cars.csv` or `claimants.csv`. Keep the notebook’s working directory aligned with the location of its dataset, or update the file path.

Some notebooks use datasets available through scikit-learn. The regularization notebook fetches California housing data, which may require internet access on its first run.

## Suggested Learning Order

1. Start with car mileage prediction and linear regression.
2. Continue with logistic regression, decision trees, and evaluation metrics.
3. Explore preprocessing, cross-validation, and ensemble methods.
4. Study regularization and feature selection.
5. Move to clustering, association rules, and recommendation systems.
6. Finish with PCA and t-SNE.

## Project Status

This is a learning repository containing coursework, practice, and experiments. Notebooks may require small code corrections, path changes, or adjustments for library compatibility. Dependencies are not version-pinned, and a fresh end-to-end run of every notebook has not been verified.

## Author

Maintained by [Sujin Oven](https://github.com/sujinoven) as part of an ongoing machine learning learning journey.
