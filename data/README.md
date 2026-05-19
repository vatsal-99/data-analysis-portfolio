# Data Directory

This folder contains datasets used across the portfolio projects.

---

## Included in This Repository

| File | Project | Description |
|------|---------|-------------|
| `USA_Housing.csv` | Housing Price Prediction | 5,000 US housing records with area income, house age, rooms, population, and price |
| `Ecommerce Customers` | E-commerce Customer Analysis | 500 customer records with session length, app/web usage, membership duration, and yearly spend |
| `titanic_train.csv` | Titanic Survival Prediction | 891 passenger records with survival label, class, age, sex, fare, and embarkation port |

> **Note:** `Ecommerce Customers` has no `.csv` extension but is a standard comma-separated file. Open it with `pd.read_csv('data/Ecommerce Customers')`.

---

## Download Separately (Kaggle)

These datasets are not included due to size or licensing restrictions.

### 911 Calls Dataset
- **Source:** [Kaggle — Montgomery County 911 Calls](https://www.kaggle.com/mchirico/montcoalert)
- **Used in:** `notebooks/911_Calls_Analysis.ipynb`
- **Filename after download:** `911.csv`
- **Place in:** `data/911.csv`

---

## Financial Data

The Finance analysis notebook (`Finance_Data_Analysis.ipynb`) fetches stock data programmatically via `pandas-datareader`. No manual download is required — run the notebook with an internet connection and the data will be retrieved automatically.

**Stocks analysed:** BAC, C, GS, JPM, MS, WFC (2006–2016)
