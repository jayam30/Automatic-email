# Email Automation Service

This project is an **Email Automation Service** that automatically processes incoming emails from Gmail and Outlook, categorizes them using OpenAI, and responds based on their category. The application uses Redis and BullMQ for queuing and background job processing.

## Features

- **OAuth Authentication** for Gmail and Outlook
- **Email Categorization** with OpenAI GPT-3.5-turbo
- **Automated Responses** based on email category
- **Background Processing** with Redis and BullMQ for handling email jobs
- **RESTful API** to initiate email processing and handle OAuth callbacks


## Prerequisites

- **Node.js** (>=14.x)
- **Redis** (>=5.x)
- **Google and Microsoft developer accounts** for Gmail and Outlook OAuth setup
- **OpenAI API key** for email categorization and response generation

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/email-automation.git
   cd email-automation
# Gmail OAuth
GMAIL_CLIENT_ID=your_gmail_client_id
GMAIL_CLIENT_SECRET=your_gmail_client_secret
GMAIL_REDIRECT_URI=http://localhost:3000/auth/gmail/callback

# Outlook OAuth
OUTLOOK_CLIENT_ID=your_outlook_client_id
OUTLOOK_CLIENT_SECRET=your_outlook_client_secret
OUTLOOK_REDIRECT_URI=http://localhost:3000/auth/outlook/callback

# OpenAI API
OPENAI_API_KEY=your_openai_api_key

# Redis Configuration
REDIS_HOST=localhost
REDIS_PORT=6379

# Server Configuration
PORT=3000

 
