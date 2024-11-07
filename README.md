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



 
