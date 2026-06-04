# Mobile Sales Analysis Dashboard

## 📌 Project Objective    
To design and develop an **Interactive Mobile Sales Analytics Dashboard** in **Power BI** that delivers real-time insights into total sales, quantities, transactions, customer ratings, and payment behavior across brands, models, cities, and time.

The dashboard enables stakeholders to track **KPIs**, analyze performance by **brand/model/city/month/day**, understand **customer sentiment**, and make **data-driven decisions** for inventory, marketing, and channel optimization.

---

## 📊 Live Business Insights Dashboard
I created an interactive **Power BI dashboard** to analyze and visualize business insights.  
🔗 You can explore it live here: [View Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYzY0NjlmOTgtZTI0Ny00NzA2LWI1Y2ItM2U5OGMxYWZmZTM1IiwidCI6ImNhZDFhYWU2LTc3MjEtNGE2Yy05ZWM3LWY1MWQ4YTJkYjY5NiJ9)

---

## 🚨 Business Problem  
Smartphone retail is competitive and fast-moving. Teams need a single source of truth to:  
- Monitor **Total_Sales (₹769M)**, **Total Quantity (19K)**, **Transactions (4K)**, and **Average (40K)**  
- Identify **top-performing brands and models**  
- Track **monthly and weekly seasonality** in demand  
- Understand **city-level** coverage and hotspots  
- Evaluate **payment method mix** to optimize checkout and offers  
- Gauge **customer ratings** distribution to improve product and support

---

## 📂 Dataset Used  
- [Dataset](https://github.com/KamalNayanTiwary/Mobile-Sales-Analytics-Dashboard/blob/main/Mobile%20Sales%20Data.xlsx)

---

## ❓ Key Questions (KPIs)  
- Which **brands and models** contribute most to sales and quantity?  
- How do **monthly quantities** trend across the year?  
- Which **cities** show stronger sales footprints?  
- What’s the **payment method split** across UPI / Debit / Credit / Cash?  
- How are **sales distributed by day of the week**?  
- What does the **customer rating** mix look like (1–5 stars)?  
- Are **transactions and quantities** aligned with sales by brand?

---

## ⚙️ Process  
- **Data Import & Cleaning:** Ingested raw sales, transaction, and rating data; removed duplicates; standardized types with **Power Query**.  
- **Data Transformation:** Built calculated columns and **DAX measures** for KPIs (sales, qty, transactions, averages, shares).  
- **Data Modeling:** Star schema with fact table(s) and dimension tables (Date, Brand, Model, City, Payment Method).  
- **Visualization Setup:** KPIs, **map** (Sales by City), **line charts** (Month & Day trends), **bar charts** (Ratings, Models), **pie** (Payment Method), and a **brand summary table**.  
- **Dashboard Design:** Global slicers for **Brand, Mobile Model, Payment Method, City, Month** with clear typography and consistent layout.

---

## 📊 Dashboard

![Overview](https://github.com/KamalNayanTiwary/Mobile-Sales-Analytics-Dashboard/blob/main/Snapshot%20of%20Dashboard.png)

---

## 🔎 Project Insights  
- **Top-Line KPIs:** ₹**769M** Total_Sales | **19K** Total Quantity | **4K** Transactions | **Average 40K**.  
- **Brand Performance (Table):**  
  - **Apple** leads in Sales (**~₹161.6M**), Quantity (**3,932**), and Transactions (**783**).  
  - **Samsung** is a close second (**~₹160.0M** sales; Quantity **3,923**).  
  - **OnePlus (~₹153.7M)**, **Vivo (~₹150.1M)**, **Xiaomi (~₹143.8M)** follow.  
- **Model Mix:** Flagship models dominate; each top model contributes **~₹46M–₹60M** in sales.  
- **Monthly Seasonality (Quantity):**  
  - Peaks around **July (~1,700)** and **March (~1,696)**; strong start in **January (~1,672)**.  
  - **February (~1,451)** and **September (~1,521)** are softer months.  
- **Weekly Pattern (Sales by Day Name):**  
  - **Saturday** is the strongest (~**₹115M**).  
  - Gradual decline toward mid-week with **Wednesday** lowest (~**₹105M**).  
- **Payment Methods:** Mix is **evenly distributed (~24–26% each)** across **UPI, Debit Card, Credit Card, and Cash** — no single method dominates.  
- **Customer Ratings:** Skews positive — **5★ (~1.49K)** and **4★ (~0.84K)** together are **~61%** of all ratings; **1–2★** account for **~22%**, indicating overall customer satisfaction.  
- **Geography:** Broad **pan-India coverage** across major metros and Tier-2 cities (e.g., **Delhi, Mumbai, Bengaluru, Hyderabad, Kolkata, Chennai, Lucknow, Coimbatore, Ranchi, Gorakhpur**).

---

## ✅ Final Conclusion  
- **Double down on leaders:** Prioritize **Apple & Samsung** (pricing, stock, promos); replicate successful tactics to **OnePlus/Vivo/Xiaomi**.  
- **Leverage seasonality:** Plan launches and campaigns for **March–July**; bolster **Feb/Sep** with targeted offers.  
- **Weekend momentum:** Allocate ads, staffing, and stock to **weekends (Sat > Sun)**; use mid-week promotions to stabilize **Wed/Thu**.  
- **Payment strategy:** Since methods are balanced, run **A/B offers** across UPI/Debit/Credit/Cash to find ROI-positive incentives.  
- **Quality focus:** Maintain high standards and service to keep **4–5★ dominance**; address 1–2★ feedback loops.  
- **City targeting:** Sustain metros while scaling in high-potential Tier-2 cities highlighted on the map.

---

## 👨‍💻 Author & Contact  
**Kamal Nayan Tiwary**  
**Data Analyst**

📧 **kamalnayantiwary73@gmail.com**  
🔗 [LinkedIn](https://www.linkedin.com/in/kamal-nayan-tiwary-2022-2026-/)
