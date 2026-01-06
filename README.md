# agency-open-notebook
An open notebook about agency interventions in global development, powered by Open Notebook.

Open Notebook is a research notebook and source management tool: https://www.open-notebook.ai/

## Getting started
1. Copy `.env.example` to `.env` and add your API key.
2. Start the stack: `docker compose up -d`.
3. Open the UI at http://localhost:8502 (API at http://localhost:5055).

## Data and uploads
- Local runtime data (SQLite and caches) live under `notebook_data/` and are git-ignored.
- Uploaded source PDFs are kept in `notebook_data/uploads/` and are committed so others can review the same sources.
