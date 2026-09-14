## Muawiyah Jahanzaib

I sit between **finance and engineering**. I take a financial process, work out what it actually has to produce, and build the system that produces it: the data pipeline, the calculation, the controls around it, and the screen someone uses.

BSc (Hons) Accounting and Business Management, **First Class**, Brunel University London, 2026.
London, UK &middot; [youngnug.com](https://youngnug.com) &middot; muawiyahjahan@gmail.com

---

### Projects

#### [MAHAD](https://github.com/5Muawiyah/MAHAD) &middot; desktop market-risk workstation

<a href="https://github.com/5Muawiyah/MAHAD"><img src="https://raw.githubusercontent.com/5Muawiyah/MAHAD/main/docs/images/dashboard.png" alt="The MAHAD dashboard: a live price chart, a watchlist, the risk panel, and a simulated portfolio with live profit and loss" width="720"></a>

Multi-Asset Heuristic Analytics Dashboard. Live stock and crypto data from eight providers, a simulated USD portfolio with live profit and loss, and a market-risk suite on top: historical and parametric Value-at-Risk, Expected Shortfall, component VaR, beta, Sharpe and Sortino, EWMA volatility, drawdown, concentration, and a Kupiec / Basel traffic-light backtest. Every figure is labelled with its window and basis, so two numbers for the same holding are never ambiguous. A CSV risk report exports straight from the database, with the window closed.

It carries the paperwork as well as the code: a requirements note tying each acceptance check to the test that proves it, a data dictionary, a methodology note stating every formula, and a verification note of hand-worked answers the tests are checked against.

Built in layers so the risk engine is pure Python with no Qt in it. That is what lets the headless suite — over 700 tests — run on every push across Windows and Linux on Python 3.11, 3.12 and 3.13, with `ruff` and `mypy` gating the same run.

`Python 3.11-3.13` `PySide6 / Qt` `NumPy` `SQLAlchemy` `pytest` `Hypothesis`

#### [YoungNug](https://github.com/5Muawiyah/youngnug-case-study) &middot; job-application platform &middot; lead developer and co-founder

A live UK job platform that collects vacancies, scores role fit with the reasons for and against, and drafts tailored applications. I lead its development. My work on it is system design and the security layer: authentication, per-user data isolation enforced in the query layer, encryption of sensitive fields at rest, GDPR export and deletion, and a browser companion built never to submit on a user's behalf.

The product source is private. The linked repository is a written case study of the architecture and the decisions behind it.

`Python` `FastAPI` `SQLAlchemy` `React` `TypeScript` `PostgreSQL`

#### [YoungNug Companion](https://github.com/5Muawiyah/youngnug-companion) &middot; browser extension for job applications &middot; open source

<a href="https://github.com/5Muawiyah/youngnug-companion"><img src="https://raw.githubusercontent.com/5Muawiyah/youngnug-companion/main/docs/img/review_screen.png" alt="The Companion's review screen: every guessed field and drafted answer listed for approval before anything is written to the form" width="720"></a>

The browser half of YoungNug, published in full under Apache-2.0. It captures a job advert from the page a student is reading and fills the application form from their profile, in their own signed-in browser. A dedicated adapter for each of eighteen application systems (Workday, Greenhouse, Lever, LinkedIn Easy Apply, Reed and the rest), a label-reading heuristic ladder for everything else, and one rule that never bends: it fills, shows a review screen, and stops. It never submits, never solves a captcha, never writes a password or a payment field, and a local kill switch works with the network down.

The repository is written analysis-first: the process a student repeats by hand, the requirements the extension is tested against, and the decision log with the alternatives rejected, before the build detail.

`JavaScript` `Chrome Manifest V3` `esbuild` `jsdom` `Playwright` `pytest`

---

### Where this comes from

Financial Management, Corporate Reporting, Accounting Information Systems and Managing Information with Technology all at A+, and a 40-credit final-year project on the IAS 16 treatment of GPUs and its effect on reported earnings and return on assets.

Code is how I make the finance work at scale. Both halves are the point.

### Toolbox

**Data and code** &middot; Python (pandas, NumPy, pytest), SQL, SQLite / PostgreSQL / SQLAlchemy, TypeScript and React, PySide6 / Qt, Git

**Finance** &middot; financial modelling and DCF, market-risk analytics (VaR, Expected Shortfall), double-entry bookkeeping, Sage 50, advanced Excel

---

Open to graduate roles in financial systems, business analysis and risk. Reach me at **muawiyahjahan@gmail.com**.
