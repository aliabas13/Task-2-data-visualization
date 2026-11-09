# Superstore Sales & Profitability Dashboard

A Power BI dashboard built using the global Superstore dataset to track sales performance, identify profit drivers, and uncover business bottlenecks.

---

## 📊 Overview of Dashboard Visuals

### Page 1: Executive Sales & Profit Performance Dashboard

1. **KPI Cards (Top Banner)**
   * **Total Sales ($2.30M):** Displays overall lifetime revenue.
   * **Net Profit ($286.40K):** Shows the store's total net earnings after costs.
   * **Order Count (5.01K):** Tracks total unique orders processed.
   * **Average Discount (15.62%):** Highlights the overall promotional discount rate.

2. **Sales & Profit by Year (Line Chart)**
   * **Purpose:** Shows financial performance over time (2014–2017).
   * **Insight:** Displays year-over-year sales growth alongside profit margins to verify if profits grow at the same pace as revenue.

3. **Profit by Sub-Category (Horizontal Bar Chart)**
   * **Purpose:** Ranks sub-categories by total profitability.
   * **Insight:** Highlights the biggest profit makers (Copiers, Phones, Accessories) and immediately flags loss-making lines (Tables, Bookcases).

4. **Sales by Customer Segment (Donut Chart)**
   * **Purpose:** Breaks down total revenue by customer group.
   * **Insight:** Shows that Consumers generate ~50% of revenue, followed by Corporate (~30%) and Home Office (~20%).

5. **Sales & Performance by State (Geographic Map)**
   * **Purpose:** Maps order volume across the United States using bubble sizes.
   * **Insight:** Identifies California and New York as primary regional revenue drivers.

6. **Region Filter (Slicer)**
   * **Purpose:** Allows instant interactive filtering by Central, East, South, and West territories.

---

### Page 2: Product & Profitability Deep-Dive

1. **Discount vs. Profit Sensitivity (Scatter Plot)**
   * **Purpose:** Evaluates the relationship between discount percentage and profit.
   * **Insight:** Visualizes how discounts over 20% quickly push transactions into negative profit margins.

2. **Profit Performance across Sub-Categories (Clustered Column Chart)**
   * **Purpose:** Compares category margins vertically for quick visual evaluation.

3. **Fulfillment by Shipping Mode (Donut Chart)**
   * **Purpose:** Illustrates order distribution across Standard Class, Second Class, First Class, and Same Day shipping.
   * **Insight:** Confirms Standard Class is the most popular fulfillment method.

4. **Product Hierarchy & Volume Breakdown (Treemap)**
   * **Purpose:** Displays category and sub-category sales volume through proportional rectangles.
   * **Insight:** Shows Technology and Office Supplies dominating total product volume.

---

## 🛠️ Files Included

* `Superstore_Analysis.pbix` — Interactive Power BI workbook.
* `Superstore_Dashboard_Report.pdf` — PDF export of the completed dashboard.
* `high_contrast_dark_theme.json` — Custom dark-mode executive styling theme.