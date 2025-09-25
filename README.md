n8n Email Classifier with Telegram Alerts
This project is an automated email classification workflow built using n8n
.
It automatically classifies incoming emails (e.g., Jobs,Social media, General, offers / Promotion , Payments / Bills  ) and sends Telegram notifications if the email is  Important to the client.

Features

✅ Fetches emails automatically from your email inbox

✅ Classifies emails based on subject/content

✅ Labels emails into categories (Payment's, General, Social media etc.)

✅ Sends Telegram alerts for important emails

✅ Fully automated workflow, runs in the background

✅ Easy to customize classification rules using text classifier

Tech Stack

n8n
 – Workflow automation tool

n8n
 – Workflow automation tool

 Schedule trigger - execute every 5 minutes to trigger get gmail node

Email Node – Fetching incoming emails which are unread

Function/Code Node – Sends email content to Gemini model for classification

Google Gemini Chat Model – AI-based email classification

Telegram Node – Sends alerts for important emails

Configure Credentials

Email Node → Connect your Gmail account using google api credentials 

Google Gemini API → Add your API key in n8n credentials

Telegram Node → Add your Telegram Bot Token & Chat ID
