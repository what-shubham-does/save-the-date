# A & S · Save the Date · 3 December 2026

A quiz-based Save the Date website for Anmol & Shubham's wedding.

## Features
- Interactive quiz with 3 questions
- Animated reveal of wedding details
- RSVP form with Google Sheets integration
- Mobile-optimized design

## Deployment
Hosted on Netlify. Pushes to `main` auto-deploy.

## RSVP Setup
The RSVP form sends data to a Google Apps Script. To configure:
1. Create a Google Sheet with headers: `Name | Guests | Status | Timestamp`
2. Add the Apps Script (see setup guide)
3. Deploy as a web app
4. Paste the URL into `index.html` at `GOOGLE_SCRIPT_URL`
