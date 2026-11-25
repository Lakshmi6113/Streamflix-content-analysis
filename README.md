# Streamflix-content-analysis

## Project Overview
StreamFlix Content Analytics is an end-to-end data analytics project focused on understanding subscriber behaviour, content performance, and platform engagement for a fictional streaming platform.

The project uses Python for data cleaning, exploratory data analysis (EDA), and KPI calculations, followed by Power BI to create an interactive dashboard. The analysis helps identify viewing trends, subscriber patterns, content preferences, and opportunities to improve platform engagement and retention.

## Objectives
- Analyze subscriber demographics, subscription plans, and device preferences.
- Evaluate content performance by genre, type, and country.
- Understand monthly viewing trends and user engagement.
- Calculate important business KPIs related to subscriptions, churn, and watch time.
- Build an interactive Power BI dashboard to communicate insights.
- Provide actionable recommendations based on the analysis.

## Tools & Technologies
- **Python:** Pandas, NumPy, Matplotlib
- **Power BI:** Interactive dashboards and data visualization
- **Jupyter Notebook / Google Colab:** Data analysis and documentation
- **Microsoft Word:** Management report

## Datasets
The project uses six datasets:

| Dataset | Description |
|---|---|
| subscribers.csv | Subscriber details, plans, and subscription status |
| titles.csv | Content information, genres, and licensing details |
| watch_history.csv | Subscriber viewing activity |
| ratings.csv | Content ratings |
| reviews.csv | Subscriber reviews and sentiment |
| watchlist.csv | Titles added to subscriber watchlists |

## Project Workflow

### Phase 1: Data Cleaning & Quality Checks
- Loaded and inspected all six datasets using Pandas.
- Checked missing values, duplicate records, and data types.
- Validated date fields and numerical columns.
- Checked relationships between subscriber, title, and activity records.
- Prepared cleaned datasets for further analysis.

### Phase 2: Exploratory Data Analysis (EDA)
- Analyzed monthly viewing sessions and watch hours.
- Identified top-performing genres and content types.
- Compared viewing activity across countries.
- Explored subscriber plan and device distributions.
- Analyzed age groups, completion rates, and review sentiment.
- Created visualizations to identify trends and patterns.

### Phase 3: KPI Calculations
Calculated key business metrics, including:
- Total Watch Hours
- Active Subscriber Rate
- Churn Rate
- Average Completion Rate
- Monthly Recurring Revenue (MRR)
- Average Revenue Per Active Subscriber (ARPA)
- Average Watch Time Per Active Subscriber
- Watchlist Conversion Rate
- Top 10% Title Play Concentration
- Original Content Share of Watch Hours

### Phase 4: Power BI Dashboard & Management Report
Developed a five-page interactive Power BI dashboard:

1. **Engagement Overview** – Viewing trends and key engagement KPIs.
2. **Content Performance** – Genre performance, top titles, and completion rates.
3. **Subscriber Insights** – Subscription plans, countries, and subscriber growth.
4. **Viewer Experience** – Device usage, ratings, and review sentiment.
5. **Catalogue & Investment** – Original content, licensing, and catalogue analysis.

Prepared a management report summarizing key findings, risks, opportunities, and recommendations.

## Key Business Insights

- Total viewing time reached approximately **3.33 million hours**.
- The active subscriber rate was **74.66%**.
- The churn rate was **25.34%**.
- The average content completion rate was **65.31%**.
- TV Shows accounted for approximately **86.47%** of total watch hours.
- Drama was the leading genre by watch hours.
- Smart TVs were the most commonly used viewing device.
- Positive reviews represented the largest share of customer feedback.
- Watchlist conversion was approximately **1.22%**.
- Original content contributed approximately **27.17%** of total watch hours.

## Project Structure

```text
StreamFlix-Content-Analytics/
│
├── data/
│   ├── subscribers_cleaned.csv
│   ├── titles_cleaned.csv
│   ├── watch_history_cleaned.csv
│   ├── ratings_cleaned.csv
│   ├── reviews_cleaned.csv
│   └── watchlist_cleaned.csv
│
├── notebooks/
│   ├── Phase1_DataCleaning_Lakshmi_K.ipynb
│   ├── Phase2_EDA_Lakshmi_K.ipynb
│   └── Phase3_KPIs_Lakshmi_K.ipynb
│
├── visualizations/
│   └── EDA charts and analysis images
│
├── dashboard/
│   └── Phase4_Dashboard_Lakshmi_K.pbix
│
├── report/
│   └── Phase4_Report_Lakshmi_K.docx
│
└── README.md
```

*Note: Update the folder and file names to match the files you actually upload.*

## Conclusion
This project demonstrates an end-to-end data analytics workflow, from data cleaning and exploratory analysis to KPI calculation and interactive dashboard development. The insights provide a better understanding of subscriber engagement, content performance, and platform trends, supporting data-driven business decisions.

## Author
**Lakshmi K**  
Aspiring Data Analyst

**Skills Demonstrated:** Python | Pandas | NumPy | Matplotlib | Power BI | Data Cleaning | EDA | KPI Analysis | Data Visualization
