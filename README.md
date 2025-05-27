# Product-Value-Predictor
# 🚛 Forecasting Fleet Vehicle Resale Prices: A Data Science Journey from Chaos to Clarity

**Author:** Brandy Horne  
**Tags:** Time Series Forecasting, Data Science, AutoTS, CRISP-DM, Tableau, Business Strategy

---

## 🎯 The Business Problem

The resale value of commercial vehicles is influenced by a tangled web of factors: economic trends, supply chain disruptions, customer behavior, asset specifications, and more. Executives needed **accurate 5-year forecasts** to guide strategic decisions on pricing, inventory management, and asset liquidation.

But existing tools were limited. Most models relied on short-term trends, static assumptions, or oversimplified depreciation curves. We needed a system that was dynamic, explainable, and built for the road ahead.

---

## 🔍 Laying the Groundwork: Understanding the Domain

Before touching data, I immersed myself in the **fleet resale ecosystem**. I explored:

- **Economic indicators** (e.g., inflation, interest rates, fuel prices)
- **Supply and demand cycles** affecting commercial vehicles
- **Internal business processes** — how resale prices impacted broader strategic planning

This domain understanding grounded every decision and helped ensure my modeling work aligned directly with business needs.

---

## 🧠 Data Discovery: More Than Just Rows and Columns

I worked cross-functionally to collect and harmonize a diverse set of data sources:

- **Vehicle specifications:** age, mileage, model, engine type
- **Customer segments:** usage patterns, regional factors
- **External indicators:** economic trends, market conditions

From there, I performed deep **exploratory analysis**—identifying outliers, evaluating feature relationships, and engineering variables like rolling averages and seasonality lags.

---

## 🧹 Cleaning Up the Data Garage

Effective modeling starts with clean, interpretable data. I:

- Removed noise and outliers
- Applied **Variance Inflation Factor (VIF)** to detect multicollinearity
- Created lag features and encoded categorical variables
- Normalized numeric features to align across sources

By this stage, I had transformed a fragmented dataset into a well-tuned forecasting engine.

---

## 🤖 Modeling the Future

### Baseline: ARIMA
I started with a baseline **ARIMA model** to establish expectations and identify key performance gaps. This allowed me to monitor performance over several months and pinpoint areas for improvement.

### Final Model: AutoTS
After extensive benchmarking, I selected **[AutoTS](https://github.com/winedarksea/AutoTS)**—a Python package designed for automated time series modeling and ensembling. It enabled:

- Quick experimentation across model types (ARIMA, LightGBM, Prophet, etc.)
- Ensemble blending for stability
- Built-in anomaly detection and forecast intervals

**Result:** A model with over **15% improvement in accuracy** compared to the baseline, and the flexibility to adapt to evolving market conditions.

---

## 📊 Communicating Insights, Not Just Outputs

Modeling was only half the battle. I built a **Tableau dashboard** for executives to visualize forecasts at a glance—complete with filters for vehicle type, location, and more. Each month, I reported on:

- Model accuracy and trends
- Emerging patterns in resale behavior
- Business implications and strategic recommendations

This transformed the model from a technical artifact into a **decision-making compass.**

---

## 📦 Lessons Learned

1. **Context matters.** Economic and behavioral variables were critical to forecasting accuracy.
2. **Modeling is iterative.** Baselines help you evolve with purpose.
3. **Communication is key.** Dashboards and storytelling made the data actionable.

---

## 🧠 Final Thoughts

This project was more than just a modeling exercise—it was a testament to the value of combining **technical skill**, **strategic thinking**, and **clear communication**. It reminded me that great data science isn’t about the flashiest model—it’s about solving the right problem in the right way.

---

**Contact:**  
[GitHub](https://github.com/brandyanalytics) | [LinkedIn](https://linkedin.com/in/brandyhorne01) | Brandyhorne01@gmail.com  
*Built with 💻 by Brandy Horne | © 2025*
