# 🛒 Supermart Grocery Sales Interactive Management Dashboard

An end-to-end executive retail sales performance dashboard designed in Microsoft Excel for leadership and store management[cite: 8]. This project translates 9,994 grocery transactions across Tamil Nadu into executive KPI summary cards, dynamic Pivot Tables, intuitive visualizations, multi-field slicers, and strategic data-driven recommendations[cite: 8].

---

## 📌 Project Overview & Business Scenario
- **Project Context:** The management team required a unified, intuitive dashboard to evaluate sales trends, profit health, product category contribution, discount mechanics, and municipal geographic reach without combing through raw line-item records[cite: 8].
- **Core Objectives:**
  1. Understand overall sales performance and historical growth trajectory[cite: 8].
  2. Evaluate product category and sub-category sales and margin efficiency[cite: 8].
  3. Analyze the relationship between promotional discounts and net profit[cite: 8].
  4. Assess geographic performance across cities and regions in Tamil Nadu[cite: 8].
- **Tools & Techniques Used:** Microsoft Excel (Advanced Pivot Tables, Pivot Charts, Timeline/Slicers, Report Connections, Calculated Fields, Currency & Percentage Formatting).
- **Dataset:** 9,994 transactional records spanning 2015 to 2018 across 24 cities in Tamil Nadu.

---

## 🚀 Key Performance Indicators (Executive Summary)
- **Gross Sales Revenue:** ₹1.50 Crore (₹14,956,982)[cite: 3, 4]
- **Net Total Profit:** ₹37.47 Lakhs (₹3,747,121.20)[cite: 3, 4]
- **Overall Profit Margin:** **25.05%**[cite: 1]
- **Total Orders Logged:** 9,994 transactions[cite: 1]
- **Average Order Value (AOV):** ₹1,496.60
- **Geographic Footprint:** 24 Municipal Cities (Tamil Nadu) across 5 Regional Zones[cite: 3, 4]

---

## 🔍 Analytical Objectives & Findings

### 1. Overall Sales Performance (Objective 1)
- **Consistent Annual Acceleration:** Top-line sales grew year-over-year from ₹29.76L (2015) to ₹31.32L (2016), ₹38.72L (2017), and peaked at **₹49.78L in 2018** (+28.55% annual growth).
- **Festive Q4 Seasonality:** Order volumes concentrate heavily in late Q3 and Q4, peaking in **November (₹21.94L)**, **December (₹20.88L)**, and **September (₹20.64L)**.
- **Balanced Category Mix:** Sales are distributed evenly across all 7 categories (13.6% to 15.2% share each), led by **Eggs, Meat & Fish (₹22.67L)** and **Snacks (₹22.38L)**[cite: 1].
- **Regional Strength:** The **West (₹47.99L)** and **East (₹42.48L)** regions generate **60.5%** of all top-line sales.

### 2. Product Category & Sub-Category Performance (Objective 2)
- **High-Volume Drivers:** At the item level, **Health Drinks (₹10.51L)** and **Soft Drinks (₹10.34L)** are the primary revenue drivers, each surpassing ₹10 Lakhs in sales[cite: 1].
- **High Sales with Compressed Margins:**
  - **Spices (Oil & Masala):** Generates ₹6.73L in sales (ranked 10th overall) but delivers the **lowest profit margin across all 23 sub-categories (23.82%)**[cite: 1].
  - **Masalas (Oil & Masala):** Generates ₹6.97L in sales with a below-average margin of **24.23%**[cite: 1].
  - **Atta & Flour (Food Grains):** Delivers ₹5.35L in sales at an underperforming **23.91%** margin[cite: 1].
  - **Cakes (24.56%)** and **Biscuits (24.76%)** lag behind Bakery category peer **Breads & Buns (25.69%)**[cite: 1].
- **High-Margin Value Drivers:** **Noodles (26.34%)**, **Fish (26.27%)**, and **Organic Staples (25.79%)** maintain superior margin conversion[cite: 1].

