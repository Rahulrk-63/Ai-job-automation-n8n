# AI-Powered Job Application Automation using n8n

This project demonstrates an automated system for job searching,
AI-based filtering, auto-application, and tracking using n8n.

## Tech Stack
- n8n
- REST APIs
- Google Sheets
- Notion
- Gemini AI
- Bright Data

## Features
- Automated LinkedIn job scraping
- AI-powered job filtering
- Auto job applications
- Centralized job tracking

# n8n Workflows

This folder represents automation workflows designed using n8n.

## Workflow 1: LinkedIn Job Scraper
- Fetches job listings using LinkedIn search parameters
- Stores job data in Google Sheets

## Workflow 2: Auto Job Application
- Filters jobs with status "Not Applied"
- Automatically applies using job links
- Updates application status

## Workflow 3: AI Job Filtering
- Uses Gemini AI to analyze job relevance
- Pushes best jobs into Notion tracker

These workflows can be exported as JSON files when deployed
in a live n8n environment.
