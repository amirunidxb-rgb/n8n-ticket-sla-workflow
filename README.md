# n8n Ticket SLA Workflow

A lightweight customer support ticketing workflow built with n8n, Google Sheets, and Gmail.

## Features

- Customer ticket submission form
- Automatic ticket ID generation
- Google Sheets ticket logging
- SLA timer based on ticket priority
- Automatic unresolved ticket alerts via Gmail
- Priority-based escalation logic

## Workflow Overview

1. Customer submits a support ticket
2. Ticket is stored in Google Sheets
3. SLA timer starts based on priority
4. Workflow checks if the ticket is resolved
5. If unresolved, an alert email is sent automatically

## Technologies Used

- n8n
- Google Sheets
- Gmail API

## Ticket Priorities

| Priority | SLA |
|---|---|
| Critical | 30 min |
| High | 75 min |
| Medium | 120 min |
| Low | 180 min |

## Import Workflow

1. Download the `Ticket.json` workflow file
2. Open n8n
3. Import workflow from JSON
4. Reconnect Google Sheets and Gmail credentials
5. Configure your spreadsheet and email settings

## Notes

This repository contains a sanitized version of the workflow.  
All credentials, webhook IDs, and sensitive metadata have been removed for security purposes.

## Author

Amirali Barmar
