# Medical Insurance Charges — EDA & Prediction

A beginner-friendly machine learning project exploring medical insurance charges and comparing regression models.

## Objective
Explore the dataset and estimate insurance charges from age, BMI, number of children, sex, smoking status, and region.

## Workflow
1. Data loading and validation
2. Exploratory data analysis
3. Duplicate and data-quality checks
4. Train/test split
5. Pipeline-based preprocessing
6. Baseline, Linear Regression, Ridge Regression, and Random Forest comparison
7. Test-set evaluation and residual analysis

## Dataset
Place `insurance.csv` in the same directory as `insurance_charges_analysis.ipynb`.

Expected columns: `age`, `sex`, `bmi`, `children`, `smoker`, `region`, `charges`.

Only include the dataset in this repository if its license and source terms allow redistribution. Otherwise, document the source and instructions for obtaining it.

## Run locally
```bash
python -m venv .venv
# Windows:
.venv\\Scripts\\activate
# macOS/Linux:
# source .venv/bin/activate

python -m pip install --upgrade pip
python -m pip install numpy pandas matplotlib seaborn scikit-learn jupyter
jupyter notebook
```

Open `insurance_charges_analysis.ipynb`, then choose **Kernel → Restart Kernel and Run All Cells**.

## Evaluation
The notebook reports MAE, RMSE, and R² on a held-out test set. Results depend on the dataset and software versions; run the notebook to produce the actual scores.

## Important note
This is an educational project, not a production insurance pricing tool. The data may not represent all populations, and correlations do not prove causation.
