# 🛍️ Customer Behaviour Analysis on Shopping

A data analysis project that explores customer shopping patterns, purchase behaviour, and demographic trends to derive actionable insights for retail and e-commerce businesses.

---

## 📌 Overview

Understanding how customers behave is essential for any retail or e-commerce business. This project analyses a shopping dataset to uncover patterns in customer demographics, product preferences, spending habits, and purchase frequencies — helping businesses make data-driven decisions to improve marketing strategies and boost sales.

---

## 🎯 Objectives

- Analyse customer demographics (age, gender, location)
- Identify top-selling product categories and items
- Understand purchase frequency and spending patterns
- Segment customers based on behaviour
- Derive insights to support marketing and retention strategies

---

## 📂 Project Structure

```
Customer-Behaviour-Analysis-on-Shopping/
│
├── Business Problem Document.pdf                  # Problem statement and business context
├── Customer Shopping Behavior Analysis Pdf.pdf    # Full analysis report in PDF format
├── Customer_Behavior_Dashboard.pbix               # Power BI interactive dashboard
├── Customer_Shopping_Behavior.sql                 # SQL queries for data exploration
├── Customer_Shopping_Behavior_Analysis_update...  # Updated analysis notebook/script
├── Customer_Shopping_Behaviour_Analysis.ipynb     # Main Jupyter Notebook for analysis
├── customer_shopping_behavior.csv                 # Raw dataset
├── dashboard.png                                  # Dashboard screenshot/preview
├── LICENSE                                        # MIT License
└── README.md                                      # Project documentation (this file)
```

---

## 📊 Dataset

The dataset contains transactional and demographic records of customers, including fields such as:

| Column | Description |
|---|---|
| Customer ID | Unique identifier for each customer |
| Age | Age of the customer |
| Gender | Gender of the customer |
| Category | Product category purchased |
| Item Purchased | Specific item bought |
| Purchase Amount | Amount spent (USD) |
| Payment Method | Mode of payment used |
| Frequency of Purchases | How often the customer shops |
| Review Rating | Customer review score |
| Subscription Status | Whether the customer is subscribed |
| Discount Applied | Whether a discount was used |
| Promo Code Used | Whether a promo code was applied |

---

## 🔍 Key Analyses

### 1. Demographic Analysis
- Age distribution across customer segments
- Gender breakdown of the customer base
- Geographic spread of customers

### 2. Purchase Pattern Analysis
- Most popular product categories
- Top-selling items by age group and gender
- Seasonal trends in purchases

### 3. Spending Behaviour
- Average purchase amount by category and demographic
- Impact of discounts and promo codes on spending
- High-value vs. low-value customer identification

### 4. Customer Segmentation
- Segmentation based on purchase frequency and amount
- Subscription vs. non-subscription customer behaviour
- Payment method preferences

---

## 📈 Sample Insights

- 🧑‍🤝‍🧑 The **36–50 age group** accounts for the highest purchase frequency
- 👗 **Clothing** and **Accessories** are the most popular categories
- 💳 Customers who use **promo codes** tend to have higher average order values
- 🔄 Subscribed customers show significantly higher **repeat purchase rates**

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualisation |
| Seaborn | Statistical plotting |
| Jupyter Notebook | Interactive analysis environment |
| SQL | Data querying and exploration |
| Power BI | Interactive dashboard and reporting |

---

## 🚀 Getting Started

### Prerequisites

- Python 3.7+
- Power BI Desktop (for `.pbix` dashboard)
- Any SQL client (e.g. MySQL Workbench, DBeaver) for `.sql` queries

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ZeagelOg/Customer-Behaviour-Analysis-on-Shopping.git
   cd Customer-Behaviour-Analysis-on-Shopping
   ```

2. **Install Python dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. **Run the Jupyter Notebook**
   ```bash
   jupyter notebook Customer_Shopping_Behaviour_Analysis.ipynb
   ```

4. **Explore the SQL queries** by opening `Customer_Shopping_Behavior.sql` in your preferred SQL client with `customer_shopping_behavior.csv` loaded as a table.

5. **View the dashboard** by opening `Customer_Behavior_Dashboard.pbix` in Power BI Desktop.

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 👤 Author

**ZeagelOg**  
GitHub: [@ZeagelOg](https://github.com/ZeagelOg)

---

> ⭐ If you found this project helpful, please consider giving it a star!
