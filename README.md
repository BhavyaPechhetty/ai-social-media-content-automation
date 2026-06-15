# AI Social Media Content Automation

## Overview

This project automates the process of creating and publishing social media content using AI-powered workflows.

The workflow uses Google Sheets as a trigger, Gemini AI for content generation, and LinkedIn integration for automated posting.

## Features

* Automated workflow using n8n
* Google Sheets trigger
* AI-powered content generation with Gemini
* LinkedIn post generation
* Social media content automation
* Workflow scheduling support

## Tech Stack

* n8n
* Google Sheets API
* Google OAuth 2.0
* Gemini AI
* LinkedIn API

## Workflow

1. Add article information to Google Sheets.
2. Google Sheets Trigger detects new data.
3. Gemini AI summarizes and generates content.
4. LinkedIn post is created automatically.
5. Content is published through the workflow.

## Project Structure

```text
project/
├── workflow.json
├── screenshots/
├── docs/
└── README.md
```

## Learning Outcomes

* Workflow Automation
* OAuth 2.0 Authentication
* API Integration
* Prompt Engineering
* AI-Powered Content Generation

## Screenshots

.
## Challenges Faced

- Configuring Google OAuth 2.0 credentials
- Managing API authentication in n8n
- Handling content formatting for LinkedIn posts
## Future Improvements

* Multi-platform posting
* Analytics dashboard
* Content approval workflow
* AI image generation support
