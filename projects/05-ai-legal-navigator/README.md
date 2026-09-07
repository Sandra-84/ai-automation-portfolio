# AI Legal Navigator

## AI-Powered Legal Information Routing

An AI workflow for handling routine legal questions, retrieving relevant information from a knowledge base and escalating cases to human support when needed.

## Problem

Routine legal questions can require searching through large amounts of information before an appropriate response can be prepared.

## Solution

The workflow routes legal questions to the appropriate workflow and uses RAG-based knowledge retrieval to provide relevant information.

Cases that require additional review can be escalated to human support.

## Workflow

User Request
↓
Request Routing
↓
RAG / Knowledge Retrieval
↓
AI Processing
↓
Response / Human Escalation

## Architecture

![AI Legal Navigator architecture](05-architecture.png)

## Technologies

- n8n
- OpenRouter
- LLM
- RAG
- Qdrant
- OpenAI Embeddings
- Telegram
- Gmail
- Google Sheets

## Business Value

- Route routine legal questions to appropriate workflows
- Retrieve relevant information from a knowledge base
- Support structured AI-assisted responses
- Escalate cases requiring human review

## Key Concepts

AI Agents · RAG · Knowledge Retrieval · Workflow Routing · Human-in-the-Loop · n8n

