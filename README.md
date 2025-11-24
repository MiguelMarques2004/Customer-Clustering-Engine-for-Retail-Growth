# 🧠 Retail Customer Clustering & Segmentation

Project developed for the **Machine Learning II (NOVA IMS)** course, focused on **retail customer clustering** to support marketing decisions and targeted campaigns.

## 📌 Objective

- Create **customer segments** based on demographics, location, and purchase behavior  
- Analyze the profile of each cluster  
- Suggest **promotions and targeted campaigns** for each segment  

## 🗂️ Data

- `customer_info.csv` – demographic information, location, spending by category, promotions, etc.  
- `customer_basket.csv` – shopping baskets (list of products per transaction)  
- `product_mapping.xlsx` – mapping from product to category  

## 🧠 Methodology (summary)

- **EDA & data cleaning** (outliers, missing values, new variables such as age and years as a customer)  
- **Normalization** of relevant features  
- **Clustering** testing different clustering algorithms
- Analysis of **cluster profiles** (e.g., young customers, families, big spenders, bargain hunters, etc.)  
- **Association rules** on `customer_basket` to suggest segment-specific campaigns  

