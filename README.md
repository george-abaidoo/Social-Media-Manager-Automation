# 📲 Social Media Manager Automation (n8n)

This project automates **social media content scheduling and performance tracking** using [n8n](https://n8n.io/).  
It’s designed for busy entrepreneurs or content creators who want to keep their feeds active without spending all day online.

---

## 🚀 Workflow Overview

1. **Google Sheets Trigger** – User maintains a sheet with planned posts (date, time, text, media links).  
2. **Scheduler Node** – At the right time, n8n picks up the scheduled post.  
3. **Twitter & LinkedIn Nodes** – Publishes the content automatically to both platforms.  
4. **Analytics Step** – At the end of the day, pulls engagement metrics (likes, shares, comments).  
5. **Email Report** – Sends a daily summary email to the user with post performance.

---

## 📊 Workflow Diagram


*Workflow screenshot to be illustrated after full implementation)*

---

## 🛠️ Setup Instructions

1. Import workflow JSON into n8n.  
2. Set up credentials for:
   - Google Sheets API
   - Twitter API
   - LinkedIn API
   - SMTP/Email account  
3. Fill in a Google Sheet with:
   - Post text  
   - Media link (optional)  
   - Scheduled date/time  
4. Activate the workflow.

---

## ✅ Example Output

- **Automated Post**:  
  > “Top 5 productivity hacks you can try today 💡” posted to Twitter & LinkedIn at 10:00 AM.  

- **Daily Email Report**:
  > Twitter: 42 likes, 7 retweets
  
  > LinkedIn: 65 likes, 15 comments  
