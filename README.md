## Hi, I'm Diego 👋

I build small, useful systems that **automate real operational work** — booking pipelines, customer notifications, document processing, and the glue that holds them together. Most of what I ship is Python on the backend, talking to third-party APIs, deployed on Railway, and running for actual people who depend on it day to day.

### Focus

- **Automation & integrations** — WhatsApp Cloud API, booking platforms, OTA portals, PDF/Excel pipelines, GTFS open-data feeds.
- **Pragmatic backends** — Flask, SQLAlchemy, Postgres/SQLite, the smallest amount of framework that gets the job done.
- **Small interfaces with sharp edges** — server-rendered HTML, vanilla JS, native desktop wrappers when the workflow lives off the web.

### Featured projects

| Project | What it does |
|---|---|
| [**flask-whatsapp-cloud-api**](https://github.com/diegoals28/flask-whatsapp-cloud-api) | Production Flask backend for Meta's WhatsApp Cloud API: HMAC-verified webhooks, idempotent inbound dedup, dead-letter queue with exponential backoff, dry-run mode, admin dashboard with WhatsApp-style chat view. 64 tests. |
| [**flask-vouchers-app**](https://github.com/diegoals28/flask-vouchers-app) | Internal admin tool for a tour operator: voucher CRUD, supplier-account credentials, stats, Excel ingestion, JSON APIs. Single-file Flask, dual SQLite/Postgres backend, inline DDL migrations. |
| [**flask-mobile-autofill**](https://github.com/diegoals28/flask-mobile-autofill) | Phone-driven autofill for a third-party booking portal: select tour + date on mobile, a JS bookmarklet on desktop fetches and pastes the participants into the right fields, with DOM-aware ticket classification across 6 languages. |
| [**pdf-batch-splitter**](https://github.com/diegoals28/pdf-batch-splitter) | Hybrid Flask + PySide6/QtWebEngine desktop app, packaged as a single Windows `.exe` via PyInstaller. Splits a multi-booking ticket PDF into one file per booking using typo-tolerant `difflib` name matching. |
| [**roma-transit-live**](https://github.com/diegoals28/roma-transit-live) | Live ATAC Roma transit departure board built on open data (GTFS static + GTFS-Realtime). Flask + protobuf parser + dialect-aware bulk upsert. Real run: 8388 stops, 434 routes, 28k live RT predictions per poll. |

### Stack I reach for

`Python 3` · `Flask` · `SQLAlchemy` · `Alembic` · `PostgreSQL` · `SQLite` · `APScheduler` · `requests` · `pytest` · `Gunicorn` · `Railway` · `Bootstrap 5` · `vanilla JS` · `PySide6` · `PyInstaller` · `pypdf` · `openpyxl` · `protobuf` · `GTFS / GTFS-RT`

### Contact

- 📧 [diegolarasalgado1@gmail.com](mailto:diegolarasalgado1@gmail.com)
