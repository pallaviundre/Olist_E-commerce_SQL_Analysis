# Olist E-commerce SQL Analysis

## Project Overview
This project presents an end-to-end SQL analysis of the Brazilian Olist e-commerce dataset.
The objective is to extract meaningful business insights related to sales performance,
customer behavior, delivery efficiency, and customer satisfaction using MySQL.

The analysis simulates a real-world business scenario where SQL is used to support
data-driven decision-making for an e-commerce platform.

---

## Dataset
- **Source:** Olist Brazilian E-commerce Dataset (Kaggle)
- **Description:** Public dataset containing information on orders, customers, sellers,
  products, payments, reviews, and delivery details
- **Scale:** ~100,000 orders across multiple related tables

### Tables Used
- `customers`
- `orders`
- `order_items`
- `order_payments`
- `order_reviews`
- `products`
- `sellers`
- `product_category`

---

## Tools & Technologies
- MySQL
- MySQL Workbench
- GitHub

---

## Analysis Sections

### 1️⃣ Sales Analysis
*(SQL file: `01_sales_analysis.sql`)*

Key business questions answered:
- Monthly trend of orders and revenue
- Top product categories by revenue
- Top-selling products by total sales
- Peak order day and hour

**Key Insight:**  
Sales exhibit clear time-based trends, with a small number of product categories
contributing a significant portion of total revenue.

---

### 2️⃣ Customer Analysis
*(SQL file: `02_customer_analysis.sql`)*

Key business questions answered:
- One-time vs repeat customers
- Top customers by total spend
- RFM-based customer segmentation (Champions, Loyal, At Risk, Lost)

**Key Insight:**  
The majority of customers are one-time buyers, while repeat customers contribute
disproportionately higher revenue, highlighting the importance of retention strategies.

---

### 3️⃣ Delivery & Operations Analysis
*(SQL file: `03_delivery_analysis.sql`)*

Key business questions answered:
- Average delivery time
- Late vs on-time deliveries
- States with the highest delivery delays

**Key Insight:**  
Delivery performance varies significantly by region, indicating opportunities for
logistics and supply chain optimization.

---

### 4️⃣ Reviews & Customer Satisfaction
*(SQL file: `04_review_analysis.sql`)*

Key business questions answered:
- Review score distribution
- Relationship between delivery time and review scores
- States with the lowest average customer ratings

**Key Insight:**  
Longer delivery times are strongly associated with lower customer review scores,
demonstrating a direct link between operational efficiency and customer satisfaction.

---

## Conclusion
This project demonstrates the use of SQL to solve real-world business problems by:
- Joining multiple relational tables
- Applying aggregations and date-based analysis
- Performing customer segmentation
- Translating raw data into actionable insights

The analysis highlights how SQL can be effectively used to support business decisions
in an e-commerce environment.
