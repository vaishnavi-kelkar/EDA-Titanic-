# Titanic Survival - Exploratory Data Analysis

**Author:** Vaishnavi Kelkar

## Dataset
The Titanic passenger dataset (891 records, 15 attributes) including passenger class, gender, age, fare, family size, and survival status. Sourced from the classic Titanic dataset (via seaborn's built-in dataset).

## Tools Used
- Python (pandas, matplotlib, seaborn)
- Jupyter Notebook

## Steps Performed
1. **Data Cleaning**: Handled missing values in `age` (filled with median) and `embark_town` (filled with mode), dropped the `deck` column (too many missing values), removed duplicates.
2. **Exploratory Analysis**: Examined survival rate overall and across gender, passenger class, age groups, and fare.
3. **Visualization**: Created bar charts, histograms, and box plots to visually compare survival patterns.

## Key Insights
- Overall survival rate was approximately **38%**.
- **Females survived at ~74%** compared to **males at ~19%** — reflecting the "women and children first" evacuation policy.
- **1st class passengers** had a survival rate of **~63%**, compared to **~24% for 3rd class**, showing a strong link between socio-economic status and survival.
- Passengers who paid **higher fares** (correlated with 1st class) had noticeably better survival odds.
- Age distribution shows a slightly higher survival tendency among younger passengers.

## Files
- `Titanic_EDA.ipynb` — full analysis notebook with code, charts, and insights
- `titanic.csv` — dataset used
- `chart_*.png` — exported visualizations

## How to Run
```bash
pip install pandas matplotlib seaborn jupyter
jupyter notebook Titanic_EDA.ipynb
```
