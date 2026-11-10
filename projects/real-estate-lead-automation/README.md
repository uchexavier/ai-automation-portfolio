# Real Estate Lead Automation System

## Project Overview

An AI-powered lead management workflow designed to help real estate businesses capture, qualify, organize, and prioritize incoming property enquiries.

The system automates the process of extracting important information from enquiries, updating lead records, and notifying the relevant team through WhatsApp.

## Business Problem

Real estate teams often receive enquiries containing incomplete or unstructured information. Manually reviewing and organizing these enquiries can lead to:

- Delayed responses to potential clients.
- Poor lead organization.
- Missed high-priority opportunities.
- Time-consuming administrative work.

## Solution

This workflow uses n8n and AI-powered information extraction to process incoming property enquiries and organize them into structured lead records.

## Workflow Architecture

1. **Webhook Form:** Receives incoming property enquiries.
2. **AI Information Extraction:** Extracts relevant information using an AI model and structured output.
3. **Lead Classification:** Identifies lead intent and urgency.
4. **Google Sheets:** Stores and updates lead information.
5. **WhatsApp Notification:** Sends a notification to the real estate team.

## Information Extracted

- Lead intent: Buyer, Seller, Tenant, Landlord, or Unknown.
- Urgency: High, Medium, Low, or Unknown.
- Property type.
- Preferred location.
- Budget.
- Timeline.

## Technologies Used

- n8n — Workflow automation.
- AI model — Information extraction and classification.
- Google Sheets — Lead storage and management.
- WhatsApp Business Cloud API — Team notifications.
- Webhook — Form submission trigger.

## Business Benefits

- Reduces manual lead processing.
- Improves lead organization.
- Helps teams identify urgent enquiries.
- Provides faster internal notifications.
- Creates a more structured lead management process.

## Project Status

Working demonstration. Tested with sample property enquiries.

## Future Improvements

- Automated lead follow-up.
- High-priority lead routing.
- Error handling and monitoring.
- CRM integration.
- Lead performance reporting.

## Security Notice

This repository documents the project. API credentials, access tokens, private client information, and sensitive workflow data must never be published here.
