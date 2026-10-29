# 👥 Customer Dashboard 2023 | Tableau

An interactive **Tableau dashboard** for **comparative customer analysis: Current Year (CY) vs Previous Year (PY)**. The user can **pick any year as the Current Year**, and the dashboard compares it with the year before. It shows how many customers the business has, how much each customer spends, how often they order, and which customers bring in the most profit.

**Live Dashboard:** [View on Tableau Public](https://public.tableau.com/views/ComparativePerformance-CustomerDashboard/CustomerDashboard?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 📌 Project Objective

- Compare customer performance between the Current Year and the Previous Year
- Let users choose any year as the Current Year for a flexible comparison
- Track monthly trends in customers, sales per customer and orders
- See how many orders customers usually place (repeat vs. one-time buyers)
- Identify the most profitable customers

---

## 📊 Dashboard Components

| Component | What it shows |
|---|---|
| **Year Selection** | User picks any year as the Current Year (CY); it is compared with the Previous Year (PY) |
| **Total Customers** | Number of unique customers in the selected year, with a monthly CY vs PY trend line |
| **Total Sales Per Customer** | Average sales value per customer, with a monthly CY vs PY trend line |
| **Total Orders** | Total orders placed in the selected year, with a monthly CY vs PY trend line |
| **Customer Distribution by No. of Orders** | Bar chart showing how many customers placed 0, 1, 2 ... 8 orders |
| **Top Customers by Profit** | Top 10 customers ranked by Current Year (CY) profit, with their CY sales and CY orders |
| **Navigation Button** | Button linking to the companion **Sales Dashboard** |

---

## 🔢 Key Metrics (Current Year selected: 2023)

| Metric | Value |
|---|---|
| Total Customers | **693** |
| Total Sales Per Customer | **1,058** |
| Total Orders | **1,687** |
| Average Orders Per Customer | **~2.4** (1,687 ÷ 693) |

---

## 💡 Key Insights

### 1. Most customers are low-frequency buyers
| Orders placed | Customers |
|---|---|
| 1 | 200 |
| 2 | 200 |
| 3 | 156 |
| 4 | 85 |
| 5 | 39 |
| 6 | 9 |
| 7 | 2 |
| 8 | 2 |

- **400 customers (~58%)** placed only 1 or 2 orders.
- **293 customers (~42%)** placed 3 or more orders.
- Only **52 customers (~7.5%)** placed 5 or more orders, so a very small group are true loyal, high-frequency buyers.
- Big opportunity: convert the 1–2 order customers into repeat buyers through loyalty offers, follow-ups and personalised promotions.

### 2. Seasonal pattern across the year (CY 2023)
- **Customers and orders were lowest around February** and grew through the year.
- Both rise noticeably from **September** and reach their **peak around November**.
- Sales per customer moves differently: it is highlighted high in **January** and low in **April**, showing that more customers does not always mean higher spend per customer.

### 3. Top customers drive strong profit
- Profit, sales and orders in this table are for the selected Current Year (CY).
- **Raymond Buch** is the most profitable customer: **₹6,781 profit** on ~₹14K sales from 3 orders.
- **Hunter Lopez (₹5,046)** and **Tom Ashbrook (₹4,599)** complete the top 3.
- The **top 10 customers together generated about ₹30,100 in profit**.
- The top 3 alone contribute about **₹16,400**, more than half of the top-10 profit.

### 4. Profit depends on more than order count
- **Steven Roelle** made ₹1,676 profit from just **1 order** (~₹4K sales).
- **Helen Wasserman** and **Brian Moss** placed **5 orders each** but earned about ₹1,947 and ₹1,938 profit respectively, far less than the top 3.
- Top profit earners such as Raymond Buch and Hunter Lopez have only 2–3 orders, so **order value and margin matter more than order frequency** for profit.

---

## 🛠️ Tools & Skills Used

- **Tableau** (Desktop / Public): dashboard design, calculated fields, table calculations (`INDEX()` for ranking)
- Current Year vs Previous Year comparison with a user-selectable year
- KPI cards with trend (sparkline) charts
- Bar chart for distribution analysis
- Ranked table for Top N analysis
- Dashboard navigation button between dashboards

---

## 🚀 How to Use

1. Download or clone this repository.
2. Open the `.twbx` file in **Tableau Desktop** or **Tableau Public**.
3. Select the year you want as the **Current Year** to compare it with the previous year.
4. Hover over the charts to see details and use the **Sales Dashboard** button to switch to the sales view.

---

## 👤 Author

**Deepak**
English Language Trainer turned Data Analyst

📫 Connect me through: 
    1.  Phone: +91-7607146249
    2.  Email: coachdeepaksingh@gmail.com

---

⭐ If you found this project useful, please give it a star!
