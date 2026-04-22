<div align="center">

# Pushpesh Kumar
### Data Analyst · Turning Raw Data into Business Decisions

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/pushpesh-kumar-38a5a1155/)
[![Email](https://img.shields.io/badge/Email-pushpeshkumar903%40gmail.com-EA4335?style=flat-square&logo=gmail)](mailto:pushpeshkumar903@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-181717?style=flat-square&logo=github)](https://github.com/Pushpesh987/Pushpesh987-Data-Analyst-Portfolio-)

</div>

---

## About Me

I'm a Data Analyst with hands-on experience transforming complex datasets into clear, actionable insights. My work spans sales performance analysis, financial budget tracking, and interactive dashboard development using Excel, Power BI, SQL, and Python.

I focus on the **full analytics workflow** — from raw data ingestion and cleaning to exploratory analysis, visualization, and business storytelling. My goal with every project is to answer the question: *"What should we do next?"*

---

## 📁 Projects

### 🥤 Coca-Cola U.S. Sales Analysis
**Tools:** Microsoft Excel · Pivot Tables · Charts · Slicers

> Analyzed multi-retailer U.S. sales data to uncover regional performance gaps, pricing dynamics, and seasonal demand patterns — delivered as a fully interactive Excel dashboard.

**Business Questions Answered:**
- Which regions and products drive the most revenue and margin?
- How does pricing affect sales volume across different markets?
- When are peak demand periods, and how should inventory respond?

**Key Findings:**
| Insight | Detail |
|---|---|
| 🏆 Top Region | West region leads all markets in revenue |
| 📦 Top Product | Sodapop drives highest revenue — margin optimization opportunity identified |
| 📅 Peak Period | June–August consistently shows highest demand |
| 💲 Pricing Signal | Optimal price band identified for volume-to-margin balance |

**Dashboard Features:** Regional filters, product-level drilldowns, time-series trend charts, and a correlation heatmap between price and volume.

🔗 [View Full Project on GitHub](https://github.com/Pushpesh987/coke-sales-analysis)

<details>
<summary>📸 Dashboard Screenshots</summary>

![Sales Analysis](https://raw.githubusercontent.com/Pushpesh987/coke-sales-analysis/main/screenshots/sales_analysis.png)
![Sales Analysis 2](https://raw.githubusercontent.com/Pushpesh987/coke-sales-analysis/main/screenshots/sales_analysis_2.png)
![Time Analysis](https://raw.githubusercontent.com/Pushpesh987/coke-sales-analysis/main/screenshots/time_analysis.png)
![Heatmap](https://raw.githubusercontent.com/Pushpesh987/coke-sales-analysis/main/screenshots/heatmap.png)

</details>

---

### 💰 IT Expenditure Analysis
**Tools:** Power BI · DAX · Power Query · Excel

> Built a 3-page Power BI dashboard to analyze IT spending across business units, geographies, and cost categories — comparing Actual vs. Forecast vs. Plan to flag budget deviations and drive spend accountability.

**Business Questions Answered:**
- Are we on budget, and where are the biggest variances?
- Which cost categories and regions are overspending?
- How reliable are our forecasts compared to actuals?

**Key Findings:**
| Insight | Detail |
|---|---|
| 📊 Budget Utilization | 92.78% of planned budget utilized overall |
| 👷 Labor Dependency | ~52% of total spend is labor, with high contractor reliance |
| ⚠️ Governance Gap | Infrastructure overspend spiked in December — poor spend controls |
| 🌍 Regional Blind Spot | USA underspend masked significant overspend in Spain & Germany |
| 📋 Planning Issue | Functional & Enablement areas consistently over-budgeted |

**Dashboard Pages:** Executive Summary · Variance Drilldown · Business Area Deep Dive

🔗 [View Full Project on GitHub](https://github.com/Pushpesh987/it-expenditure-analysis)

<details>
<summary>📸 Dashboard Screenshots</summary>

![Executive Summary](https://raw.githubusercontent.com/Pushpesh987/it-expenditure-analysis/main/screenshots/s1.png)
![Variance Drilldown](https://raw.githubusercontent.com/Pushpesh987/it-expenditure-analysis/main/screenshots/s2.png)
![Business Area Deep Dive](https://raw.githubusercontent.com/Pushpesh987/it-expenditure-analysis/main/screenshots/s3.png)

</details>

---

### 🤖 ChatGPT App Review Analysis
**Tools:** Python · Pandas · TextBlob · Matplotlib · Seaborn · WordCloud · Jupyter Notebook
 
> Performed end-to-end NLP and sentiment analysis on **193,148 real user reviews** from the ChatGPT mobile app — uncovering what users love, what frustrates them, and what drives star ratings.
 
**Business Questions Answered:**
- What is the overall sentiment landscape of ChatGPT's user base?
- Which specific words and themes drive positive vs. negative feedback?
- Does NLP-derived sentiment reliably correlate with numeric star ratings?
- What product pain points are users signaling, and how should the team respond?

**Key Findings:**
| Metric | Value |
|---|---|
| 📋 Reviews Analyzed | 193,148 |
| ⭐ 5-Star Share | 76.5% of all reviews |
| 😊 Positive Sentiment (NLP) | 74.1% — 143,111 reviews |
| 😐 Neutral Sentiment | 22.7% — a key conversion opportunity |
| 😠 Negative Sentiment | 3.2% — concentrated around answer quality & access |
| 🔗 Polarity–Rating Correlation | r = 0.33 (statistically significant) |
| 📝 Avg Review Length | 8.7 words — short reviews dominate |
| 🔑 Top Negative Signal | `wrong`, `bad`, `cant`, `doesnt` — usability & answer failures |
 
**Analysis Pipeline:**
1. **Data Cleaning** — Removed duplicates, null values, and non-English reviews; standardized text
2. **Feature Engineering** — Computed `polarity`, `subjectivity`, `review_length`, and `sentiment_label` using TextBlob
3. **EDA** — Rating distributions, review length histograms, sentiment breakdowns
4. **Text Analysis** — Top keywords for positive vs. negative reviews; word clouds per sentiment category
5. **Correlation Analysis** — Heatmap of ratings, polarity, subjectivity, and review length
6. **BI Dashboard** — 4-panel executive summary synthesizing all findings
**Key BI Insights:**
 
- **Answer quality is the #1 pain point** — `wrong`, `bad`, `doesnt` cluster tightly in 1-star reviews, pointing directly at output accuracy
- **22.7% neutral users are an untapped opportunity** — these are not dissatisfied, just unimpressed; targeted improvements could convert them to promoters
- **Longer reviews = more critical** — negative reviews average more words, making review length a reliable triage signal for support escalation
- **NLP sentiment tracks star ratings** (r = 0.33) — enabling automated review monitoring without relying on explicit scores
- **Satisfied users are emotionally expressive** — high polarity + high subjectivity signals ideal candidates for testimonial and referral campaigns

🔗 [View Full Project on GitHub](https://github.com/Pushpesh987/chatgpt-analysis)
 
<details>
<summary>📸 Visualization Screenshots</summary>
  
![Rating Distribution](https://github.com/Pushpesh987/chatgpt-analysis/blob/main/screenshots/rating_distribution.png)
![Sentiment Overview](https://github.com/Pushpesh987/chatgpt-analysis/blob/main/screenshots/sentiment_overview.png)
![Sentiment vs Rating](https://github.com/Pushpesh987/chatgpt-analysis/blob/main/screenshots/sentiment_vs_rating.png)
![Top Keywords](https://github.com/Pushpesh987/chatgpt-analysis/blob/main/screenshots/top_keywords_all.png)
![Word Clouds](https://github.com/Pushpesh987/chatgpt-analysis/blob/main/screenshots/wordclouds.png)
![Correlation Heatmap](https://github.com/Pushpesh987/chatgpt-analysis/blob/main/screenshots/correlation_heatmap.png)
![Insight Dashboard](https://github.com/Pushpesh987/chatgpt-analysis/blob/main/screenshots/insight_dashboard.png)
 
</details>

---

## 🛠 Skills & Tools

### Analytics & Querying
![SQL](https://img.shields.io/badge/SQL-Advanced-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-Data%20Analysis-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=flat-square&logo=numpy&logoColor=white)

**SQL:** Joins, Aggregations, Window Functions, Subqueries, CTEs, Views  
**Python:** Data cleaning, transformation, exploratory data analysis (EDA)

### Visualization & Reporting
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboards-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-Advanced-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=flat-square)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-4C72B0?style=flat-square)

**Power BI:** DAX measures, Power Query (M), relational data models, interactive reports  
**Excel:** Pivot Tables, Slicers, dynamic charts, conditional formatting, heatmaps

### Development & Environment
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-Version%20Control-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-CLI-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## 📫 Let's Connect

I'm open to **Data Analyst**, **Business Analyst**, and **BI Analyst** roles. If you're working on an interesting data problem or want to collaborate, reach out:

- 📧 [pushpeshkumar903@gmail.com](mailto:pushpeshkumar903@gmail.com)
- 💼 [LinkedIn — Pushpesh Kumar](https://www.linkedin.com/in/pushpesh-kumar-38a5a1155/)

---

<div align="center">
  <sub>Profile views: <img src="https://komarev.com/ghpvc/?username=Pushpesh987&style=flat-square&color=blue" alt="profile views"/></sub>
</div>
