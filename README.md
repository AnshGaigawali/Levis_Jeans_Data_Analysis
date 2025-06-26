# 👖 Levi’s Men’s Jeans Pricing ,Style & Discount Analysis

An end-to-end data analysis and business intelligence project that explores the pricing structure, discounts, and style trends of Levi’s men's jeans on the **Levi’s India online store**. The project combines **web scraping, data cleaning, visualization**, and a professional **Power BI dashboard** to derive actionable insights from real-world e-commerce data.

---

## 📌 Table of Contents
- [🔍 Project Motivation](#-project-motivation)
- [🧠 Technologies Used](#-technologies-used)
- [⚙️ How It Works](#-how-it-works)
- [📊 Power BI Dashboard](#-power-bi-dashboard)
- [📈 Key Insights](#-key-insights)
- [🔮 Future Improvements](#-future-improvements)
- [📸 Screenshots](#-screenshots)
- [🙋‍♂️ About Me](#-about-me)

---

## 🔍 Project Motivation
While browsing the **Levi’s India website** to buy jeans, I noticed varying discount patterns and price differences across styles. I decided to analyze this data at scale using real-time scraping and visualization tools to uncover insights that could help users make smarter buying decisions — and brands optimize pricing.

---

## 🧠 Technologies Used
- **Python** – Data scraping & preprocessing
  - Libraries: `Selenium`, `Pandas`, `Matplotlib`, `Seaborn`, `Regex`
- **Power BI** – Interactive report/dashboard
- **Jupyter Notebook** – EDA & code walkthrough

---

## ⚙️ How It Works

### ✅ Step 1: Web Scraping
- Scraped Levi's India Men's Jeans collection using Selenium.
- Handled dynamic content with infinite scrolling.
- Extracted: Product Title, Sale Price, Regular Price, Image URL, Product Link.

### ✅ Step 2: Data Cleaning & Processing
- Removed duplicates & missing prices.
- Calculated `Discount (%)` using:
  ((Regular Price - Sale Price) / Regular Price) * 100

### ✅ Step 3: Power BI Dashboard
- Imported the cleaned CSV.
- Created calculated columns:
  - Discount (%)
  - Discount Range
  - Jeans Style
- Created visuals: KPI cards, pie charts, histograms, bar charts, scatter plot, and an image-rich product table.

## 📊 Power BI Dashboard Highlights
- KPI Cards for:
  - Total Products
  - Average Sale Price
  - Average Discount (%)
- Histograms for Sale and Regular Prices
- Pie Chart for Discount Range segmentation
- Bar Chart for Top 10 Discounted Products
- Scatter Plot for Sale vs. Regular Price
- Table with Product Image, Title, Discount, and clickable Link
- Slicers for filtering by Discount Range and Jeans Style

## 📈 Key Insights
- Most products had discounts in the 30–50% range.
- Styles like 511, 501, and 513 are frequently listed and often discounted.
- Higher-end products retained sale prices despite high original pricing.
- The scatter plot clearly shows pricing clusters and outliers.

## 🔮 Future Improvements
- Add scheduled scraping to track historical price trends.
- Include a scrape timestamp field to enable time series visualizations.
- Expand the dataset to include women’s jeans or other categories.
- Deploy dashboard using Power BI Online and embed it on a portfolio site.

## 🙋‍♂️ About Me
- Ansh Gaigawali
- 🎓 B.Tech - Information Technology (2022–2026)
- 📍 Pimpri Chinchwad College of Engineering

- 📧 anshgaigawali@gmail.com
- 🔗 [LinkedIn](https://www.linkedin.com/in/ansh-gaigawali-b96482259/)
- 🐙 [GitHub](https://github.com/AnshGaigawali)
