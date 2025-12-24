# ☕ Daily Brew Coffee Ltd. – Power BI Sales Analysis & Growth Strategy

> **From Data Chaos to Data-Driven Growth**

A comprehensive **Power BI case study** combined with a **strategic business growth roadmap** for Daily Brew Coffee Ltd., a fast-growing specialty coffee chain in New York City.

---

## 📋 Project Overview

Daily Brew operates **15+ retail locations** across NYC, collecting massive volumes of transaction data but struggling to extract actionable insights. This project transforms raw sales, product, customer, and employee data into:

1. **Interactive Power BI dashboards** (4 pages) for real-time operational insights
2. **Strategic business analysis** with growth opportunities and financial projections
3. **Actionable recommendations** to improve profitability and customer loyalty

### Key Questions Answered

- 📈 How are we performing month by month?
- 🏪 Which stores are bringing in the most revenue?
- ☕ Which products are our top sellers and most profitable?
- 🎯 Are promotional items actually boosting sales?
- 👥 Who are our most valuable and loyal customers?
- 🕐 What time of day are we making the most sales?
- 👨‍🍳 How are our staff performing in terms of sales?
- 🛒 What is the average customer basket size?
- 📊 What are the growth opportunities to 5x profit by 2026?

---

## 📁 Repository Structure

```
daily-brew-coffee-analysis/
├── Dataset/
│   └── Md_Sahid_Coffee_Shop_Sales_Analysis.pbix    # Power BI desktop file (5.2 MB)
│
├── Dashboards/
│   ├── main_page.png                               # Executive Summary
│   ├── store_and_staff_performance.png             # Store & Staff KPIs
│   ├── product_and_customer_analysis.png           # Product & Customer Insights
│   └── summary.png                                 # Key Metrics Overview
│
├── Reports/
│   ├── coffee_shop_sales_analysis_report.pdf       # Detailed analysis report
│   ├── Daily_Brew_Complete_Growth_Report.tex       # LaTeX growth strategy
│   └── Daily_Brew_Complete_Growth_Report.pdf       # Compiled PDF version
│
├── README.md                                       # This file
├── LICENSE
└── .gitignore

```

---

## 🎯 Key Business Findings

### Current Performance Metrics

| Metric | Value | Insight |
|--------|-------|---------|
| **Total Revenue** | $1.92M | Strong annual performance |
| **Gross Profit Margin** | 74% | Exceptional profitability (industry avg: 40-50%) |
| **Customer Base** | 2,000 | 100% loyalty program penetration |
| **Avg Revenue/Customer** | $851.80 | High lifetime value |
| **Annual Transactions** | 4,200+ | Robust activity level |
| **Gross Profit/Staff** | $126.54K | Excellent operational efficiency |

### Critical Insights from Dashboards

#### 1. Profit Concentration Risk ⚠️
- **Beverages represent 92% of profit** ($2.03M)
- Food (6%) and Merchandise (2%) severely underutilized
- Single-category vulnerability to market disruptions

#### 2. Promotional Inefficiency ⚠️
- **Promotions contribute only 0.74% of profit** ($29.40K)
- Current promotional strategy is fundamentally misaligned
- Marketing budget being wasted on low-margin items

#### 3. Staff Performance Variation
- **Top performer (Britanni Jorden) generates 2.35x average staff revenue**
- Average revenue per staff: $76.66K
- Significant untapped potential through standardization

#### 4. Temporal Demand Patterns
- **Morning Peak: 7:00 AM** (commuter rush)
- **Lunch Peak: 1:00 PM** (mid-day surge)
- Clear opportunity for dynamic scheduling optimization

#### 5. Exceptional Customer Loyalty ✅
- **100% loyalty program penetration** among 2,000 customers
- Enables sophisticated customer tracking and personalization
- Strong foundation for targeted growth initiatives

---

## 📊 Dashboard Overview

### Page 1: Executive Summary Dashboard

![Executive Summary](Dashboards/main_page.png)

**Key visualizations:**
- KPI cards (Revenue, COGS, Profit, Transactions)
- Revenue distribution by store/city
- Revenue breakdown by product category
- Monthly revenue trending
- Top-selling products

**Use case:** Executive briefing, monthly business reviews, high-level performance tracking

---

### Page 2: Store & Staff Performance Dashboard

