# ☕ Coffee Shop Sales & Rush-Hour Operations Analytics

## 📌 Project Overview
This Power BI dashboard provides operational intelligence for coffee shop managers by analyzing hourly transaction volumes, sales revenue peaks, and shift performance. Designed to assist in labor scheduling and inventory prep, the report highlights morning vs. afternoon rush-hour patterns using custom DAX parameters and dynamic bookmark controls.

---

## 🎯 Business Objectives & Key Questions
* **Peak Hour Identification:** What are the high-volume store hours requiring additional staffing?
* **Shift Analysis:** How does total revenue compare between Morning Shifts (6 AM – 12 PM) and Afternoon Shifts (12 PM – 8 PM)?
* **Product Mix:** Which beverage and food categories drive sales during specific operational hours?
* **Daily Traffic Trends:** What days of the week experience the heaviest store traffic?

---

## 🛠️ Data Stack & Skills Applied
* **Business Intelligence:** Microsoft Power BI Desktop & Power BI Service
* **Data Modeling:** Star Schema data structure connecting Sales Fact tables with Date & Time dimensions
* **DAX Syntax:** Measures for hourly aggregations, shift-based metrics, and dynamic totals using `CALCULATE`, `FILTER`, `SUM`, and `TIME` logic
* **UI/UX Optimization:** Bookmark navigation for instant shift toggling (Morning vs. Afternoon), custom color palettes, and responsive layouts

---

## 📊 Key Dashboard Features
1. **Rush-Hour Bell Curve:** Visual representation of transaction volume by hour to pinpoint exact busy windows.
2. **Shift Switcher Bookmarks:** Interactive buttons letting managers isolate morning vs. afternoon store performance instantly.
3. **Top Selling Products Table:** Breakdown of top revenue-generating menu items by shift period.

---

## 📁 Repository Structure
```text
├── README.md                           # Project documentation and summary
├── Coffee_Shop_Sales_Analysis.pbix     # Interactive Power BI report file
└── Coffee_Shop_Dashboard_Overview.pdf  # PDF report export for visual review


🚀 How to View
Download the Coffee_Shop_Sales_Analysis.pbix file.

Open in Microsoft Power BI Desktop to test interactive shift bookmarks and detailed metrics.

For a quick visual review without Power BI Desktop, check Coffee_Shop_Dashboard_Overview.pdf.
