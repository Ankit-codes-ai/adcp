# ADCP Creative Agentic Platform — Assessment Submission

## Overview
This project implements the client-side of an Agentic Platform following AdCP's MCP protocol requirements.

Because Adzymic does **not** provide a real backend for assessment candidates, this submission includes a **local mock MCP backend** (`mock_agent.py`) that simulates:

- queued
- in_progress
- completed

This allows the project to run fully on Replit or locally.

## Test URL (Local)
```
http://127.0.0.1:8000/mcp
```

## How to Run on Replit or Locally

### 1. Install dependencies:
```
pip install flask streamlit requests
```

### 2. Start mock backend:
```
python mock_agent.py
```

### 3. Run the UI:
```
streamlit run ui_app.py
```

## Files Added
- `mock_agent.py` — local MCP simulation

