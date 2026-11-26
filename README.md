# Titanic Passenger Data Analysis

This project explores the Titanic passenger dataset using Python, pandas, and seaborn. It includes data inspection, cleaning, exploratory data analysis, visualizations, and the creation of a cleaned CSV file.

## Project Overview

The notebook `archive/MR-GAGAN_G.ipynb` performs the following tasks:

- Loads the Titanic test dataset
- Displays dataset shape, column names, and summary statistics
- Checks for duplicate rows and missing values
- Removes the `Cabin` column
- Fills missing `Age` values with the median age
- Fills missing `Fare` values with the median fare
- Fills missing `Embarked` values with the mode
- Creates a `FamilySize` feature
- Analyzes survival patterns by gender and embarkation location
- Creates visualizations for survival, age, gender, and correlations
- Exports the cleaned dataset as `titanic_cleaned.csv`

## Files

| File | Description |
| --- | --- |
| `archive/MR-GAGAN_G.ipynb` | Main data analysis notebook |
| `archive/tested.csv` | Original passenger dataset used by the notebook |
| `archive/titanic_cleaned.csv` | Cleaned and processed dataset |
| `archive/titanic.csv` | Additional Titanic dataset |
| `archive/titanic1.csv` | Additional Titanic dataset |
| `archive/Untitled.ipynb` | Empty supplementary notebook |
| `archive/MR-GAGAN_G.pdf` | PDF export of the main notebook |

## Dataset

The tested dataset contains 418 passenger records and the following columns:

- `PassengerId`
- `Survived`
- `Pclass`
- `Name`
- `Sex`
- `Age`
- `SibSp`
- `Parch`
- `Ticket`
- `Fare`
- `Embarked`
- `FamilySize`

## Requirements

- Python 3
- Jupyter Notebook or JupyterLab
- pandas
- numpy
- matplotlib
- seaborn

Install the dependencies with:

```bash
pip install pandas numpy matplotlib seaborn
```

## How to Run

1. Clone or download this project.
2. Open a terminal in the project directory.
3. Start Jupyter Notebook:

```bash
jupyter notebook
```

4. Open `archive/MR-GAGAN_G.ipynb`.
5. Run all cells from top to bottom.

The notebook reads `tested.csv` and writes `titanic_cleaned.csv` in the same directory.
