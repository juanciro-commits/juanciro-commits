# Hi, I'm Juan Salazar

I'm an Industrial Engineer with hands-on experience in procurement and project management, gained through progressive roles in the FMCG sector. Currently pursuing a Master of Science in Business Analytics. I like turning messy operational data into dashboards, pipelines, and decisions that actually get used.

- Studying: **MS in Business Analytics** @ University of Central Florida (expected Summer 2027)
- Background: **BS in Industrial Engineering** @ Universidad del Valle, Cali, Colombia (GPA 3.73/4.0)
- Currently exploring: portfolio optimization and out-of-sample backtesting, Python-based ETL pipelines, Supabase/PostgreSQL, Neon (serverless Postgres), and AI-assisted development with Claude Code

**Programming & Data**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Neon](https://img.shields.io/badge/Neon-00E599?style=for-the-badge&logo=neon&logoColor=black)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

**Tools & Workflow**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Claude](https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)

## Featured Projects

### [Portfolio Allocation: Minimum Variance vs. 1/N](https://github.com/juanciro-commits/Portfolio-Allocation-Project)

Builds minimum-variance portfolios on 9 multi-asset ETFs (U.S. and international stocks, Treasuries, corporate bonds, gold, REITs) with daily data from 2005 to 2026, and studies how they behave out of sample against an equal-weight (1/N) benchmark through the 2008 crisis, the COVID crash and the 2022 inflation shock.

- Monthly rolling-window backtest (225 rebalances, Feb 2008 – Oct 2026) of unconstrained, long-only (numerical optimizer) and volatility-targeted leveraged versions, with turnover, trading costs, a no-trade band and borrowing-cost sensitivity
- Minimum variance cut volatility to about a third of 1/N's (4.5% vs 12.9%) and max drawdown from −37.2% to −13.9%, with a higher Sharpe ratio (0.48 vs 0.40)
- That edge depended on the rate regime: Sharpe 0.79 vs 0.49 in 2008–2021, but −0.24 vs 0.08 in 2022–2026, when the stock–bond correlation turned positive
- With realistic borrowing spreads and short fees, the leveraged version's advantage over 1/N disappears
- 📓 Python · pandas · NumPy · yfinance · Jupyter

### Warehouse Storage Optimization — Bachelor's Thesis

Built a data pipeline analyzing 15,274 historical orders and inventory records (Power BI + Excel trapezoidal method) and applied the Cube Per Order Index (COI) to design a data-driven storage assignment model. Validated the model through discrete-event simulation in FlexSim.

- Picker travel distance: 954.01 km → 687.34 km (**-27.95%**)
- Throughput: 68.07 → 81.52 orders/hour (**+19.77%**)
- 📄 [Thesis presentation (PDF)](Thesis_Presentation.pdf)

### [NBA Analytics Dashboard](https://github.com/FernandoValencia-DS/nba-analytics-pipeline)

Collaborative project with an automated ETL pipeline in Python that pulls live NBA game and player data from the NBA API into a Neon database on a daily schedule via GitHub Actions. Power BI connects directly to Neon for automatic refreshes.

- Two interactive dashboards: player comparison (shot charts, percentiles) and team comparison (head-to-head, season performance)
- Built in paired sessions using Git/GitHub for version control, with Claude Code assisting on script development
- 📊 [Live Power BI dashboard](https://app.powerbi.com/view?r=eyJrIjoiYjE1MzhmZjAtMzhkZS00NjJlLTlhMTEtMDg5ZGIyZjAxNjAwIiwidCI6ImZkNzY2ZWRkLThiZWEtNGM5OS04NjcyLTU2ZDFjYWJjMjcwNiIsImMiOjR9&pageName=20fe8de5bda3640e3517)

## Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/juan-pablo-salazar-ciro/)
[![Handshake](https://img.shields.io/badge/Handshake-D3423E?style=for-the-badge&logo=handshake&logoColor=white)](https://app.joinhandshake.com/profiles/juan-salazar)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:juan.ciro@correounivalle.edu.co)
