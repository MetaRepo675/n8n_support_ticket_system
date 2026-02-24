# Automated Support Ticket Management System with n8n

This project is a workflow in n8n that automatically processes emails received in the support mailbox, creates a ticket, sends an automatic response, and notifies the team.

 ## Features
- Gmail inbox monitoring (emails with specific labels)
- Email information extraction (sender, subject, body)
- Automatic ticket registration in Google Sheets (for follow-up)
- Card creation in Trello (as support ticket)
- Automatic acknowledgement response to user
- Notification to support group in Telegram
- AI-enabled extension for prioritizing tickets

## Prerequisites
- n8n installed (local or cloud)
- Gmail account with Gmail API enabled
- Google Sheets account (for storing logs)
- Trello account and a board with a specific list
- Telegram bot and support group chat ID
- (optional) OpenAI key for smart analytics

## Setup

1. Clone this repository:
```bash
git clone https://github.com/yourusername/n8n-support-ticket-system.git
cd n8n-support-ticket-system
