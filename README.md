# Titanic Survival Prediction — Machine Learning Project

Course-style **binary classification** project: predict whether a passenger **survived** the Titanic disaster from demographic and travel features. The notebook follows a full workflow from exploration through evaluation and interpretation (**Parts A–F**).

## Problem

- **Target:** `Survived` — `0` = did not survive, `1` = survived  
- **Task:** Build and evaluate a supervised **classification** model on tabular passenger data.

## Dataset

Data is loaded **from URL** inside the notebook (no local CSV required):

**[Titanic CSV](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)**

Source: Data Science Dojo public dataset (same link as typical course materials).

## Repository contents

| File | Description |
|------|-------------|
| `titanic_survival_ml_project.ipynb` | Main deliverable: code, visualizations, and written explanations (Parts A–F). |
| `requirements.txt` | Python dependencies for reproducibility. |
| `README.md` | This file. |

## Requirements

- **Python 3.9+** recommended (matches common macOS/Xcode Python setups).  
- Packages: see `requirements.txt` (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `jupyter`).

## Setup

### Option A — Virtual environment (recommended)

```bash
cd bathula_capstoneproject
python3 -m venv .venv
source .venv/bin/activate    # Windows: .venv\Scripts\activate
python3 -m pip install --upgrade pip
python3 -m pip install -r requirements.txt
```

### Option B — User install

```bash
python3 -m pip install -r requirements.txt
```

If `jupyter` is not found after install, add your user scripts directory to `PATH` (macOS example):

```bash
export PATH="$HOME/Library/Python/3.9/bin:$PATH"
```

## How to run

1. Start Jupyter from the project folder:

   ```bash
   jupyter notebook titanic_survival_ml_project.ipynb
   ```

   Or use **JupyterLab**:

   ```bash
   jupyter lab
   ```

2. In the notebook menu: **Kernel → Restart Kernel and Run All**.

3. **Save** the notebook so outputs (tables, metrics, figures) are stored in the `.ipynb` file before submission.

You can also open the notebook in **VS Code / Cursor** and run cells with a selected Python interpreter (ideally the same environment where dependencies are installed).

## Notebook structure (Parts A–F)

| Part | Topic |
|------|--------|
| **A** | Data loading and exploration (shape, dtypes, missing values, numeric summaries). |
| **B** | Preprocessing and feature engineering (imputation, encoding, dropping irrelevant columns, reasoning). |
| **C** | Visualizations: survival counts, gender, age-related patterns + insights. |
| **D** | Train/test split, model training, **justification** of classifier choice. |
| **E** | Evaluation: accuracy, confusion matrix, precision/recall/F1, cross-validation, feature importances. |
| **F** | Results interpretation: performance, errors, causes of mistakes, limitations, improvements. |

## Author

**Bathula Hrishitha**
