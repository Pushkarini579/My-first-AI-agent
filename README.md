# AI Chat Agent using n8n (Gemini + Memory + SerpAPI)

## Overview

This project is a simple AI-powered chat agent built using n8n and LangChain nodes. It can respond to user messages, maintain short-term memory for context, and fetch real-time information using Google search.

## Features

* Chat trigger to start the workflow on user input
* AI agent to process and respond to queries
* Google Gemini model for natural language understanding
* Memory buffer to retain last 7 interactions
* SerpAPI integration for real-time search results
* Optional calculator tool (currently disabled)

## Workflow Architecture

User Message → AI Agent →

* Gemini Model (language processing)
* Memory (context retention)
* Tools (search and calculator)

## Setup Instructions

### Prerequisites

* n8n installed (local or cloud)
* Google Gemini API access
* SerpAPI key

### Import Workflow

1. Open n8n
2. Go to Workflows
3. Click "Import from JSON"
4. Paste the provided JSON
5. Save and activate

### Configure Credentials

* Add Google Gemini API credentials
* Add SerpAPI credentials
* Attach them to respective nodes

### Run the Agent

* Click "Open Chat"
* Start interacting with the agent

## Customization

* Enable calculator tool if needed
* Increase memory window size
* Add more tools (APIs, database, etc.)
* Connect to external platforms like WhatsApp or Telegram

## Notes

* Memory is limited to 7 messages (configurable)
* Calculator node is disabled by default
* SerpAPI requires an API key

## Future Improvements

* Add long-term memory (database)
* Add system prompts for personality
* Build a frontend interface
* Deploy as a chatbot service

## Author

Pushkarini
