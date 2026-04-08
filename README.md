# SyncMaster AI

A simple and functional **Multi-Agent Productivity Assistant** developed for the Gen AI Academy APAC Edition. This project focuses on orchestrating automated workflows by connecting a central AI agent to various enterprise data platforms.

## Overview
SyncMaster AI is designed to handle fragmented tasks by bridging three core Google Cloud tracks:
* **Agent Orchestration:** Built using the **Google ADK** (Agent Development Kit) and deployed on **Cloud Run**.
* **Data Connectivity:** Integrated with **BigQuery** to retrieve and analyze historical technical notes.
* **Persistent Storage:** Connected to **AlloyDB AI** for saving and managing actionable tasks.

## Tech Stack
* **Model:** Gemini 2.5 Flash.
* **Orchestration:** Google ADK.
* **Backend:** FastAPI (Python).
* **Cloud Infrastructure:** Google Cloud Run, BigQuery, and AlloyDB.

## How It Works
1. **User Input:** The user provides a natural language request via the API.
2. **Task Analysis:** The agent determines which tools are needed (Calendar, BigQuery, or AlloyDB) based on the intent.
3. **Execution:** The system executes the specific database or tool calls in the background.
4. **Confirmation:** A structured JSON response is returned to confirm successful orchestration.

## API Documentation
Once the service is running, you can access the interactive Swagger UI documentation at:
`https://syncmaster-api-165786782905.asia-southeast2.run.app/docs`

