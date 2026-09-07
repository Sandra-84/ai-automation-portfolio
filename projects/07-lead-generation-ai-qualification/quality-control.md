# Quality Control

## Automated AI Response Quality Control

A scheduled workflow that tests AI agent responses against predefined test cases and evaluates their quality using a Judge Agent.

## Workflow

Scheduled Test Run
↓
Test Cases
↓
AI Agent
↓
Judge Agent
↓
Knowledge Base
↓
Score
↓
Google Sheets Log
↓
Alert if Score < Threshold

## How It Works

The workflow periodically runs predefined test cases against the AI agent.

The Judge Agent evaluates each answer using the knowledge base and assigns a score.

The result is recorded in Google Sheets.

If the score falls below the defined threshold, an alert is triggered.

## Technologies

- n8n
- Judge Agent
- Qdrant
- Embeddings
- Google Sheets
- Webhooks
- Gmail
- Telegram

## Key Concepts

Automated Testing · AI Evaluation · Judge Agent · Quality Control · Knowledge Grounding · Monitoring
