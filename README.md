# Vola

**Vola** is a personal investment management web application. It is designed to replace complex spreadsheets with a structured, secure, and scalable platform that integrates data from multiple sources and provides clear dashboards for decision making.

---

## Features

* **Research Artefact Vault**: Upload and version research reports, fundamental analysis, narrative analysis, and screenshots (FinViz, Stock Rover, etc.).
* **Conviction Scoring**: Import Stock Rover CSVs to calculate and track conviction scores over time.
* **Macro / Regime Analysis**: Monitor CAEY and other indicators to determine market regimes.
* **Asset Allocation & Wealth Plan**: Define targets, track actual allocation, and generate rebalance suggestions.
* **Trade Management**: PFV ladders, TradingView alert ingestion, and profit-taking logic.
* **Performance Review**: Automatic trading journal with realized/unrealized P\&L, win rate, and R-multiples.
* **AI Integration**: Use OpenAI to summarize artefacts, detect inconsistencies, and generate narratives.
* **Backups & DR**: Automated nightly backups, off-site storage, and restore drills.

---

## Tech Stack

* **Frontend**: Retool (apps, tables, workflows)
* **Backend**: Supabase (Postgres + Auth + Storage + Realtime + pgvector)
* **APIs**: Supabase Edge Functions, OpenAI, TradingView webhooks
* **Infra/Automation**: GitHub Actions for CI/CD and backups

---

## Roadmap

This repository will track the staged development of Vola:

1. **Foundations**: Authentication, RLS, base schema
2. **Data Model MVP**: Tables for regime, conviction, artefacts, trades
3. **Serverless Endpoints**: Webhooks for TradingView, CSV ingestion, AI summaries
4. **Retool Clients**: Artefact Vault, Conviction, Regime Widget, Trade Monitor
5. **AI / RAG**: Embeddings and retrieval-augmented generation
6. **Backups & DR**: Automated pg\_dump and restore drills

---

## Project Status

🚧 Under active development — personal use only at this stage. Future versions may support multi-user scenarios.

---

## Naming

**Vola** comes from *volatility* — the app helps navigate and capitalize on market fluctuations.

---

## License

Private project. Not licensed for redistribution at this stage.
