### Hi, I'm Angel 👋

I like the whole path from **raw data to a decision**: pulling it from APIs and CSVs, modeling it in SQL, building the app around it and proving it works with tests. Most of what I build ends up as a database, a dashboard, or both.

- 📍 Based in Mexico
- 🎓 7th term, B.Eng. in IT & Digital Innovation (UTCGG); associate degree (TSU) in Multiplatform Software Development
- 🎯 Looking for a **Data Analyst or Software Developer internship in the U.S.** (Sep–Dec 2027, J-1 program)
- 📫 [LinkedIn](https://www.linkedin.com/in/%C3%A1ngel-andr%C3%A9s-valencia-contreras-726799400) · [Medium](https://medium.com/@angelandresvalenciaga.00) · [Email](mailto:angelandresvalenciaga.00@gmail.com)

---

## Selected work

### 📡 [ISP Coverage & Sales Portal](https://github.com/angel-valencia-c/isp-coverage-portal)
A regional internet provider was answering every "is there coverage at my address?" by phone. With a team of 3, we built a portal where customers check coverage, compare plans and request installation, and staff manage the leads.

- Admin panel with **3 roles**, lead notes, **duplicate detection** (same phone within 7 days) and filtered **CSV export**
- **Demand analytics** by municipality, community and covered vs. uncovered zones, to show where to expand next
- **220 automated tests (pytest), all passing, 77% coverage**

`Flask 3` `SQLAlchemy` `Alembic` `MySQL` `Flask-Login` · client project, team of 3

### 🎮 [ARC Raiders Loot Analysis](https://github.com/angel-valencia-c/arc-raiders-loot-analysis)
Which enemies drop the most valuable loot, and where? The Kaggle data hid its relationships in JSON strings inside CSV columns.

- ETL that flattens nested JSON into a **normalized 7-table SQLite schema** (1,021 rows)
- SQL joins + **5 seaborn/matplotlib charts**. Finding: *Queen* is worth **27,340** in loot, but only on 3 of the 6 maps
- 7 unit tests with GitHub Actions CI

`pandas` `SQLite` `Jupyter` `seaborn` `pytest`

### 🔗 [URL Shortener Analytics](https://github.com/angel-valencia-c/url-shortener-analytics)
A link shortener built for marketing: every click is logged **before** the 302 redirect, so you know which campaign actually works.

- Captures UTM tags and ad click IDs (Google, Meta, TikTok, Microsoft), plus device and browser parsed from the User-Agent
- Password-protected dashboard with Chart.js trends, link editing, on/off switch and **Excel/CSV reports**

`Flask` `SQLite` `Chart.js` `openpyxl`

### ⚽ Football Match Predictor <sub>private · in progress</sub>
Predicts match outcomes from historical results pulled from two sports-data REST APIs.

- ETL with rate-limit handling and upserts into SQLite
- Poisson goal model with time-decayed form, opponent-strength weighting and head-to-head history
- **Next:** a leak-free backtest scored with Brier score against a baseline

`SciPy` `SQLAlchemy` `REST APIs`

---

## How I work

I build with AI coding agents, but the decisions and the checks are mine. On the ISP portal it looked like this:

1. **Write the spec first**: requirements, business rules and acceptance criteria ([project spec](https://github.com/angel-valencia-c/isp-coverage-portal/blob/main/.agents/PROJECT.md)).
2. **Split it into phases** small enough to review in one sitting.
3. **Delegate to agents** with clear roles: [planner, executor and auditor](https://github.com/angel-valencia-c/isp-coverage-portal/tree/main/.agents).
4. **Nothing is done until the tests pass**: that phase-by-phase discipline is how the portal reached [220 tests](https://github.com/angel-valencia-c/isp-coverage-portal/tree/main/tests).

## Toolbox

| | |
|---|---|
| **Data** | Python · pandas · SQL (MySQL, SQLite) · Jupyter · matplotlib · seaborn · SciPy |
| **Backend** | Flask · SQLAlchemy · Alembic · REST APIs · PHP |
| **Frontend** | HTML · CSS · JavaScript · Chart.js |
| **Quality & tools** | pytest · GitHub Actions · Git · Linux (Arch / CachyOS) |

## Right now

- 🧪 Making the football model's backtest honest: only past matches, Brier score vs. baseline
- ✍️ Writing about what I learn on [Medium](https://medium.com/@angelandresvalenciaga.00)

<sub>Last updated: November 2026</sub>
