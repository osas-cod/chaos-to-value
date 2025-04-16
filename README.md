# Chaos-to-Value System

This project transforms unstructured, chaotic data into structured, actionable insights using GPT and silent processing systems.

## What it does

- Ingests chaotic data (logs, APIs, files, etc.)
- Silently processes: cleans, segments, detects anomalies
- GPT-4 extracts patterns, insights, and value
- Routes insights to dashboards, alerts, or APIs

## Local Setup

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload
