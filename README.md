### Hi, I'm Angel 👋

I like the whole path from **raw data to a decision**: pulling it from APIs and CSVs, modeling it in SQL, building the app around it and proving it works with tests. Most of what I build ends up as a database, a dashboard, or both.

- 📍 Based in Mexico
- 🎓 7th term, B.Eng. in IT & Digital Innovation (UTCGG); associate degree (TSU) in Multiplatform Software Development
- 🎯 Looking for a **Data Analyst or Software Developer internship in the U.S.** (Sep–Dec 2027, J-1 program)
- 📫 [LinkedIn](https://www.linkedin.com/in/%C3%A1ngel-andr%C3%A9s-valencia-contreras-726799400) · [Medium](https://medium.com/@angelandresvalenciaga.00) · [Email](mailto:angelandresvalenciaga.00@gmail.com)

---

## Selected work

### [ISP Coverage & Sales Portal](https://github.com/angel-valencia-c/isp-coverage-portal)
A regional internet provider was answering every "is there coverage at my address?" by phone. With a team of 3, we built a portal where customers check coverage, compare plans and request installation, and staff manage the leads.

- Admin panel with **3 roles**, lead notes, **duplicate detection** (same phone within 7 days) and filtered **CSV export**
- **Demand analytics** by municipality, community and covered vs. uncovered zones, to show where to expand next
- **220 automated tests (pytest), all passing, 77% coverage**

<img src="https://skillicons.dev/icons?i=python&theme=dark" width="28" height="28" alt="Python" title="Python" /> <img src="https://skillicons.dev/icons?i=flask&theme=dark" width="28" height="28" alt="Flask" title="Flask" /> <img src="assets/icons/sqlalchemy.svg" width="28" height="28" alt="SQLAlchemy" title="SQLAlchemy" /> <img src="https://skillicons.dev/icons?i=mysql&theme=dark" width="28" height="28" alt="MySQL" title="MySQL" /> <img src="assets/icons/pytest.svg" width="28" height="28" alt="pytest" title="pytest" /> &nbsp;<sub>+ Alembic, Flask-Login · client project, team of 3</sub>

### [ARC Raiders Loot Analysis](https://github.com/angel-valencia-c/arc-raiders-loot-analysis)
Which enemies drop the most valuable loot, and where? The Kaggle data hid its relationships in JSON strings inside CSV columns.

- ETL that flattens nested JSON into a **normalized 7-table SQLite schema** (1,021 rows)
- SQL joins + **5 seaborn/matplotlib charts**. Finding: *Queen* is worth **27,340** in loot, but only on 3 of the 6 maps
- 7 unit tests with GitHub Actions CI

<img src="https://skillicons.dev/icons?i=python&theme=dark" width="28" height="28" alt="Python" title="Python" /> <img src="assets/icons/pandas.svg" width="28" height="28" alt="pandas" title="pandas" /> <img src="https://skillicons.dev/icons?i=sqlite&theme=dark" width="28" height="28" alt="SQLite" title="SQLite" /> <img src="assets/icons/jupyter.svg" width="28" height="28" alt="Jupyter" title="Jupyter" /> <img src="assets/icons/matplotlib.svg" width="28" height="28" alt="Matplotlib" title="Matplotlib" /> <img src="assets/icons/pytest.svg" width="28" height="28" alt="pytest" title="pytest" /> <img src="https://skillicons.dev/icons?i=githubactions&theme=dark" width="28" height="28" alt="GitHub Actions" title="GitHub Actions" /> &nbsp;<sub>+ seaborn</sub>

### [URL Shortener Analytics](https://github.com/angel-valencia-c/url-shortener-analytics)
A link shortener built for marketing: every click is logged **before** the 302 redirect, so you know which campaign actually works.

- Captures UTM tags and ad click IDs (Google, Meta, TikTok, Microsoft), plus device and browser parsed from the User-Agent
- Password-protected dashboard with Chart.js trends, link editing, on/off switch and **Excel/CSV reports**

<img src="https://skillicons.dev/icons?i=python&theme=dark" width="28" height="28" alt="Python" title="Python" /> <img src="https://skillicons.dev/icons?i=flask&theme=dark" width="28" height="28" alt="Flask" title="Flask" /> <img src="https://skillicons.dev/icons?i=sqlite&theme=dark" width="28" height="28" alt="SQLite" title="SQLite" /> <img src="https://skillicons.dev/icons?i=js&theme=dark" width="28" height="28" alt="JavaScript" title="JavaScript" /> &nbsp;<sub>+ Chart.js, openpyxl</sub>

### Football Match Predictor <sub>private · in progress</sub>
Predicts match outcomes from historical results pulled from two sports-data REST APIs.

- ETL with rate-limit handling and upserts into SQLite
- Poisson goal model with time-decayed form, opponent-strength weighting and head-to-head history
- **Next:** a leak-free backtest scored with Brier score against a baseline

<img src="https://skillicons.dev/icons?i=python&theme=dark" width="28" height="28" alt="Python" title="Python" /> <img src="assets/icons/sqlalchemy.svg" width="28" height="28" alt="SQLAlchemy" title="SQLAlchemy" /> <img src="https://skillicons.dev/icons?i=sqlite&theme=dark" width="28" height="28" alt="SQLite" title="SQLite" /> &nbsp;<sub>+ SciPy, REST APIs</sub>

---

## How I work

I build with AI coding agents, but the decisions and the checks are mine. On the ISP portal it looked like this:

1. **Write the spec first**: requirements, business rules and acceptance criteria ([project spec](https://github.com/angel-valencia-c/isp-coverage-portal/blob/main/.agents/PROJECT.md)).
2. **Split it into phases** small enough to review in one sitting.
3. **Delegate to agents** with clear roles: [planner, executor and auditor](https://github.com/angel-valencia-c/isp-coverage-portal/tree/main/.agents).
4. **Nothing is done until the tests pass**: that phase-by-phase discipline is how the portal reached [220 tests](https://github.com/angel-valencia-c/isp-coverage-portal/tree/main/tests).

## Toolbox

<table>
  <tr>
    <td><b>Data</b></td>
    <td><img src="https://skillicons.dev/icons?i=python&theme=dark" width="40" height="40" alt="Python" title="Python" /> <img src="assets/icons/pandas.svg" width="40" height="40" alt="pandas" title="pandas" /> <img src="https://skillicons.dev/icons?i=mysql&theme=dark" width="40" height="40" alt="MySQL" title="MySQL" /> <img src="https://skillicons.dev/icons?i=sqlite&theme=dark" width="40" height="40" alt="SQLite" title="SQLite" /> <img src="assets/icons/jupyter.svg" width="40" height="40" alt="Jupyter" title="Jupyter" /> <img src="assets/icons/matplotlib.svg" width="40" height="40" alt="Matplotlib" title="Matplotlib" /><br/><sub>seaborn · SciPy · SQL</sub></td>
  </tr>
  <tr>
    <td><b>Backend</b></td>
    <td><img src="https://skillicons.dev/icons?i=flask&theme=dark" width="40" height="40" alt="Flask" title="Flask" /> <img src="assets/icons/sqlalchemy.svg" width="40" height="40" alt="SQLAlchemy" title="SQLAlchemy" /> <img src="https://skillicons.dev/icons?i=php&theme=dark" width="40" height="40" alt="PHP" title="PHP" /><br/><sub>Alembic · Flask-Login · REST APIs</sub></td>
  </tr>
  <tr>
    <td><b>Frontend</b></td>
    <td><img src="https://skillicons.dev/icons?i=html&theme=dark" width="40" height="40" alt="HTML" title="HTML" /> <img src="https://skillicons.dev/icons?i=css&theme=dark" width="40" height="40" alt="CSS" title="CSS" /> <img src="https://skillicons.dev/icons?i=js&theme=dark" width="40" height="40" alt="JavaScript" title="JavaScript" /><br/><sub>Chart.js · Jinja2</sub></td>
  </tr>
  <tr>
    <td><b>Quality & tools</b></td>
    <td><img src="assets/icons/pytest.svg" width="40" height="40" alt="pytest" title="pytest" /> <img src="https://skillicons.dev/icons?i=githubactions&theme=dark" width="40" height="40" alt="GitHub Actions" title="GitHub Actions" /> <img src="https://skillicons.dev/icons?i=git&theme=dark" width="40" height="40" alt="Git" title="Git" /> <img src="https://skillicons.dev/icons?i=linux&theme=dark" width="40" height="40" alt="Linux" title="Linux" /> <img src="https://skillicons.dev/icons?i=arch&theme=dark" width="40" height="40" alt="Arch Linux" title="Arch Linux" /><br/><sub>I daily-drive CachyOS (Arch)</sub></td>
  </tr>
</table>

## Right now

- 🧪 Making the football model's backtest honest: only past matches, Brier score vs. baseline
- ✍️ Writing about what I learn on [Medium](https://medium.com/@angelandresvalenciaga.00)

<sub>Last updated: November 2026</sub>
