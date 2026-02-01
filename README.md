# n8n-data-analyst-workflow

## Features
- Reads data from Google Sheets
- Uses Gemini AI to generate insights
- Creates chart instructions (bar, line, pie)
- Sends automated email reports

## How to Use
1. Import `workflow.json` into n8n
2. Add your Google Sheets + Gmail credentials manually
3. Replace placeholders like:
   - SHEET_ID
   - youremail@gmail.com

## Requirements
- n8n (latest)
- Google Sheets OAuth
- Gmail OAuth
- Gemini API access
