# AI Feedback Triage

> AI decides when it can act autonomously — and when a human should take over.

## Problem

Customer feedback must be read, classified and prioritized. As volume increases, manual review becomes slower and important issues can be missed.

## Solution

The AI analyzes incoming feedback, validates the input and assigns a confidence / priority level.

## How it works

Customer feedback → input validation → AI analysis → confidence assessment.

- **High:** automatic response
- **Medium:** human review
- **Low:** request more information

Every result is logged in Google Sheets.

## Stack

n8n · OpenRouter · AI Agent · Google Sheets
