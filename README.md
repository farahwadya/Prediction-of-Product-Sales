# Prediction of Product Sales
This project aims to predict product sales. It analyzes the relationship between various factors such as product type, outlet type, visibility, price, and advertising to forecast sales performance.

### Data Cleaning & Preprocessing
- Handled missing values in Item_Weight using group-based max.
- Filled missing Outlet_Size values based on most common size per Outlet_Type.
- Standardized Item_Fat_Content values (e.g., 'LF' → 'Low Fat').
- Removed duplicates and ensured consistency of categorical columns.

### Data exploration
1. Item Visibility vs Outlet Sales based on outlet type
<img width="589" height="455" alt="Item Visibility vs Outlet Sales" src="https://github.com/user-attachments/assets/e2146326-5db2-4e95-932f-34de3803ec35" />

2. Distribution of Item Fat Content 
<img width="580" height="455" alt="Distribution of Item Fat Content" src="https://github.com/user-attachments/assets/35163e25-0559-45ec-89eb-68c20be519d5" />
