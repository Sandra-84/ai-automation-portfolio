# AI Knowledge Assistant with Human-in-the-Loop

> Every unanswered question can become new organizational knowledge.

## Problem

Employees repeatedly ask colleagues or experts the same questions. Valuable knowledge remains distributed across people instead of becoming reusable organizational knowledge.

## Solution

The AI agent first searches the company's knowledge base using RAG / Qdrant. If a reliable answer is found, it responds immediately. If not, the question is escalated to an expert, and the confirmed answer is added to the knowledge base.

## How it works

Employee question → AI Agent → RAG / knowledge search → answer found?

- **Yes:** answer the employee
- **No:** expert review → confirmed answer → store Q&A → update knowledge base

## Stack

n8n · OpenAI · RAG · Qdrant · OpenAI Embeddings · Google Sheets · Telegram
