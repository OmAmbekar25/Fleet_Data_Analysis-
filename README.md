# ✈️ Fleet Data Analysis

This project delivers a detailed analysis of global commercial aircraft fleet data. The dashboard and analysis highlight patterns in fleet composition, aircraft cost, age, airline investments, and procurement trends. The goal is to empower data-driven decision-making for airline strategists, analysts, and procurement planners.

---

## 📌 Project Objective

To analyze the aircraft fleet across multiple airlines based on aircraft type, operational status (Current, Future, Historic), cost, age, and orders. The analysis uncovers trends in fleet modernization, investment strategy, and market dominance of major aircraft manufacturers.

---

## 📊 Key Features of the Analysis

-  Fleet count and cost segmented by **Current**, **Historic**, and **Future** aircraft.
-  Insights into **most popular aircraft types** (e.g., A320, B737).
-  Airline-wise fleet size, average age, and total investment.
-  Aircraft **age vs. unit cost** relationships showing depreciation trends.
-  Correlation between fleet size, orders, and total cost.

---

## 🧹 Data Preparation

- ✅ Checked and handled missing values.
- ✅ Verified and corrected data types.
- ✅ Removed outliers (especially in `Average_Age`) using IQR for clean analysis.
- ✅ Derived new columns like `Total_Cost` = `UnitCost × Total Aircraft`.

---

## 📈 Exploratory Data Analysis (EDA)

- ✈️ **Fleet Status Breakdown**: Most aircraft are currently operational.
- 🏢 **Top Parent Airlines**: Lufthansa, IAG, and American Airlines top the fleet charts.
- 🛩 **Top Aircraft Types**: Airbus A320 and Boeing 737 dominate global fleets.
- 💰 **Cost Analysis**: American Airlines leads in investment, exceeding $120B.
- 📉 **Age vs Cost Trends**: Newer aircraft cost more; older models are heavily depreciated.
- 📊 **Correlation Insights**:
  - Fleet Size ↔ Total Cost: Strong positive correlation (0.69)
  - Orders ↔ Total Cost: Moderate positive correlation (0.53)

---

## 📉 Visualizations

- 📊 Bar Charts: Aircraft type & airline distribution
- 📦 Boxplots: Unit cost and aircraft age spread
- 📐 Scatter Plots: Cost vs Age analysis
- 📚 Stacked Bar Charts: Fleet type per airline

---

## 🧠 Insights & Conclusion

- Airbus and Boeing dominate global aviation.
- Airlines like Lufthansa, American, and United are investing heavily in fleet expansion.
- Modern aircraft cost more but bring efficiency; older aircraft are more affordable but aging.
- Fleet size and total cost are closely tied, helping identify top spenders in global aviation.
- The data highlights fleet modernization efforts and guides procurement planning.

---

## 🛠 Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook

---


> 🚀 Feel free to fork, star ⭐, or contribute to this project if you found it helpful!
