# SyncMaster AI

A simple and functional **Multi-Agent Productivity Assistant** developed for the Gen AI Academy APAC Edition. This project focuses on orchestrating automated workflows by connecting a central AI agent to various enterprise data platforms.

## Overview
SyncMaster AI is designed to handle fragmented tasks by bridging three core Google Cloud tracks:
* [cite_start]**Agent Orchestration:** Built using the **Google ADK** (Agent Development Kit) and deployed on **Cloud Run**[cite: 7, 8].
* [cite_start]**Data Connectivity:** Integrated with **BigQuery** to retrieve and analyze historical technical notes[cite: 7, 8].
* [cite_start]**Persistent Storage:** Connected to **AlloyDB AI** for saving and managing actionable tasks[cite: 7, 8].

## Tech Stack
* [cite_start]**Model:** Gemini 2.5 Flash[cite: 18, 19].
* [cite_start]**Orchestration:** Google ADK[cite: 18, 19].
* [cite_start]**Backend:** FastAPI (Python)[cite: 18, 19].
* [cite_start]**Cloud Infrastructure:** Google Cloud Run, BigQuery, and AlloyDB[cite: 18, 19].

## How It Works
1.  [cite_start]**User Input:** The user provides a natural language request via the API[cite: 16, 17].
2.  [cite_start]**Task Analysis:** The agent determines which tools are needed (Calendar, BigQuery, or AlloyDB) based on the intent[cite: 16, 17].
3.  [cite_start]**Execution:** The system executes the specific database or tool calls in the background[cite: 16, 17].
4.  [cite_start]**Confirmation:** A structured JSON response is returned to confirm successful orchestration[cite: 16, 17].

## API Documentation
Once the service is running, you can access the interactive Swagger UI documentation at:
`https://syncmaster-api-165786782905.asia-southeast2.run.app/docs`
