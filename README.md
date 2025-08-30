# coffee-shop-demand-analysis
Problem

Coffee shops face demand fluctuations influenced by price, product mix, location, and time of day. This project applies microeconomic theory to transaction-level sales data (149k+ records) to understand consumer behavior and estimate price elasticity, complements/substitutes, and temporal demand patterns.

Objectives

Estimate price elasticity of demand for coffee and related products.

Identify complementary or substitute relationships (e.g., coffee and bakery items).

Analyze temporal demand (by hour of day, weekday vs weekend).

Compare consumer demand across store locations.

Translate results into business-relevant insights.

Approach

Data Preparation

Cleaned and validated 149,000+ transaction records.

Extracted time features (hour, weekday).

Constructed variables for demand (quantity), price, and complements.

Modeling

Price Elasticity Model: log-log regression of quantity vs unit price.

Complement/Substitute Test: coffee demand with bakery purchases as dummy variable.

Temporal Model: regressions with hour and weekday indicators.

Location Segmentation: regressions with store-level effects.

Visualization

Price vs quantity scatter (approximate demand curve).

Hourly sales line chart.

Weekday sales bar chart.

Findings

Negative price elasticity confirmed the law of demand: higher prices reduced sales volumes.

Bakery and coffee items behaved as complements — bakery promotions increased coffee demand.

Morning hours showed significant demand spikes, consistent with time-constrained preferences.

Store locations differed in intercepts, showing heterogeneous consumer behavior.

Skills Demonstrated

Data cleaning and feature engineering (Python, Pandas, Numpy).

Econometric modeling using statsmodels.

Microeconomic framing: demand theory, elasticity, complements, preferences.

Data visualization (Matplotlib, Seaborn).

Reproducible research workflow.

coffee-shop-demand-analysis/
│── Coffee_Shop_Sales_Analysis.ipynb   # Main analysis notebook
│── Coffee Shop Sales.xlsx             # Raw dataset (transactions)
│── README.md                          # Project documentation
│── requirements.txt                   # Python dependencies

Requirements

Python 3.x

pandas, numpy, matplotlib, seaborn, statsmodels, openpyxl


Conclusion

This project demonstrates how microeconomic theory provides structure and analytics provides solutions. By combining regression analysis with elasticity, complementarity, and temporal patterns, the study produced actionable insights for pricing, promotions, and demand management in the coffee retail sector.
