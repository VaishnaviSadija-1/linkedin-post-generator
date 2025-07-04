# 🔍 LinkedIn Competitor Post Intelligence & AI-Powered Content Generator

This n8n-powered automation workflow helps you analyze top-performing LinkedIn posts from your competitors and generate similar, high-impact content for your own brand using Google Gemini AI. It simplifies competitive research, speeds up content creation, and centralizes everything in Google Sheets.

## 📸 Workflow Overview

<img width="2276" height="854" alt="Image" src="https://github.com/user-attachments/assets/95406cfa-5777-4274-86d3-fdf3ec1a4e7e" />

## ⚙️ How It Works

1. Manual Trigger – Start the workflow manually in n8n  
2. Read Sheet – Fetch competitor LinkedIn profile URLs from a connected Google Sheet  
3. Scrape Posts – Use Apify API to extract post data like likes and engagement  
4. Save Raw Data – Store the scraped post data in a Google Sheet for reference  
5. Analyze with Gemini (LLM Chain A) – Find the most engaging post using AI  
6. Generate New Content (LLM Chain B) – Gemini creates a fresh branded post inspired by competitor data  
7. Append Result – Save the generated content to a final Google Sheet for publishing or scheduling

## 🎥 Demo

[![Loom Demo](https://user-images.githubusercontent.com/102853659/246312121-7dbb8cb7-e2be-4baf-9399-12d3889e97b6.png)](https://www.loom.com/share/99e6ded6bfef46b299471967fa030882?sid=0fe74c85-233d-4ef4-86e8-3525d132474d)



## 🧠 Why Use This

- Improve Strategy – Learn what’s working for others and adapt it  
- Save Time – Skip manual stalking of LinkedIn posts  
- Plan Ahead – Generate weekly content ideas automatically  

## 🛠️ Tech Stack

- n8n – Workflow automation engine  
- Google Sheets – Input/output data  
- Apify API – LinkedIn post scraper  
- Google Gemini LLM – For analyzing & generating content  
- Output Parsers – To structure AI responses  

## 🚀 Planned Enhancements

- [ ] Auto-post directly to LinkedIn  
- [ ] Add sentiment or topic categorization  
- [ ] Email/Slack notifications on new content  

## 🔐 Setup Guide

Make sure you configure the following before running the workflow:

1. Google Sheets API credentials (OAuth2 or Service Account)  
2. Apify actor setup for LinkedIn post scraping  
3. Gemini API key and model setup in n8n  
4. Your n8n instance running with proper environment variables and credentials  

## 👤 Author

**Vaishnavi Anil Sadija**  
Email: sadijavaishnavi1@gmail.com  

## 📄 License

MIT License – Use, modify, and contribute freely.
