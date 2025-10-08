🧠 Google Maps Scraper AI Agent (n8n + Gemini)

An AI-powered automation workflow built in n8n that scrapes business data from Google Maps, processes it intelligently using Google Gemini, and exports it to Google Sheets — all without manual intervention.

⚙️ Features

💬 AI Agent Integration: Uses Google Gemini to handle chat-based commands and context.

🗺️ Google Maps Scraper: Automatically extracts business information like name, rating, contact, and address.

📂 Smart Data Flow: Copies, processes, and structures data dynamically.

📊 Google Sheets Export: Appends scraped data to Google Sheets for easy access and visualization.

🔄 Fully Automated Workflow: Triggers on chat messages and runs end-to-end without user input.

🧩 Workflow Overview
When Chat Message Received → AI Agent (Gemini)
→ Scrape Data (Apify Actor)
→ Copy File (Google Drive)
→ Run Actor & Get Dataset
→ Append Row in Google Sheet
→ Edit Fields (Output)

💡 Workflow Highlights:

Trigger: When a chat message is received.

AI Agent: Handles instructions and decides scraping parameters.

Scraping: Powered by Apify Actor for accurate and structured data.

Data Management: Automatically updates Google Sheets in real time.

🧰 Tech Stack
Component	Description
n8n	Workflow automation platform
Google Gemini	AI model for contextual decision-making
Apify	Web scraping platform for Google Maps
Google Sheets	Data storage and collaboration
Google Drive	File handling and copy automation
🚀 How It Works

The workflow listens for chat input (e.g., “Scrape restaurants in Mumbai”).

Google Gemini interprets the request and generates scraping parameters.

The Apify Actor scrapes Google Maps based on those parameters.

Data is copied, cleaned, and appended to a Google Sheet automatically.

The final message returns the sheet link to the user.

🧑‍💻 Setup Instructions

Clone this repository.

Import the workflow JSON into your n8n instance.

Connect the following integrations:

Google Gemini

Apify

Google Drive

Google Sheets

Configure your Google Sheet ID in the Append Sheet node.

Execute the workflow and start chatting!

🔗 Resources

n8n Documentation

Apify Platform

Google Gemini API

Google Sheets API

🧠 Author

Shubh Asawa
✨ Building AI + Automation Workflows
