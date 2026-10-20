# Hi, I'm Zara Gadzhieva 👋

Software developer · Python · SQL · JavaScript 

I build backends and data pipelines for domains where mistakes are expensive:
personal data, payroll, legal deadlines, regulated records. Two years of hands-on
development, on top of 12 years inside international organisations,
where I worked daily with structured XML data, cross-system reconciliation, access
management and incident resolution.

That combination is what I bring to a team: I read a regulation or a business process,
turn it into explicit rules, and ship them as tested, reviewed, documented code.

📍 Geneva · Swiss B permit · French, English, Russian

## Selected work

**[patent-xml-validator](https://github.com/Zuzz001zu/patent-xml-validator)** - XML data validation  
Checks PCT patent bibliographic data: schema validation with line numbers, 18 PCT business
rules (priority periods, numbering, kind codes, receiving office competence), XXE-safe parsing,
results stored in SQL and an HTML report for the people correcting the data.  
`Java 21` `XML / XSD` `JDBC` `H2` `JUnit 5` · CI with a generated report

**[headcount-data-quality](https://github.com/Zuzz001zu/headcount-data-quality)** - data pipeline  
Consolidates HR and payroll exports from three systems, runs 15 data quality rules
(including AVS check-digit validation and HR ↔ payroll cross-checks), computes headcount,
FTE and staff movements in SQL and generates an Excel report for the statistics team.  
`Python` `pandas` `SQL` `openpyxl` · 65 tests · CI on Python 3.11–3.13 · report built as a CI artifact

**[helpdesk-api](https://github.com/Zuzz001zu/helpdesk-api)** - REST API  
Ticketing backend with SLA due dates per priority, an enforced status workflow (invalid
transitions return 409), comments and a statistics endpoint.  
`FastAPI` `PostgreSQL` `SQLAlchemy 2.0` `Alembic` `Docker` · 30 tests run against PostgreSQL in CI

**[textstats-go](https://github.com/Zuzz001zu/textstats-go)** - CLI tool  
Text statistics from the command line with JSON output for scripting.  
`Go` · CI on Linux, macOS and Windows · cross-compiled release binaries

**[Kekstagram](https://github.com/Zuzz001zu/2515105-kekstagram-2)** · [demo](https://zuzz001zu.github.io/2515105-kekstagram-2/) - front-end app  
Image-sharing app in vanilla JavaScript with an LLM API for hashtag suggestions,
13 modules, input validation and XSS protection.  
`JavaScript ES6+` `REST` `Vite`

## Engineering practices

- Business rules isolated from transport and storage, each with its own tests
- Feature branches and pull requests; nothing merges without green CI
- Database schema versioned with migrations; drift checked in CI (`alembic check`)
- Validation at every boundary: API payloads, file imports, user input
- Reproducible environments with Docker; secrets kept out of the code
- Documentation that explains decisions, not only commands

## Stack

**Backend & data:** Python, FastAPI, Pydantic, SQLAlchemy, pandas, SQL (PostgreSQL, SQLite)  
**Front-end:** JavaScript (ES6+), HTML, CSS / Sass, Vite  
**Tooling:** pytest, Ruff, Docker, Git, GitHub Actions, Linux · Go for CLI tools

## Contact

[LinkedIn](https://www.linkedin.com/in/zuzz/)
