# Data Analysis & Machine Learning Portfolio

> Real-world projects demonstrating end-to-end data analysis, statistical modeling, and machine learning implementation

**Vatsal Chandrani** | Full Stack Developer + Data Analyst  
📧 vatsalchandrani99@gmail.com | 🌐 [vatsalchandrani.me](https://vatsalchandrani.me) | 💼 [LinkedIn](https://linkedin.com/in/vatsal-chandrani)

---

## About This Portfolio

This repository showcases 5 comprehensive data analysis and machine learning projects built using Python. Each project demonstrates practical problem-solving skills, from exploratory data analysis to building predictive models that deliver actionable business insights.

**What makes these projects different:**
- Real datasets from Kaggle and industry sources
- Complete analysis pipeline from data cleaning to insights
- Business context and real-world applications
- Clean, well-documented code
- Actionable recommendations based on findings

---

## Projects Overview

### 🚨 [911 Emergency Calls Analysis](notebooks/911_Calls_Analysis.ipynb)

**The Challenge:** Emergency services need to understand call patterns to optimize resource allocation and response times.

**What I Did:**
- Analyzed thousands of 911 emergency calls from Montgomery County, PA
- Identified temporal patterns (peak hours, days, seasonal trends)
- Visualized call distribution across emergency types (EMS, Fire, Traffic)
- Mapped geographic hotspots for different emergency categories

**Key Insight:** Emergency call volume shows predictable patterns that can inform staffing decisions. For example, EMS calls peak during specific hours while traffic incidents cluster around rush hours.

**Impact:** This type of analysis helps dispatch centers allocate resources efficiently and reduce response times during high-demand periods.

**Technical Highlights:**
- Time series decomposition and trend analysis
- Geospatial visualization using location data
- Multi-dimensional data aggregation
- Statistical pattern recognition

**Tech Stack:** Python · Pandas · NumPy · Matplotlib · Seaborn

---

### 💰 [E-commerce Customer Spend Prediction](notebooks/Ecommerce_Customer_Analysis.ipynb)

**The Business Problem:** An e-commerce company wants to decide whether to focus development resources on their mobile app or website.

**What I Did:**
- Built a linear regression model to predict customer yearly spending
- Analyzed correlation between platform usage (mobile vs web) and revenue
- Examined customer session length, membership duration, and engagement metrics
- Evaluated model performance using R-squared, RMSE, and MAE

**Key Insight:** Discovered which platform features drive higher customer lifetime value, providing clear direction for product investment.

**Business Impact:** Data-driven recommendation on where to allocate development budget for maximum ROI.

**Technical Highlights:**
- Feature engineering and selection
- Multiple linear regression modeling
- Residual analysis for model validation
- Business metric interpretation

**Tech Stack:** Python · Pandas · NumPy · Scikit-learn · Matplotlib · Seaborn

---

### 📈 [Financial Market Analysis](notebooks/Finance_Data_Analysis.ipynb)

**The Goal:** Analyze stock market trends and calculate financial metrics to inform investment decisions.

**What I Did:**
- Performed comprehensive technical analysis on historical stock data
- Calculated moving averages (SMA, EMA) and volatility metrics
- Analyzed trading volume patterns and price momentum
- Compared performance across multiple stocks
- Computed risk-return ratios

**Key Insight:** Identified clear buy/sell signals using technical indicators and uncovered risk patterns across different market conditions.

**Real-World Use:** This analysis mirrors what financial analysts and algorithmic trading systems use for investment strategy development.

**Technical Highlights:**
- Time series analysis of financial data
- Technical indicator calculation
- Statistical analysis of returns and volatility
- Comparative performance analysis

**Tech Stack:** Python · Pandas · NumPy · Matplotlib · Financial APIs

---

### 🏠 [Housing Price Prediction Model](notebooks/Housing_Price_Prediction.ipynb)

**The Challenge:** Predict house prices based on property features and area characteristics.

**What I Did:**
- Built a multiple linear regression model using USA housing dataset
- Analyzed relationships between price and features (area income, house age, rooms, population)
- Performed feature correlation analysis and multicollinearity checks
- Validated model assumptions through residual analysis
- Evaluated prediction accuracy using standard regression metrics

**Key Insight:** Average area income and number of rooms are the strongest predictors of house price, with the model achieving high R-squared accuracy.

**Real-World Application:** Real estate companies use similar models for automated property valuation, helping buyers assess fair market value and sellers price competitively.

**Technical Highlights:**
- Multiple linear regression
- Feature correlation matrix analysis
- Residual distribution analysis
- Cross-validation techniques

**Tech Stack:** Python · Pandas · NumPy · Scikit-learn · Matplotlib · Seaborn

---

### 🚢 [Titanic Survival Prediction](notebooks/Titanic_Survival_Prediction.ipynb)

**The Classic ML Challenge:** Predict passenger survival using demographic and ticket information.

**What I Did:**
- Built a logistic regression classifier from scratch
- Handled missing data through intelligent imputation strategies
- Engineered features from existing variables (family size, title extraction)
- Evaluated model using accuracy, precision, recall, and confusion matrix
- Analyzed feature importance to understand survival factors

**Key Findings:**
- Gender was the strongest predictor (women-and-children-first protocol)
- Passenger class significantly affected survival odds
- Age and family size showed non-linear relationships with survival

**Why This Matters:** Beyond the historical context, this project demonstrates the complete machine learning workflow — data preprocessing, feature engineering, model training, and evaluation.

**Technical Highlights:**
- Binary classification with logistic regression
- Handling missing data strategically
- Feature engineering (creating new variables from existing ones)
- Model evaluation with multiple metrics

**Tech Stack:** Python · Pandas · NumPy · Scikit-learn · Matplotlib · Seaborn

---

## Technical Skills Demonstrated

**Programming & Tools:**
- Python (Pandas, NumPy, Scikit-learn)
- Jupyter Notebooks
- Git & GitHub

**Data Analysis:**
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Data Cleaning & Preprocessing
- Feature Engineering

**Machine Learning:**
- Linear Regression (Simple & Multiple)
- Logistic Regression (Classification)
- Model Evaluation & Validation
- Cross-validation techniques

**Visualization:**
- Matplotlib
- Seaborn
- Statistical plotting
- Time series visualization

**Domain Knowledge:**
- Business analytics
- Financial analysis
- Real-time systems (connects to my full-stack background)
- Data-driven decision making

---

## How to Run These Projects

### Prerequisites
```bash
Python 3.8+
Jupyter Notebook
```

### Installation
```bash
# Clone this repository
git clone https://github.com/vatsal-99/data-analysis-portfolio.git
cd data-analysis-portfolio

# Install required packages
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```

### Dataset Setup

**Included in repo** (ready to use):
- E-commerce customer data
- USA housing data

**Download separately** (from Kaggle):
- [911 Calls Dataset](https://www.kaggle.com/mchirico/montcoalert) → place in `data/` folder
- [Titanic Dataset](https://www.kaggle.com/c/titanic/data) → place in `data/` folder

See [`data/README.md`](data/README.md) for detailed instructions.

---

## Why I Built This Portfolio

I'm a Full Stack Developer with 5+ years of enterprise experience, and I built these projects to demonstrate my analytical and data science capabilities alongside my software development skills. 

**My unique combination:**
- Strong software engineering foundation (React, .NET, Node.js)
- Data analysis and machine learning skills
- Experience working on mission-critical systems (US law enforcement platform)
- Business-minded approach to technical problems

I'm currently expanding my skills into AI integration (Claude API, OpenAI) to build intelligent, data-driven applications.

---

## What's Next

I'm actively working on:
- Integrating AI capabilities (RAG systems, LLMs) into full-stack applications
- Building predictive models for real-time systems
- Exploring deep learning applications

---

## Let's Connect

I'm open to opportunities in:
- Full Stack Development with AI/ML integration
- Data Analysis & Business Intelligence
- Senior Developer roles at product companies

**Reach out:**
- 📧 Email: vatsalchandrani99@gmail.com
- 💼 LinkedIn: [linkedin.com/in/vatsal-chandrani](https://linkedin.com/in/vatsal-chandrani)
- 🌐 Portfolio: [vatsalchandrani.me](https://vatsalchandrani.me)

---

## License

These projects are for educational and portfolio demonstration purposes. Datasets are from public sources (Kaggle) and are used under their respective licenses.

---

⭐ **If you found these projects helpful or interesting, consider giving this repo a star!**