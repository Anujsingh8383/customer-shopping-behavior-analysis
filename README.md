# 🛍️ Customer Shopping Behavior & Trend Analysis

## 📌 Project Overview
An end-to-end data analytics project examining **3,900 customer transactions** across various product categories, seasons, and customer segments. The analysis focuses on understanding category demand, repeat purchase cadences, promotional discount impacts, and subscription economics to deliver actionable commercial insights.

---

## 🛠️ Tech Stack & Tools
* **SQL (MSSQL / PostgreSQL):** Business KPI aggregation, window functions (`ROW_NUMBER()`), conditional segmentation (`CASE` statements), and CTEs.
* **Power BI:** Interactive dashboard modeling, DAX measures, and category-level drill-downs.
* **Gamma:** Executive presentation design and commercial storytelling.

---

## 🔍 Key Business Questions Solved via SQL
1. **Revenue Distribution:** Revenue split across gender demographics and age segments.
2. **Discount Efficiency:** Identification of high-value basket sizes despite discount utilization.
3. **Assortment Rating:** Top-performing products based on customer review metrics.
4. **Logistics vs Spend:** Purchase volume and average order value (AOV) comparison across Standard vs. Express fulfillment.
5. **Subscription Economics:** Comparative spend dynamics between subscribers (27%) and non-subscribers (73%).
6. **Customer Regularity:** Customer segmentation into *New*, *Returning*, and *Loyal* cohorts using window aggregation.
7. **Category Leaders:** Top 3 ordered items per retail category using partition rankings.

---

## 📊 Key Insights & Findings
* **Clothing Dominance:** Clothing represents the largest demand share (~1.74k purchases, $104k revenue), followed by Accessories, while footwear and outerwear remain stable niche drivers.
* **Consistent Basket Size:** Average Order Value (AOV) hovers remarkably steady at **~$59.76** across categories and age demographics.
* **Seasonality:** Fall leads overall spend ($60k) and average ticket size ($61.6), while transaction volume remains well-balanced across all four quarters (~1,000 orders/season).
* **Subscription Gap:** 27% of customers are subscribed ($59.49 average spend vs $59.87 for non-subscribers), indicating an opportunity to enhance subscription perks and retention.

---

## 💡 Strategic Recommendations
1. **Protect the Core Assortment:** Leverage clothing and accessories as continuous volume drivers.
2. **Cross-Selling Strategies:** Attach footwear and accessories to clothing checkouts to lift overall basket sizes above the current $60 threshold.
3. **Cadence-Driven Retention:** Deploy automated marketing triggers aligned with primary repurchase cadences (Monthly, Quarterly, 3-Month replenishment).

---

## 📁 Repository Contents
* `/sql/`: Contains `.sql` scripts with all analytical queries and data transformation logic.
* `/dashboard/`: Contains the Power BI `.pbix` file.
* `/presentation/`: Executive slide deck summarizing commercial actions.
