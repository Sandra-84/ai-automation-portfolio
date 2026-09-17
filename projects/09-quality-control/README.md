# AI Response Quality Control

> Automated evaluation helps monitor the quality of AI-generated responses.

## Purpose

A supporting workflow for automated monitoring of AI answer quality.

A scheduled workflow runs test cases against the AI agent. A Judge Agent with access to the knowledge base evaluates each answer, logs the result and can trigger alerts when the score falls below the defined threshold.

## How it works

Scheduled trigger → test dataset → risk / routing logic → LLM evaluation → restore tokens → final review output

The evaluation results are logged for monitoring and quality control.

## Capabilities

- Scheduled AI testing
- Automated response evaluation
- Judge Agent
- Knowledge-base-aware evaluation
- Quality logging
- Threshold-based monitoring

## Stack

n8n · Judge Agent · Qdrant · OpenAI Embeddings · Google Sheets · Webhooks · Gmail · Telegram