![Store & Staff Performance](Dashboards/store_and_staff_performance.png)

**Key visualizations:**
- Gross profit per staff member
- Average revenue and transactions per employee
- Revenue by transaction time (identifies peak hours)
- Individual employee revenue leaderboard
- Neighborhood-level profitability table
- Store location analysis

**Use case:** Operations management, staff evaluation, shift optimization

---

### Page 3: Product & Customer Analysis Dashboard

![Product & Customer Analysis](Dashboards/product_and_customer_analysis.png)

**Key visualizations:**
- Total customers and loyalty metrics
- Average revenue per customer
- Revenue by transaction date and customer type
- Product category and product group performance
- Promotional item profit contribution
- Customer segmentation and value distribution

**Use case:** Product strategy, customer retention, promotional effectiveness

---

### Page 4: Summary Dashboard

![Summary Dashboard](Dashboards/summary.png)

**Key visualizations:**
- Consolidated KPIs and metrics overview
- Quick-reference performance indicators
- Visual summary of all key findings

**Use case:** Dashboard drill-down, quick status checks

---

## 💡 Strategic Growth Recommendations

### 4 Growth Strategies for 5x Profit Growth (24-Month Roadmap)

#### Strategy 1: Store Expansion 🏪
- **Timeline:** Months 6-24
- **Target:** Expand from 15 to 50 stores
- **Financial Impact:** +$4.74M annual profit
- **Approach:** Market analysis → pilot (5 stores) → scaled expansion

#### Strategy 2: Product Diversification 🍰
- **Timeline:** Months 2-5
- **Initiatives:** Premium food line, branded retail products, subscription boxes
- **Financial Impact:** +$1.5M annual revenue, reduce beverage concentration
- **Target Mix:** Beverages 60% → Food 20% → Merchandise 20%

#### Strategy 3: Digital & Omnichannel Expansion 📱
- **Timeline:** Months 4-12
- **Initiatives:** Mobile app, delivery integration, corporate B2B programs, subscription service
- **Financial Impact:** +$2.6M incremental profit
- **Target:** 25% of orders through digital channels by Month 12

#### Strategy 4: Customer Acquisition at Scale 👥
- **Timeline:** Ongoing (Months 4-24)
- **Initiatives:** Enhanced loyalty program, digital marketing, community partnerships
- **Financial Impact:** Grow customer base from 2,000 to 10,000+ (+$7.27M profit)
- **Target CAC:** $10-15 per customer (LTV/CAC ratio: 18-40:1)

### 24-Month Financial Projections

| Metric | Current | Month 12 | Month 24 | Growth |
|--------|---------|----------|----------|--------|
| **Stores** | 15 | 20 | 50 | +233% |
| **Customers** | 2,000 | 5,000 | 10,000 | +400% |
| **Annual Revenue** | $1.92M | $4.20M | $9.60M | +400% |
| **Annual Profit** | $1.43M | $2.81M | $4.16M | +191% |
| **Profit Margin** | 74% | 67% | 43% | Blended |

---

## 🛠 Data Model

All dashboards are built on a **star-schema data model** with:

### Fact Table
- **Sales by Store:** Transaction-level data (transaction_id, date, time, store, staff, customer, product, quantity, price, promo flag)

### Dimension Tables
- **Product Lookup:** Product details, categories, pricing, cost, promo/new flags
- **Customer Lookup:** Customer demographics, loyalty enrollment, home store
- **Store Lookup:** Store location, neighborhood, size, manager
- **Employee Lookup:** Staff information and position
- **Calendar Table:** Complete date hierarchy (date, week, month, quarter, year)
- **Food Inventory:** Daily inventory tracking for waste analysis

---

## 🚀 Getting Started

### Prerequisites
- **Power BI Desktop** (latest version recommended)
- 2GB RAM minimum
- Windows 10+ or Mac with Power BI Desktop

### Installation Steps

1. **Clone the repository:**
```bash
git clone https://github.com/yourusername/daily-brew-coffee-analysis.git
cd daily-brew-coffee-analysis
```

2. **Open Power BI file:**
   - Launch Power BI Desktop
   - File → Open → Navigate to `Dataset/Md_Sahid_Coffee_Shop_Sales_Analysis.pbix`
   - Wait for data model to load (~30 seconds)

