# 🛒 Customer Segmentation and Marketing Strategy

A data-driven project to segment customers for effective marketing strategies using K-Means clustering.  
**Goal**: Identify customer groups based on demographics, purchase behavior, and preferences to optimize marketing campaigns.  

---

## 📂 Repository Structure

- `2A.tsv/` – Raw customer dataset (`customer_data.csv`)  
- `customer_clustering.ipynb/` – Jupyter notebook containing data preprocessing, analysis, and clustering (`customer_segmentation.ipynb`)  
- `README.md` – Project documentation  

---

## 🔍 Dataset

**Customer dataset** (3,900 entries, 19 columns) including:

| Column                    | Description |
|----------------------------|------------|
| Customer ID               | Unique customer identifier |
| Birth Date                | Customer date of birth |
| Gender                    | Customer gender |
| Item Purchased            | Purchased item name |
| Category                  | Product category |
| Purchase Amount (USD)     | Amount spent per purchase |
| Location                  | Customer location |
| Size                      | Item size purchased |
| Color                     | Item color purchased |
| Season                    | Season of purchase |
| Review Rating             | Product review score |
| Subscription Status       | Subscription membership |
| Payment Method            | Payment type used |
| Shipping Type             | Shipping method |
| Discount Applied          | Discount used or not |
| Promo Code Used           | Promo code usage |
| Previous Purchases        | Number of past purchases |
| Preferred Payment Method  | Customer’s preferred payment |
| Frequency of Purchases    | Purchase frequency category |

---

## 🛠️ Methodology

1. **Data Preprocessing**  
   - Standardize numeric features (e.g., `Purchase Amount`)  
   - Convert data types as needed  
   - Group locations into broader regions  

2. **Data Cleaning & Outlier Detection**  
   - Check and handle outliers in numeric features  
   - Handle missing or inconsistent entries (if any)  

3. **Encoding Categorical Variables**  
   - Label encoding and/or one-hot encoding for relevant features  
   - Ensure compatibility with clustering algorithms  

4. **Customer Segmentation via K-Means**  
   - Determine optimal number of clusters using the Elbow Method  
   - Apply PCA for dimensionality reduction and visualization  
   - Fit K-Means and assign cluster labels to customers  

5. **Cluster Analysis**  
   - Examine cluster characteristics (demographics, spending behavior, preferences)  
   - Identify actionable marketing insights per cluster  

---

## 📊 Key Insights

- Distinct customer segments emerge based on purchase behavior, location, and demographics  
- High-value customers can be targeted with personalized campaigns  
- Frequent purchasers and loyal subscribers form a separate cluster for retention strategies  
- Seasonal preferences and payment methods help optimize promotions  
