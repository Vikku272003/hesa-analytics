#  HESA Student Enrolment & Tuition Revenue Analysis

A end-to-end data analytics project analysing UK Higher Education student 
enrolment trends and tuition revenue impact using real HESA data (2020/21 – 2024/25).

##  Project Overview

This project was built to demonstrate real-world data analytics skills applied 
to the UK Higher Education sector. It covers the full analytics pipeline — from 
raw messy data through to a cloud database, SQL queries, and professional visualisations.

**Key questions answered:**
- Are UK student enrolments growing or declining?
- How has international student recruitment changed since 2022/23?
- What is the estimated tuition revenue impact of these trends?
- How does the University of Greenwich compare to national benchmarks?

##  Tech Stack

| Tool | Purpose |
|---|---|
| Python 3 | Core programming language |
| pandas | Data cleaning & manipulation |
| matplotlib | Data visualisation |
| SQLAlchemy | Python to PostgreSQL connection |
| PostgreSQL 17.6 | Cloud database (Supabase) |
| Google Colab | Development environment |
| HESA Open Data | Data source |

##  Key Findings

### Student Enrolments
- UK HE enrolments peaked at 2.94M in 2022/23
- Enrolments have declined for 2 consecutive years since
- International students dropped by 73,000 (9.7%) from peak

### University of Greenwich
- Greenwich grew 59% over 10 years (18,655 to 29,695)
- First enrolment decline recorded in 2024/25
- Greenwich growth outperformed the national average

### Tuition Revenue
- UK HE tuition revenue peaked at £34.7bn in 2022/23
- Revenue has fallen by £1.4bn since peak
- Primary driver: international student decline post-2022/23

## Data Sources

| Dataset | Source | Years |
|---|---|---|
| HE student enrolments (national) | HESA SB273 Figure 3 | 2020/21 to 2024/25 |
| HE enrolments by provider | HESA DT051 Table 1 | 2015/16 to 2024/25 |

Data published under Creative Commons Attribution 4.0 International Licence.

##  How to Run

1. Download data from HESA website
2. Upload files to Google Colab
3. Create free Supabase account
4. Add database password to Colab Secrets as SUPABASE_PASSWORD
5. Run all cells in order

##  Disclaimer

Revenue figures are estimates based on published fee assumptions and 
HESA headcount data. Actual institutional income will vary.

##  Author

Vikasitha  
University of Greenwich  
Data Analytics Portfolio Project 2025/26
