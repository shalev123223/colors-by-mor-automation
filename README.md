# Colors by Mor Automation

AI-powered content automation workflow built with n8n.

## Overview

This project automates the process of creating and publishing blog posts for a WordPress website.

The workflow receives a content idea through Telegram, sends it to an AI Agent, generates a structured blog article, parses the JSON response, publishes the article to WordPress, and sends a confirmation message back through Telegram.

## Workflow

Telegram Message  
↓  
n8n Telegram Trigger  
↓  
AI Agent using OpenRouter / Gemini  
↓  
JavaScript JSON Parser  
↓  
WordPress Blog Post  
↓  
Telegram Confirmation Message  

## Technologies

- n8n
- Telegram Bot API
- AI Agent
- OpenRouter
- Gemini
- WordPress API
- JavaScript
- JSON Parsing
- Workflow Automation

## Main Features

- Telegram-based content input
- AI-generated blog articles
- Structured JSON output
- Automatic WordPress publishing
- Telegram success notification
- End-to-end automation flow

## My Role

Designed and built the full automation workflow, including the Telegram trigger, AI prompt logic, JSON parsing, WordPress publishing step, and confirmation notification flow.

## Use Case

This workflow was created for Colors by Mor, a beauty and nail business, to simplify content creation and automate blog publishing.
