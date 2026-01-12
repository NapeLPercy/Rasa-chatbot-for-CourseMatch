# CourseMatch Rasa Chatbot

This repository contains the Rasa-based conversational AI component for the CourseMatch platform.

## Overview
The chatbot assists users with:
- Course enquiries
- Eligibility checks
- Admission requirements
- General academic guidance

It uses intent classification and rule-based dialogue management, with custom actions that integrate with backend services.

## Tech Stack
- Rasa (NLU & Dialogue Management)
- Python (custom actions)
- Node.js / Express (external backend integration)
- MySQL (course and eligibility data)
- n8n (workflow orchestration)

## How It Works
1. User interacts with the chatbot via natural language.
2. Rasa extracts intents and entities.
3. Custom actions query backend services and databases.
4. Responses are returned based on deterministic logic.

## Running Locally

```bash
rasa train
rasa run
rasa run actions
