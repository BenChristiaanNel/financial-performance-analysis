Overview

This project is an interactive financial analysis dashboard built in Power BI that evaluates company performance and automatically translates financial statements into business insights.

Instead of only displaying metrics, the dashboard interprets them — simulating how a financial analyst would assess a company’s health, growth quality, risk level and operational efficiency.

The goal was to move from data reporting → decision support.

Business Questions Answered

The dashboard automatically evaluates:

Is the company growing sustainably?

Are profits improving or just revenue increasing?

Is growth efficient or requiring excessive assets?

Are profits backed by real cash flow?

Is leverage becoming risky?

Is overall financial health improving or deteriorating?

Key Features
Automated Financial Commentary

Dynamic DAX logic generates human-readable explanations such as:

“Revenue increased 106.4% YoY, profit margin improved 1.5 pp”

This converts raw KPIs into analyst-style interpretation.

Financial Health Classification

The model classifies company condition into categories:

Growth Quality

Risk Level

Efficiency Trend

Cash Flow Health

Instead of users interpreting ratios manually, the dashboard explains what they mean.

Time Intelligence Analysis

The dashboard compares the latest reporting period against previous periods using DAX time intelligence:

Year-over-Year Revenue Growth

Profit Margin Change

ROA / ROE Trends

Performance progression over time

Interactive Exploration

Users can dynamically filter periods to see how company performance evolves and how conclusions change accordingly.

Technical Implementation
Tools

Power BI

DAX

Data Modeling

Key Techniques Used

Time intelligence calculations

Dynamic previous-period comparison

Ratio analysis modeling

Conditional classification logic

Automated narrative generation (text measures)

KPI design for financial interpretation

Example Logic (Automated Insight)

The dashboard calculates changes between periods and generates narrative explanations:

Revenue trend → compared to previous period
Profit margin trend → improvement or deterioration
Combined → automatic interpretation text

This replicates the reasoning process of a financial analyst rather than a static report
