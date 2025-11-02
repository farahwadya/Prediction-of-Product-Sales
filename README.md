# Prediction of Product Sales
This project aims to predict product sales. It analyzes the relationship between various factors such as product type, outlet type, visibility, price, and advertising to forecast sales performance.

# Data Cleaning & Preprocessing
- Handled missing values in Item_Weight using group-based max.
- Filled missing Outlet_Size values based on most common size per Outlet_Type.
- Standardized Item_Fat_Content values (e.g., 'LF' → 'Low Fat').
- Removed duplicates and ensured consistency of categorical columns.

# Data exploration
1. Item Visibility vs Outlet Sales based on outlet type:<br>

<img width="589" height="455" alt="Item Visibility vs Outlet Sales" src="https://github.com/user-attachments/assets/e2146326-5db2-4e95-932f-34de3803ec35" />
<br>

- sales are clearly higher in Supermarkets compared to Grocery Stores, while Visibility alone is not a strong indicator, as some products sell well even with low visibility.
- For prediction models, it is recommended to include other features such as Item_MRP, Item_Type, and Outlet_Type alongside Visibility.


2. Distribution of Item Fat Content:<br>

<img width="580" height="455" alt="Distribution of Item Fat Content" src="https://github.com/user-attachments/assets/35163e25-0559-45ec-89eb-68c20be519d5" /><br>

count of low fat are higher than count of regular fat
<br>

3. Cumulative Distribution of Item Outlet Sales Analysis
<img width="512" height="405" alt="image" src="https://github.com/user-attachments/assets/1753deb1-2127-42c1-a7e7-2461d54165a0" />

- The plot above displays the Cumulative Distribution Function (CDF) of Item Outlet Sales, which is a key tool for understanding the proportion of products achieving a certain sales level.

 Key Insights:
Concentration:

- Approximately 80% of the products achieve sales of less than 4000.

- This indicates that the vast majority of items fall within the low-to-medium sales bracket.

Skewness / Variation (Spread):

- The gradual flattening of the curve after the $$$4000 mark signifies that a very small proportion of items (roughly 20%) generate the high sales figures (exceeding $$$4000).

- These high sales are spread over a wide range, suggesting the presence of a few 'High-Performing Items' that significantly contribute to the overall average sales.
# Recommindation:


Based on the analysis of **Fat Content Distribution** and the **Cumulative Distribution Function (CDF)** of *Item Outlet Sales*, the following recommendations are suggested:

1. **Prioritize Low-Fat Products**
   - Low-fat items are more frequent in the dataset, indicating higher customer preference or availability.
   - Maintain strong stock levels and ensure visibility for low-fat products in outlets.

2. **Enhance Sales of Regular-Fat Items**
   - Launch targeted promotions or discount strategies to boost the sales of regular-fat products.
   - Educate consumers on the benefits and taste profile to improve demand balance.

3. **Focus on High-Performing Items**
   - Approximately **20% of items** generate the majority of total sales.
   - Allocate more marketing resources, shelf space, and distribution support to these high-performing products.

4. **Optimize Low-to-Medium Sales Products**
   - Around **80% of products** record sales below \$4000.
   - Reassess pricing, packaging, or placement to improve performance.
   - Consider phasing out persistently underperforming products to reduce inventory costs.

5. **Apply Differentiated Strategies**
   - The sales distribution is **right-skewed**, meaning few products dominate the market.
   - Develop product-specific strategies rather than applying a one-size-fits-all approach to maximize efficiency and revenue.

---




