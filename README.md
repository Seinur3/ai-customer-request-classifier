# AI Customer Request Classifier

A small AI-powered automation prototype built with n8n and Google Gemini API.

## Overview

This project demonstrates how AI can help customer support teams classify incoming requests and route them to the appropriate departments.

## Technologies

- n8n
- Google Gemini API
- Google Sheets API
- JSON

## How It Works

1. A sample customer message is provided through a manual trigger.
2. Google Gemini analyzes the message and classifies it into one of four categories: PAYMENT, DOCUMENTS, COMPLAINT or OTHER.
3. n8n routes the message to the corresponding workflow branch.
4. The PAYMENT branch automatically saves the request, category, department and status to Google Sheets.

## Current Status

Working MVP prototype. The payment-processing branch has been tested end-to-end. The remaining categories have routing branches configured but are not yet fully integrated with Google Sheets.

## Future Improvements

- Automated email intake
- CRM integration
- Human review for uncertain classifications
- Error handling and logging
- Evaluation of classification accuracy

## Workflow

Add a screenshot of the n8n workflow here.
