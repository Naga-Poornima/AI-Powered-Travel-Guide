# AI-Powered Travel Guide

## About the Project
The AI-Powered Travel Guide is a web application that generates information about travel destinations and converts it into speech. It helps users explore places through AI-generated descriptions and audio guides.

## Features
- Generate travel information for a selected destination.
- Choose summary or detailed descriptions.
- Listen to generated audio guides.
- Support for multiple languages, including English, Hindi, Tamil, and Telugu.
- Select available voice options.

## Technologies Used
- **Frontend:** HTML, JavaScript
- **Backend:** Python, Flask
- **AI:** Google Gemini API
- **Voice Generation:** Murf API
- **Deployment:** Vercel (frontend) and Railway (backend)

## Live Demo
https://ai-powered-travel-guide-beta.vercel.app/

## Project Structure
```text
TRAVEL_GUIDE_NEW/
├── Backend/
│   ├── app.py
│   └── requirements.txt
└── Frontend/
    ├── index.html
    └── index.js
```

## Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/Naga-Poornima/AI-Powered-Travel-Guide.git
cd AI-Powered-Travel-Guide
```

### 2. Set up the backend
Open a terminal in the project folder and run:

```bash
cd Backend
pip install -r requirements.txt
```

Create a `.env` file inside the `Backend` folder and add your own API keys:

```text
GOOGLE_API_KEY=your_google_api_key
MURF_API_KEY=your_murf_api_key
```

Replace the example values with your own keys. **Never upload your `.env` file or API keys to GitHub.**

Run the backend locally using the command appropriate for your Flask application.

### 3. Open the frontend
Open `Frontend/index.html` in your browser. The frontend is configured to call the deployed backend API, so the deployed backend must be available for audio-guide generation.

## Environment Variables
- `GOOGLE_API_KEY` — Google Gemini API key.
- `MURF_API_KEY` — Murf API key.

## Author
Project developed as an AI-powered travel guide application.