3. **Explore dashboards:**
   - Click through the 4 report pages
   - Use slicers (Year, Month, City, Store) to filter data
   - Hover over visuals for drill-down details

4. **Review analysis reports:**
   - Open `coffee_shop_sales_analysis_report.pdf` for detailed insights
   - Open `Daily_Brew_Complete_Growth_Report.pdf` for 24-month growth strategy

---

## 📊 Dashboard Features

### Interactive Elements
- **Multi-select slicers** for Year, Month, City, Store
- **Drill-down capabilities** on charts and tables
- **Hover tooltips** showing additional metrics
- **Responsive design** optimized for desktop and tablet viewing

### Key Measures (DAX Calculations)
```dax
Total Revenue = SUM(Sales[quantity_sold] * Sales[unit_price])
Total COGS = SUM(Sales[quantity_sold] * Products[current_cost])
Gross Profit = [Total Revenue] - [Total COGS]
Gross Profit Margin = [Gross Profit] / [Total Revenue]
Avg Revenue per Customer = [Total Revenue] / DISTINCTCOUNT(Sales[customer_id])
Promo Item % = CALCULATE([Total Revenue], Sales[promo_item_yn] = "Y") / [Total Revenue]
```

---

## 💼 Business Recommendations Summary

### Immediate Actions (Months 1-3)
1. **Standardize staff performance** using top-performer best practices
2. **Redesign promotional strategy** - reallocate budget to high-margin beverages
3. **Conduct market analysis** for store expansion locations
4. **Plan digital platform development** for mobile app and delivery

### Near-term Initiatives (Months 4-12)
1. **Launch mobile app** with order-ahead and loyalty integration
2. **Integrate delivery platforms** (DoorDash, Uber Eats, Grubhub)
3. **Develop premium food line** with artisan bakery partnerships
4. **Begin store expansion pilots** (5 new locations)
5. **Implement digital marketing campaigns** (Google Ads, Facebook, Instagram)

### Long-term Transformation (Months 13-24)
1. **Scale to 50-store network** across NYC metro area
2. **Expand subscription program** to 1,000+ monthly subscribers
3. **Launch corporate B2B programs** for office/catering services
4. **Grow customer base to 10,000+** through targeted acquisition
5. **Evaluate franchise/licensing** for accelerated growth

---

## 📈 Expected ROI

| Initiative | Year 1 Investment | Year 1 Impact | Year 2 ROI |
|-----------|------------------|---------------|-----------|
| **Staff Standardization** | $50K | +$200K profit | 300% |
| **Promotional Redesign** | $25K | +$80K profit | 220% |
| **Mobile App & Digital** | $150K | +$900K revenue | 500% |
| **Store Expansion (5)** | $750K | +$1.6M revenue | 150% |
| **Product Diversification** | $100K | +$300K revenue | 250% |
| **Customer Acquisition** | $200K | +$1.5M revenue | 650% |
| **TOTAL** | **$1.275M** | **+$4.58M revenue** | **260%** |

---

## 🔍 Data Sources

All data is based on the **Daily Brew Coffee Ltd. case study** dataset containing:

- **Sales Transactions:** 4,200+ transactions across 15+ stores
- **Customers:** 2,000 active loyalty members
- **Products:** 50+ items across 4 product categories
- **Staff:** 20+ employees with varying productivity levels
- **Time Period:** 2017-2019 (3 years of operational history)

---

## 📚 Documentation

### In this Repository
- **README.md** (this file) – Project overview and quick start guide
- **coffee_shop_sales_analysis_report.pdf** – Detailed dashboard analysis and insights
- **Daily_Brew_Complete_Growth_Report.pdf** – 24-month growth strategy and financial projections

