# SyncMaster AI

A simple yet effective **Multi-Agent Productivity Assistant** built for the Gen AI Academy APAC Edition. This project demonstrates how to connect an AI agent to multiple enterprise data sources.

## What it does
SyncMaster AI connects three core Google Cloud tracks into one workflow:
- [cite_start]**Agent Logic:** Built using **Google ADK** (Track 1)[cite: 8].
- [cite_start]**Data Context:** Connects to **BigQuery** to retrieve technical notes (Track 2)[cite: 8].
- [cite_start]**Persistence:** Saves actionable tasks into **AlloyDB** (Track 3)[cite: 8].

## Tech Stack
- **Model:** Gemini 2.5 Flash.
- **Tools:** Google ADK, FastAPI, BigQuery, AlloyDB.
- **Platform:** Google Cloud Run.

## Workflow
1. User provides a prompt.
2. The agent identifies if it needs to check the calendar, search BigQuery, or save to AlloyDB.
3. The system executes the tools and returns a status confirmation.

## Links
- **Deployment:** https://syncmaster-api-165786782905.asia-southeast2.run.app
- **API Docs:** /docs