# AI Multi-Agent Support System

> A coordinated AI support architecture with specialized agents, human escalation and automated quality control.

## Problem

An online store receives product, order, return and warranty questions. Employees manually classify requests, search for information and prepare responses.

## Solution

A Router Agent identifies the request type and sends it to a specialized AI agent. Complex or uncertain cases can be escalated to a human operator.

## How it works

Customer request → Router Agent → specialized AI agent → response

Possible routes include:

- Product and Order Agent
- Returns & Warranty Agent
- Human Support

After the response is generated, an Evaluation Agent checks the quality of the answer and logs the result.

## Architecture

The workflow combines routing, specialized AI agents, knowledge retrieval, human escalation and automated response evaluation.

## Stack

n8n · OpenRouter · ChatGPT-4 · Telegram · Google Sheets · Qdrant / Vector Store
