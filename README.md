# Job Recommendation Bot (n8n + OpenRouter)

An AI-powered chatbot built using n8n and OpenRouter.

## Features

* Job recommendations
* Resume guidance
* Cover letter assistance
* AI/ML career advice
* Internship guidance

## Workflow

Chat Trigger → HTTP Request (OpenRouter) → Edit Fields

## Setup

1. Import the workflow JSON into n8n.
2. Create an OpenRouter API key.
3. Update the Authorization header:

Bearer YOUR_OPENROUTER_API_KEY

4. Publish the workflow.
5. Open the chat interface and start interacting with the bot.

## Model Used

openai/gpt-4o-mini

## Author

Pardhu
