## Global E-Shop Business Analysis (Superstore)

### Project Overview

This project analyzes the historical sales data of a fictitious global retail company ("Superstore"). The primary goal is to translate raw transaction-level data into actionable business strategy by uncovering insights related to product profitability, customer behavior, geographic performance, and supply chain efficiency.

### Core Objectives

1. **Data Cleaning & Preprocessing:** Ensure analytical accuracy by handling missing values, duplicates, and data type conversions.
2. **Feature Engineering:** Create new business KPIs including Average Order Value (AOV), Profit Margin (%), and Delivery Time.
3. **Exploratory Data Analysis (EDA):** Discover the most profitable product segments, highlight granular financial leaks, segment VIP customers, and evaluate supply chain stability.

### Tools & Technologies

- **Language:** Python
- **Libraries:** Pandas, Matplotlib
- **Environment:** Jupyter Notebook / Google Colab

### Key Business Insights & Recommendations

- **Profitability & Leakage:** Technology is the primary profit driver (15.6% margin), while Furniture is losing money. **Recommendation:** Discontinue the top 10 loss-making SKUs (primarily specific Tables, -$17.7K) rather than dropping the entire category.
- **VIP Segmentation:** Top customers split into High-Ticket B2B (AOV > $3,800) and High-Frequency buyers. **Recommendation:** Assign dedicated sales reps to B2B clients and implement loyalty programs for frequent buyers.
- **Customer Retention:** The brand boasts a phenomenal **98.5% retention rate**. **Recommendation:** Set up automated re-engangement email campaigns targeting the remaining 1.5% of one-time buyers.
- **Geographic Strategy:** The West and East regions completely dominate revenue. **Recommendation:** Localize inventory for top-selling items in these coastal hubs to reduce shipping costs, and investigate low market penetration in the South.
- **Supply Chain:** Average delivery times are highly consistent (~4 days) across all regions. **Recommendation:** Introduce an automated "Expedited Shipping" tier for high-value orders (>$1,000) to enhance the VIP experience.

### Repository Structure

- [project_superstore.ipynb](https://www.notion.so/project_superstore.ipynb):: The main Jupyter Notebook containing the full analysis, code, and visualizations.
- [Superstore.csv](https://www.notion.so/Superstore.csv): The raw dataset used for the project.
