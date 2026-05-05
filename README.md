# 🍔 Food Delivery App Analysis — Power BI

An interactive multi-page Power BI dashboard analyzing food delivery operations across cities, covering revenue performance, customer behavior, restaurant metrics, and delivery efficiency.

---
<img width="1288" height="732" alt="image" src="https://github.com/user-attachments/assets/19cb4b05-80cc-42be-a00d-6778a217f9f2" />
<br> <br>
<img width="1306" height="732" alt="image" src="https://github.com/user-attachments/assets/5e39b27d-b086-47f5-9b9d-df37590b28ef" />
<br> <br>
<img width="1297" height="712" alt="image" src="https://github.com/user-attachments/assets/2daa06f2-9e05-45f9-b825-3952ca367f43" />
<br> <br>
<img width="1303" height="722" alt="image" src="https://github.com/user-attachments/assets/46dd9307-8ef5-4011-bd40-c5792f3504ef" />



## 📊 Dashboard Overview

The report spans **4 pages**, each focused on a distinct area of the business:

| Page | Focus Area |
|------|-----------|
| **Page 1 — Overview** | Revenue, orders, top restaurants, order status |
| **Page 2 — Customer Analysis** | Customer types, retention, signup trends |
| **Page 3 — Restaurant & Cuisine Analysis** | Cuisine orders, ratings, cost segments |
| **Page 4 — Delivery Performance** | Delivery times, late orders, cancellations |

---

## 📌 Key Metrics at a Glance

| Metric | Value |
|--------|-------|
| Total Revenue | ₹165M |
| Total Orders | 200K |
| Avg Order Value | ₹824.57 |
| Avg Delivery Time | 44.55 mins |
| Total Customers | 20K |
| Repeat Customer % | 99.95% |
| Orders per Customer | 10.00 |
| Total Restaurants | 56K |
| Avg Restaurant Rating | 3.70 |
| Late Delivery % | 48.12% |
| Cancelled Orders | 20K |

---

## 📄 Page-by-Page Breakdown

### Page 1 — Overview
- **KPI Cards:** Total Revenue, Total Orders, Avg Order Value, Avg Delivery Time
- **Revenue by City** — Horizontal bar chart; top city generates ₹15.4M
- **Top 10 Restaurants** — Table with Total Revenue, Total Orders, and Avg Rating
- **Order Status Breakdown** — Donut chart: Delivered (80.1%), Cancelled (9.97%), Delayed (9.93%)
- **Order Trend** — Monthly line chart across 2023–2025
- **Revenue Trend** — Monthly line chart (range: ₹4.5M–₹5.0M)
- **Filter:** City-wise slicer

### Page 2 — Customer Analysis
- **KPI Cards:** Total Customers, Repeat Customers, Repeat Customer %, Orders per Customer
- **Orders by Customer Type** — Bar chart: New (99K), Returning (81K), Premium (20K)
- **New vs Repeated Customers** — Donut chart: New 49.7%, Returning 40.27%, Premium 10.03%
- **Top 10 Customers** — Table with CustomerID, Total Revenue, Total Orders, Avg Rating, City
- **Signup Trend** — Monthly line chart (Jan 2022 – Oct 2023), range 700–900 signups
- **Filter:** Table Booking toggle (Yes / No)

### Page 3 — Restaurant & Cuisine Analysis
- **KPI Cards:** Total Restaurants, Avg Rating, Avg Votes, Revenue per Restaurant (₹2.93K)
- **Orders by Cuisine** — Bar chart; top cuisine drives 44K orders
- **Revenue by Top 10 Restaurants** — Bar chart; top restaurant at ₹0.90M
- **Avg Rating by Cuisine** — Horizontal bar chart (range: 3.5–4.0)
- **Cost Bucket by Orders** — Donut chart: Budget (59.1%), Mid Range (12.39%), Premium (2.x%)
- **Filter:** Cost Bucket slicer (Budget / Mid Range / Premium)

### Page 4 — Delivery Performance
- **KPI Cards:** Late Orders (96K), Cancelled Orders (20K), Late Delivery % (48.12%), Avg Delivery Time (44.55 mins)
- **City-wise Delivery** — Matrix table: Avg delivery time by city and order status (Cancelled / Delayed / Delivered)
- **City-wise Delivery Time** — Horizontal bar chart; highest city at 58.80 mins
- **Cancellation by City** — Bar chart; top city has 1,876 cancellations
- **Delivery Status Breakdown** — Donut chart: On Time (51.88%) vs Late (48.12%)
- **Delivery Trend** — Line chart of Avg Delivery Time across 2023–2025
- **Filter:** Year slicer (2023 / 2024 / 2025)

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|------|-------|
| **Power BI Desktop** | Dashboard creation, data modeling |
| **DAX** | KPI measures, calculated columns |
| **Power Query** | Data transformation and cleaning |

---

## 🚀 Getting Started

### Prerequisites
- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free download)

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/mittal-2004/Food-Delivery-Analysis--Power-BI.git
   ```
2. Open `Food_delivery_app_analytics.pbix` in Power BI Desktop.
3. Refresh the data source if prompted.
4. Use the slicers (City, Year, Cost Bucket, Table Booking) to explore the dashboard interactively.

---

## 💡 Key Insights

- **80.1%** of all orders are successfully delivered; ~10% each are cancelled or delayed.
- **Repeat customer rate is 99.95%** — virtually all customers reorder, indicating strong retention.
- **48.12% of deliveries are late**, pointing to a significant operational improvement opportunity.
- The **Budget cost segment dominates** at 59.1% of orders, suggesting a price-sensitive customer base.
- **Top city generates ₹15.4M** in revenue — nearly double the second-ranked city.

---

## 📁 Repository Structure

```
Food-Delivery-Analysis--Power-BI/
│
├── Food_delivery_app_analytics.pbix   # Power BI report file
├── Food_delivery_app_analytics.pdf    # Dashboard preview (PDF export)
└── README.md
```

---

## 📬 Contact

**Manav Mittal**  
GitHub: [@mittal-2004](https://github.com/mittal-2004)
