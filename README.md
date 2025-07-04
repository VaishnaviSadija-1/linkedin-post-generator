🔍 LinkedIn Competitor Post Intelligence & AI-Powered Content Generator

This n8n-powered automation workflow helps you analyze top-performing LinkedIn posts from your competitors and generate similar, high-impact content for your own brand using Google Gemini AI. It simplifies competitive research, speeds up content creation, and centralizes everything in Google Sheets.

📸 Workflow Overview

<img width="1440" alt="workflow-screenshot" src="https://github.com/user-attachments/assets/86be0073-14b6-4205-b483-0658a9214f4e" />


⚙️ How It Works

1. Manual Trigger – Start the workflow manually in n8n
2. Read Sheet – Fetch competitor LinkedIn profile URLs from a connected Google Sheet
3. Scrape Posts – Use Apify API to extract post data like likes and engagement
4. Save Raw Data – Store the scraped post data in a Google Sheet for reference
5. Analyze with Gemini (LLM Chain A) – Find the most engaging post using AI
6. Generate New Content (LLM Chain B) – Gemini creates a fresh branded post inspired by competitor data
7. Append Result – Save the generated content to a final Google Sheet for publishing or scheduling

🧠 Why Use This

* Improve Strategy – Learn what’s working for others and adapt it
* Save Time – Skip manual stalking of LinkedIn posts
* Plan Ahead – Generate weekly content ideas automatically

🛠️ Tech Stack

n8n – Workflow automation engine
Google Sheets – Input/output data
Apify API – LinkedIn post scraper
Google Gemini LLM – For analyzing & generating content
Output Parsers – To structure AI responses

🚀 Planned Enhancements

* Auto-post directly to LinkedIn
* Add sentiment or topic categorization
* Email/Slack notifications on new content

🔐 Setup Guide

Make sure you configure the following before running the workflow:

1. Google Sheets API credentials (OAuth2 or Service Account)
2. Apify actor setup for LinkedIn post scraping
3. Gemini API key and model setup in n8n
4. Your n8n instance running with proper environment variables and credentials

👤 Author

Vaishnavi Anil Sadija
Passionate about automation, AI, and building scalable workflows
Email: [sadijavaishnavi1@gmail.com](mailto:sadijavaishnavi1@gmail.com)

License

MIT License – Use, modify, and contribute freely.

