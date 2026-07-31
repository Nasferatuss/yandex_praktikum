# Data Analyst portfolio — Yandex.Praktikum

Thirteen projects from the Yandex.Praktikum Data Analyst program, in the order they were
completed. The progression is deliberate: from data cleaning with pandas, through
statistical hypothesis testing and SQL, to cohort economics, A/B analysis and a deployed
dashboard.

Every notebook keeps its outputs — charts and tables render directly on GitHub, no need to
run anything, which is just as well: the data lives in the Praktikum sandbox at `/datasets/`
and is not redistributable. **The notebooks themselves are written in Russian**; this README
is the map.

## Projects

| Project | Question it answers | Stack |
| --- | --- | --- |
| [big_cities_music](big_cities_music) | Do Moscow and St. Petersburg listen to different music, and at different hours? Real Yandex.Music data. | pandas |
| [banks](banks) | Do marital status and number of children affect whether a borrower repays on time? Bank credit-department data. | pandas |
| [apartment_spb](apartment_spb) | What drives apartment prices in St. Petersburg, and how do typical parameters change with distance from the centre? | pandas, Matplotlib |
| [telecom_tarif](telecom_tarif) | Which of two telecom plans earns more? Includes hypothesis tests on revenue between plans and between Moscow and the regions. | pandas, NumPy, SciPy, Matplotlib |
| [games_succes](games_succes) | What makes a video game succeed, and how does that differ by region? Regional user portraits and hypothesis tests, for ad-campaign planning. | pandas, NumPy, Matplotlib |
| [venture_fund](venture_fund) | Venture funds and their startup investments — queried straight from the database. | SQL, PostgreSQL |
| [application_loss](application_loss) | Why is ProcrastinatePRO+ losing money? Cohort analysis: LTV, CAC, ROI, retention, DAU/WAU/MAU. | pandas, Matplotlib, Seaborn |
| [stackoverflow](stackoverflow) | StackOverflow posts from 2008, analysed in pure SQL. | SQL, PostgreSQL |
| [revenue_store](revenue_store) | Which growth hypotheses to run, and did the A/B test win? ICE/RICE prioritisation, cumulative revenue and conversion curves, significance on raw and cleaned data. | pandas, SciPy, Matplotlib |
| [catering_market](catering_market) | Where should a new restaurant open in Moscow? Open-data market study, presented for investors. | pandas, Seaborn, Plotly |
| [mobile_app](mobile_app) | Where do users drop out of a food-delivery app? Sales funnel, path to purchase, A/A/B test results. | pandas, Matplotlib, Seaborn, Plotly |
| [dashboard_event](dashboard_event) | A dashboard on user events for a news aggregator. Built on a provisioned Yandex.Cloud VM: PostgreSQL deployed, a cron'd collection pipeline, a filtered Dash app. The VM is gone — what is here is the [published dashboard](https://public.tableau.com/app/profile/maxim1170/viz/My_First_Viz_16694721975350/_?publish=yes) and the deck, not code. | SQLAlchemy, PostgreSQL, Dash, Tableau |
| [graduation_project](graduation_project) | **Capstone.** Which segments of a regional bank's customers are about to churn? Segmentation, plus A/B testing and SQL assignments. | pandas, SciPy, Matplotlib, Seaborn, SQL, PostgreSQL |

## What this covers

**Analysis** — exploratory data analysis, cleaning and preprocessing, segmentation, cohort
analysis and unit economics (LTV, CAC, ROI, retention).

**Statistics** — hypothesis testing, A/B and A/A/B test design and evaluation, statistical
significance on raw versus cleaned data.

**SQL** — aggregation, joins and window functions against PostgreSQL, both as the analysis
tool itself and as the source layer.

**Delivery** — charts and dashboards (Matplotlib, Seaborn, Plotly, Dash, Tableau), plus
investor- and stakeholder-facing presentations.

## License

MIT — see [LICENSE](LICENSE).
