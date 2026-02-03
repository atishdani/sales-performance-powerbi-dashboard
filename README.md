# 📊 Sales Performance & Profitability Dashboard | Power BI

## 📌 Objective
Built an interactive Power BI dashboard to analyze:
- Sales trends over time
- Profitability by category
- Top 5 cities by revenue
- Payment mode distribution
- Profit vs quantity relationship

## 📂 Data
- Orders.csv: Order Date, City, Payment Mode, Amount
- Details.csv: Category, Sub-Category, Quantity, Profit  
**Relationship:** Orders[Order ID] → Details[Order ID]

## 📐 KPIs (DAX)
- Total Amount = SUM(Orders[Amount])
- Total Profit = SUM(Details[Profit])
- Total Quantity = SUM(Details[Quantity])

## 📊 Dashboard Visuals
1. Sales Over Time (Line chart)
2. Profit by Category (Bar chart)
3. Top 5 Cities by Sales (Column chart)
4. Payment Mode Comparison (Pie chart)
5. Profit vs Quantity (Scatter chart)

## 🔍 Key Insights
- Sales show noticeable trend patterns over time.
- Profitability varies significantly across categories.
- Revenue is concentrated in the top-performing cities.
- Payment modes reveal customer preference patterns.
- Quantity and profit are related, with some segments generating higher margins.

## ✅ Business Recommendations
- Focus marketing and inventory planning on top cities.
- Promote high-margin categories/sub-categories.
- Review low-profit high-volume segments for pricing/cost improvement.
- Encourage preferred payment modes via offers/incentives.

## 🛠 Tools Used
Power BI, DAX, Data Modeling, Data Visualization