### 3. Profit & Discount Mechanics (Objective 3)
- **Zero Profit Erosion:** The Pearson correlation between `Discount` and `Profit` is **$r \approx 0.00$**, demonstrating no linear relationship between discount rates and transaction profitability[cite: 5].
- **Margin Stability Across Tiers:**
  - **10%–14% Discount:** Average Profit = ₹373.68 (25.07% Margin)[cite: 5]
  - **15%–20% Discount:** Average Profit = ₹374.18 (24.85% Margin)[cite: 5]
  - **21%–30% Discount:** Average Profit = ₹376.72 (25.23% Margin)[cite: 5]
  - **31%–35% Discount:** Average Profit = ₹373.39 (24.92% Margin)[cite: 5]
- **Key Takeaway:** Higher promotional discounts do not cannibalize net margins; profit conversion remains locked around **~25%** across all promotional tiers, with average profit holding steady at ₹360–₹390 per order[cite: 5].
- **Regional Profit Share:** **West (₹11.92L)** and **East (₹10.74L)** drive 60.5% of total company profit[cite: 3, 4].

### 4. Geographic Performance (Objective 4)
- **Market Dominance:** 100% of sales and orders originate within **Tamil Nadu**[cite: 3, 4].
- **Top 5 Revenue Cities:**
  1. **Kanyakumari:** ₹7,06,764 (459 Orders)[cite: 6]
  2. **Vellore:** ₹6,76,550 (435 Orders)[cite: 6]
  3. **Bodi:** ₹6,67,177 (442 Orders)[cite: 6]
  4. **Tirunelveli:** ₹6,59,812 (446 Orders)[cite: 6]
  5. **Perambalur:** ₹6,59,738 (434 Orders)[cite: 6]
- **Low-Margin Hotspots:**
  - **Tenkasi:** Lowest margin statewide at **24.27%** on ₹6.44L sales[cite: 6].
  - **Kanyakumari:** #1 in sales volume but converts at only **24.37%**[cite: 6].
  - **Salem:** #6 in sales volume but operates at **24.49%**[cite: 6].
  - *High-Efficiency Benchmarks:* **Karur (26.36%)** and **Bodi (26.03%)** maintain significantly higher profit conversion on comparable volumes[cite: 6].

---

## 💡 Strategic Business Recommendations

| Focus Area | Strategic Action | Business Impact |
| :--- | :--- | :--- |
| **High-Volume Staple Procurement** | Renegotiate vendor procurement contracts and adjust packaging sizes for **Spices**, **Masalas**, and **Atta & Flour**[cite: 1]. | Targets a 1.5%–2.0% margin recovery, unlocking ₹20,000–₹35,000 in immediate gross margin[cite: 1]. |
| **Discount Optimization** | Cap routine promotions at **15%–20%**. Reserve 30%+ markdowns exclusively for perishable clearance (Fruits & Veggies)[cite: 1, 5]. | Eliminates unnecessary promotional markdown while preserving baseline transaction volume[cite: 5]. |
| **Cross-Category Product Bundling** | Bundle low-margin essentials (Atta, Spices) with high-margin items (**Noodles 26.3%**, **Breads & Buns 25.7%**)[cite: 1]. | Enhances basket profitability and increases Average Order Value (AOV)[cite: 1]. |
| **Q4 Festive Inventory Alignment** | Reallocate working capital and logistics capacity heavily toward **August through December** to support surges in September, November, and December. | Prevents high-demand stockouts and captures up to 15% in incremental seasonal revenue. |
| **Municipal Margin Optimization** | Audit delivery routing, localized vendor pricing, and logistics costs in **Kanyakumari**, **Salem**, and **Tenkasi**[cite: 6]. | Aligns underperforming hubs with top-margin centers like Karur (26.36%)[cite: 6]. |

---
Dashboard

<img width="417" height="552" alt="image" src="https://github.com/user-attachments/assets/441d9595-15ed-4dc0-a43b-c906f528515b" />

