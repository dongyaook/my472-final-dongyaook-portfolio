# Olympic Gender Participation and Medal Performance Analysis (1896–2020)

This project presents an integrated analysis of gender participation trends and medal performance in the Summer Olympic Games from 1896 to 2020. It combines multi-source data to explore gender disparities, their historical evolution, and links to broader social development indicators.

## Project Overview

- Tracks the evolution of male and female athlete participation in the Summer Olympics.
- Analyses gender differences in medal performance across countries and time.
- Investigates correlations between gender equality in sports and global development indicators, such as the United Nations Gender Inequality Index (GII).
- Demonstrates an end-to-end data pipeline from acquisition to reproducible reporting.

## Technical Highlights

- Static web scraping using **CSS selectors** and **XPath** within R.
- Dynamic web scraping with **Selenium** for interactive websites.
- Public **API integration** to enrich datasets.
- Relational database management and querying with **SQLite** and **SQL**.
- Data cleaning, integration, and analysis using **R**, **tidyverse**, and **dplyr**.
- Statistical modelling, regression analysis, and insight generation.
- Data visualisation of gender trends, participation rates, medal performance, and development indicators.
- Reproducible reporting with **RMarkdown** and interactive **HTML** outputs.

## Data Sources

All datasets used are publicly accessible and intended for academic or research purposes:

- **Olympic Medal Statistics:** [Wikipedia](https://en.wikipedia.org/wiki/All-time_Olympic_Games_medal_table)
- **Athlete and Event Records:** [Kaggle - Olympic Dataset](https://www.kaggle.com/)
- **Historical Olympic Data:** [Olympedia](https://www.olympedia.org/)
- **Global Development Indicators:** [United Nations Development Programme - GII](https://hdr.undp.org/)

## Repository Structure

- `MY472-AT24-final-report.Rmd`: Full reproducible analysis script.
- `MY472-AT24-final-report.html`: Interactive report with visual outputs.
- `/database`: SQLite database for relational data management.
- `/rowdata`: Raw datasets from multiple sources.
- `/output`: Processed data and analytical results.
- `.gitignore` and `.Rhistory`: Version control and project configuration files.

## About the Author

**Dongyao**  
Email: dongyaook@outlook.com  

---

*Originally developed as part of academic coursework at LSE, this project is presented as a professional portfolio example to demonstrate capabilities in data acquisition, relational databases, statistical analysis, and reporting.*
