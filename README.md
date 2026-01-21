# Job Description Decoder

A smart web tool that helps job seekers understand what skills are actually required vs nice-to-have in job postings. Decode corporate jargon, identify ATS keywords, and spot red flags instantly.

## What It Does

Paste any job description and get:
- **Must-Have Skills**: Critical requirements you need to highlight
- **Nice-to-Have Skills**: Preferred qualifications (don't let these stop you from applying!)
- **Resume Keywords**: Important terms for ATS optimization
- **Red Flags & Insights**: Unrealistic expectations, culture hints, and noteworthy details

## Why This Exists

Job descriptions are often confusing. Companies list 20+ requirements when they really only need 5. This tool helps you:
- Focus on what actually matters
- Optimize your resume for ATS systems
- Decide if a job is worth applying to
- Prepare better for interviews

## Tech Stack

- **Frontend**: React + Tailwind CSS
- **AI Analysis**: Google Gemini API (gemini-pro)
- **Deployment**: Can be hosted anywhere (Vercel, Netlify, etc.)

## Getting Started

### Prerequisites
- A free Gemini API key from [Google AI Studio](https://aistudio.google.com/app/apikey)

### Usage
1. Open the app
2. Enter your Gemini API key (stored locally in your browser)
3. Paste any job description
4. Click "Decode JD"
5. Get instant analysis

### API Key Setup
Your API key is stored locally in your browser and never sent anywhere except directly to Google's Gemini API. You can clear it anytime by clearing your browser's local storage.

## Features

✅ Clean, intuitive interface  
✅ Instant AI-powered analysis  
✅ Mobile responsive  
✅ Copy keywords to clipboard  
✅ Reset and analyze multiple JDs  
✅ Error handling and loading states  
✅ No data stored on servers (privacy-first)

## How It Works

1. You paste a job description
2. The app sends it to Gemini API with a specialized prompt
3. Gemini analyzes and returns structured JSON
4. Results are parsed and displayed in an easy-to-scan format

## Privacy & Security

- Your API key is stored only in your browser's localStorage
- Job descriptions are sent directly to Google Gemini API
- No data is stored on any servers
- No tracking or analytics

## Limitations

- Requires a Gemini API key (free tier available)
- Analysis quality depends on how well the job description is written
- Free tier has rate limits (60 requests per minute)

## Future Ideas

- Save and compare multiple JDs
- Export results as PDF
- Salary insights based on requirements
- Company culture analyzer
- Interview question generator based on JD

## Contributing

This is a prototype built in under an hour. Feel free to fork, improve, and make it your own!

## License

MIT License - do whatever you want with it

## Built With

Built as a quick prototype to solve a real problem job seekers face every day. No corporate jargon, just practical help.

---

**Get your free Gemini API key**: https://aistudio.google.com/app/apikey

---
