# 📊 Customer Analytics Dashboard – Tableau Workbook

This repository contains a Tableau workbook (`.twbx`) that analyzes customer behavior, satisfaction, and value using data from multiple sources. The dashboard provides a comprehensive view of key customer metrics to support data-driven decision-making in marketing, sales, and customer experience.

---

## 📁 Data Sources

The analysis is based on a data model composed of the following CSV files:

- `clientes.csv`: Customer demographic and identification data.
- `ventas.csv`: Sales transactions.
- `canales.csv`: Sales or communication channels.
- `productos.csv`: Product catalog.
- `campañas_marketing.csv`: Marketing campaign data.
- `encuestas_satisfaccion.csv`: Customer satisfaction survey responses.

---

## 📐 Metrics Included

### 1. Customer Value Metrics

- **Customer Lifetime Value (CLV)**: Estimated net revenue a customer will generate over their relationship with the company.
- **Customer Acquisition Cost (CAC)**: Average cost to acquire a new customer.
- **Average Order Value (AOV)**: Average amount spent per transaction.

### 2. Behavioral Metrics

- **Purchase Frequency**: Number of purchases per customer.
- **Retention Rate**: Percentage of customers who continue buying after their first purchase.
- **Churn Rate**: Percentage of customers who stop buying or using the service.
- **Time Between Purchases**: Average interval between two consecutive purchases (in progress).

### 3. Satisfaction and Loyalty Metrics

- **Net Promoter Score (NPS)**: Measures likelihood of customers recommending the brand.
- **Customer Satisfaction Score (CSAT)**: Measures satisfaction with a product or service.
- **Customer Effort Score (CES)**: Measures how much effort a customer must exert to resolve an issue.

### 4. Segmentation Metrics

- **RFM Segmentation**: Classifies customers based on:
  - **Recency**: How recently they purchased.
  - **Frequency**: How often they purchase.
  - **Monetary**: How much they spend.

---

## 📊 Visualizations

The Tableau workbook includes:

- Metric comparison dashboards (NPS, CSAT, CES).
- Customer value analysis (CLV vs CAC).
- Behavioral trends and retention analysis.
- RFM segmentation heatmaps.
- Interactive filters by channel, product, and campaign.
 You can see in Tableau Public the dashboard:  
 https://public.tableau.com/authoring/AnlisisClientes_17527622358010/CustomerAcquisitionCostCAC#1


---

## 🚀 Getting Started

1. Download or clone this repository.
2. Open the `.twbx` file in Tableau Desktop or Tableau Public.
3. Explore the dashboards and interact with filters and parameters.

---

## 📌 Notes

- The workbook uses calculated fields and relationships between CSVs based on primary and foreign keys.

---

## 📄 License

This project is open for educational and analytical purposes.

