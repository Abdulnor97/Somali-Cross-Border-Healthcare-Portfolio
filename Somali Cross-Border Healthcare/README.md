# 🩺 Somali Cross-Border Healthcare Spending Analysis

### 📖 The Story Behind the Data
Every year, thousands of families face tough decisions when local medical options aren't enough for specialized treatments. They pack their bags and head abroad for care. But beyond the personal stress, there's a massive financial trail left behind that rarely gets mapped out.

To see the big picture, I dived into **31,285 patient records**. I wanted to follow the money and travel paths: *Where are people actually going? How much are they spending? And when during the year does this travel peak?* 

This project isn't just about raw numbers—it’s about turning complex travel data into clear, visual stories so health planners and economic teams can see exactly where the resources are flowing.

---

## 📊 Dashboard Preview

![Somali Cross-Border Healthcare Dashboard](./images/Somali%20Cross-border%20healthcare.gif)

---

## 💡 Key Insights & Economic Trends

- 💰 **The Financial Footprint:** Tracked a total of **$219M** spent across international healthcare corridors.
- 👥 **Patient Travel:** Mapped out the movement patterns of over **31,000 individual patients**.
- 📍 **Destination Breakdown:**
  - **India:** Stands out as the top destination, capturing over **$80M** of the total medical spend.
  - **Türkiye, Ethiopia, & Egypt:** Serve as the main secondary hubs handling regional patient flow.
- 💳 **Cost Per Patient:** Averages around **$11.0K per patient**, with clear seasonal spikes during specific months of the year.

---

## ⚙️ How It Was Built

### 1. Cleaning the Raw Records (ETL)
- Worked inside **Excel and Power Query** to clean up 31,000+ messy travel records.
- Standardized destination names, converted foreign currency amounts, and fixed missing values to keep the data reliable.

### 2. Modeling & Custom Metrics (DAX)
- Built custom DAX formulas to dynamically calculate key metrics like *Total Spend*, *Patient Count*, and *Average Spend*.
- Set up a clean date table to track month-over-month travel trends accurately.

### 3. Visual Layout & Theme
- Used an **Executive Dark Mode** layout with dark slate backdrops and sharp blue visual accents so key figures pop out immediately.
- Added interactive slicers so users can filter down the data by specific countries with a single click.

---

[⬅️ Back to Main Portfolio Overview](../README.md)