### External Resources
- [Power BI Documentation](https://docs.microsoft.com/en-us/power-bi/)
- [DAX Language Reference](https://dax.guide/)
- [Coffee Industry Market Research](https://www.grandviewresearch.com/industry-analysis/coffee-market)

---

## 🎓 Learning Outcomes

By working through this case study, you will learn:

✅ **Power BI Skills**
- Star-schema data modelling
- DAX formula creation and optimization
- Interactive dashboard design
- Drill-down and filtering mechanics
- Power Query data transformation

✅ **Business Intelligence**
- Translating business questions into metrics
- Identifying key performance indicators
- Recognizing patterns and anomalies
- Creating actionable recommendations

✅ **Strategic Thinking**
- Data-driven decision making
- Financial analysis and projections
- Risk assessment and mitigation
- Growth strategy development

---

## 🤝 Contributing

Contributions are welcome! If you have improvements, bug fixes, or additional analyses:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit changes (`git commit -am 'Add improvement'`)
4. Push to branch (`git push origin feature/improvement`)
5. Create Pull Request

---

## 📄 License

This project is licensed under the **MIT License** – see LICENSE file for details.

You are free to use, modify, and distribute this project for educational and commercial purposes.

---

## 👤 Author

**Md Sahid** – Junior Business Intelligence Analyst  

- 📊 Specialization: Power BI, Data Modelling, Business Analytics
- 🎓 Focus: Software Quality Assurance & Data Science  
- 📍 Based in: Dhaka, Bangladesh
- 🔗 Connect: [LinkedIn](#) | [GitHub](#) | [Email](#)

---

## 📞 Support & Questions

For questions or issues related to this project:

1. **Check the FAQ section** below
2. **Review the detailed PDF reports** in the Reports folder
3. **Open a GitHub Issue** with a detailed description
4. **Contact the author** via email or LinkedIn

### Frequently Asked Questions

**Q: How do I refresh the data in Power BI?**  
A: In Power BI Desktop, go to Home → Refresh or press Ctrl+Shift+R. The model will re-query the source dataset.

**Q: Can I use this with my own coffee shop data?**  
A: Yes! Simply replace the CSV files with your data following the same schema, then refresh the Power BI model.

**Q: How do I add new visualizations?**  
A: Click "Edit in Power BI Desktop" → Insert new chart → Drag fields from the model → Customize appearance.

**Q: Is the 24-month growth plan realistic?**  
A: The projections are based on industry benchmarks and conservative assumptions. Actual results will vary by execution quality and market conditions.

---

## 🎯 Project Completion Status

| Component | Status | Last Updated |
|-----------|--------|--------------|
| Power BI Dashboard | ✅ Complete | Dec 2025 |
| Executive Analysis Report | ✅ Complete | Dec 2025 |
| Growth Strategy Report | ✅ Complete | Dec 2025 |
| HTML Dashboard | ✅ Complete | Dec 2025 |
| GitHub README | ✅ Complete | Dec 2025 |
| LaTeX Report | ✅ Complete | Dec 2025 |

---

## 📌 Quick Links

- 🏠 [Main Dashboard](Dashboards/main_page.png)
- 📊 [Store Performance](Dashboards/store_and_staff_performance.png)
- 👥 [Customer Analysis](Dashboards/product_and_customer_analysis.png)
- 📈 [Growth Strategy](Reports/Daily_Brew_Complete_Growth_Report.pdf)
- 📋 [Full Analysis](Reports/coffee_shop_sales_analysis_report.pdf)

---

## 🙏 Acknowledgments

This project was developed as a comprehensive case study demonstrating:
- Real-world power BI analytics
- Data-driven decision making
- Strategic business planning
- Professional reporting and documentation

Special thanks to all the stakeholders and team members who contributed to this analysis.

---

**Last Updated:** December 25, 2025  
**Project Status:** 🟢 Active & Maintained  
**Version:** 1.0.0  

⭐ If you found this project helpful, please consider giving it a star on GitHub!

---

## 📋 Table of Contents

- [Project Overview](#-project-overview)
- [Repository Structure](#-repository-structure)
- [Key Business Findings](#-key-business-findings)
- [Dashboard Overview](#-dashboard-overview)
- [Strategic Growth Recommendations](#-strategic-growth-recommendations)
- [Data Model](#-data-model)
- [Getting Started](#-getting-started)
- [Dashboard Features](#-dashboard-features)
- [Business Recommendations](#-business-recommendations-summary)
- [Expected ROI](#-expected-roi)
- [Data Sources](#-data-sources)
- [Documentation](#-documentation)
- [Learning Outcomes](#-learning-outcomes)
- [Contributing](#-contributing)
- [License](#-license)
- [Author](#-author)
- [Support & Questions](#-support--questions)

---

**Made with ☕ for Daily Brew Coffee Ltd.**
