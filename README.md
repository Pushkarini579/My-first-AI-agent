# AI Chat Agent using n8n (Gemini + Memory + SerpAPI)

## Overview

This project is a simple AI-powered chat agent built using n8n and LangChain nodes. It responds to user messages, maintains short-term memory for contextual conversations, and fetches real-time information using Google search.

## Live Workflow

Access the deployed workflow here:
https://nani1.app.n8n.cloud/workflow/FbWopYGxmEj76E40

## Features

* Chat trigger to start the workflow on user input
* AI agent for intelligent response generation
* Google Gemini model for language processing
* Memory buffer to retain last 7 interactions
* SerpAPI integration for real-time search
* Optional calculator tool (currently disabled)

## Workflow Architecture

User Message → AI Agent →

* Gemini Model (language understanding)
* Memory (context retention)
* Tools (search and calculator)

## Setup Instructions

### Prerequisites

* n8n (cloud or self-hosted)
* Google Gemini API access
* SerpAPI key

### Import Workflow

1. Open n8n
2. Navigate to Workflows
3. Click "Import from JSON"
4. Paste the workflow JSON
5. Save and activate

### Configure Credentials

* Add Google Gemini API credentials
* Add SerpAPI credentials
* Connect them to respective nodes

### Run the Agent

* Click "Open Chat"
* Start interacting with the AI agent

## Customization

* Enable calculator tool for math queries
* Increase memory window size
* Add external APIs or database integration
* Connect to messaging platforms (WhatsApp, Telegram)

## Notes

* Memory is limited to 7 messages (configurable)
* Calculator node is disabled by default
* SerpAPI requires a valid API key

## Future Improvements

* Add long-term memory storage
* Introduce system prompts for personality
* Build a frontend UI
* Deploy as a full chatbot service

## Author

Pushkarini
