# 📊 E-Commerce Sales & Profitability Analysis: Optimizing Product Mix and Customer Segments | Python

## Executive Summary  
Using Python, I analyzed transaction data to uncover insights into an e-commerce business’s sales and profitability. By analyzing sales trends, product categories, customer segments, and profit ratios, the project demonstrates how data-driven decision-making can help optimize revenue growth, product performance, and customer targeting strategies.

---

## Business Problem  
Completed purchases are the backbone of revenue for any e-commerce company. However, they face challenges in understanding:  
- Which months drive the highest and lowest sales 📉📈
- Which categories and subcategories contribute the most to revenue and profit
- How profitability varies across customer segments
- Whether sales are translating into sustainable profit margins

**Key Question:**  
👉 *Which products, categories, and customer segments contribute the most to sales but the least to profit, and how can the business optimize its product mix and pricing strategy to improve overall profitability?*  

---

## Methodology  
1. Use Python to clean, transform, and analyze the raw e-commerce dataset for meaningful insights.
2. Build visualizations to track sales, profit, and performance across categories, sub-categories, and customer segments.
3. Conduct advanced analysis, including sales-to-profit ratio evaluation, to identify the best areas of opportunity for business growth.   

---

## Skills Used  
- **Python:** Pandas (groupby, merges, filtering).  
- **EDA & Visualization:** Pyplot
- **Statistical Analysis:** Customer segmentation, revenue contribution analysis.  
- **Data Cleaning:** Expanding the dataset and modifying columns  

---

## Results & Business Recommendations  
Key Findings:  
-  **Monthly Sales**: Peak sales occurred in November, lowest in January.
-  **Category Performance**: Balanced performance across categories.
-  **Profitability**: Despite high sales, some subcategories had low margins, impacting overall profit.
- **Customer Segments**: Consumer Segment was the most profitable group, showing where marketing dollars should focus.

**Business Recommendations:**  
- Leverage Technology – Since Technology shows the highest sales share, introduce premium offerings and targeted campaigns to further strengthen this lead.
- Improve Margins in Furniture - Although sales is balanced, contribution of furniture to profit is nominal. Focusing on higher-margin products within these categories can boost profitability.
- Bundle Strategies – Promote cross-category bundles (e.g., office furniture + technology products) to increase average order value.
- Customer Segmentation – Align marketing campaigns by segment to push underperforming products in each category to the right audience.

---

## Next Steps  
- Build a Power BI dashboard for real-time visualization.
- Perform predictive modeling (ML) to forecast monthly sales.
- Segment customers further using RFM (Recency, Frequency, Monetary) Analysis.
- Test dynamic pricing strategies to optimize the sales-to-profit ratio.

**Limitations:**  
- Dataset does not include customer demographics.  
- No marketing campaign data was available, limiting attribution analysis.  

---

## Project Structure 
ecommerce-analytics-python/

│── data/
│   └── ecommerce_sales.csv        
│── notebooks/
│   └── ecommerce_analysis.ipynb   
│── reports/
│   └── charts/                    
│── README.md                      
│── requirements.txt               

