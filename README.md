# Coffee Shop Sales – Microeconomic Analysis  


---

## Problem  
Coffee shops face demand fluctuations influenced by price, product mix, location, and time of day. This project applies **microeconomic theory** to transaction-level sales data (149k+ records) to understand consumer behavior and estimate **price elasticity, complements/substitutes, and temporal demand patterns**.  

---

## Objectives  
- Estimate **price elasticity of demand** for coffee and related products.  
- Identify **complementary or substitute relationships** (e.g., coffee and bakery items).  
- Analyze **temporal demand** (by hour of day, weekday vs weekend).  
- Compare consumer demand across **store locations**.  
- Translate results into **business-relevant insights**.  

---

## Approach  
1. **Data Preparation**  
   - Cleaned and validated 149,000+ transaction records.  
   - Extracted time features (hour, weekday).  
   - Constructed variables for demand (quantity), price, and complements.  

2. **Modeling**  
   - **Price Elasticity Model**: log-log regression of quantity vs unit price.  
   - **Complement/Substitute Test**: coffee demand with bakery purchases as dummy variable.  
   - **Temporal Model**: regressions with hour and weekday indicators.  
   - **Location Segmentation**: regressions with store-level effects.  

3. **Visualization**  
   - Price vs quantity scatter (approximate demand curve).  
   - Hourly sales line chart.  
   - Weekday sales bar chart.  

---

## Findings  
- **Negative price elasticity** confirmed the law of demand: higher prices reduced sales volumes.  
- **Bakery and coffee items behaved as complements** — bakery promotions increased coffee demand.  
- **Morning hours showed significant demand spikes**, consistent with time-constrained preferences.  
- **Store locations differed in intercepts**, showing heterogeneous consumer behavior.  

---

## Skills Demonstrated  
- Data cleaning and feature engineering (Python, Pandas, Numpy).  
- Econometric modeling using **statsmodels**.  
- Microeconomic framing: demand theory, elasticity, complements, preferences.  
- Data visualization (Matplotlib, Seaborn).  
- Reproducible research workflow.  

---

---

## Requirements  
- Python 3.x  
- pandas, numpy, matplotlib, seaborn, statsmodels, openpyxl  

Install via:  
```bash
pip install -r requirements.txt

## Conclusion  
This project highlights how **microeconomic theory** can structure data analysis to produce business-relevant insights. By combining demand modeling, elasticity estimation, and complement/substitute testing with temporal and location-based segmentation, the study revealed actionable patterns in consumer behavior.  

The findings confirmed the **law of demand** (negative price elasticity), identified **coffee–bakery complementarity**, and showed strong **time-of-day demand spikes** as well as **location-driven heterogeneity**.  

Overall, the project demonstrates how integrating **economic reasoning with analytics** transforms raw transaction data into insights that can guide **pricing, promotions, and operational strategies** for coffee shops and similar retail businesses.  

