# 🧠 AI Content Automation with n8n + Gemini + Telegram

This project is an **AI-powered content automation workflow** built using **n8n**, **Google Gemini AI**, and a **Telegram Bot**.

It allows users to:

- Enter any topic via Telegram  
- Automatically analyze real-time data (Twitter/X + News)  
- Detect top genres/themes  
- Choose between **Blog Post** or **Social Media Post**  
- Instantly receive AI-generated content on Telegram  

---

## 🚀 Features

- ✅ Telegram-based interaction  
- ✅ Real-time topic analysis (Twitter/X + News)  
- ✅ Genre detection using Gemini AI  
- ✅ User-driven content format selection  
- ✅ SEO-friendly blog generation  
- ✅ Social media post generation  
- ✅ Automatic message formatting & Telegram delivery  
- ✅ Fully automated, no manual steps once configured  

---

## 🔄 Workflow Overview

1. User sends a topic to the Telegram bot  
2. Workflow fetches:
   - Twitter/X discussions  
   - Latest news articles  
3. Gemini AI analyzes the content and extracts **Top 3 genres/themes**  
4. User selects a genre via Telegram inline buttons  
5. User chooses the content type:
   - 📰 **Blog Post**  
   - 📱 **Social Media Post**  
6. Gemini AI generates the requested content  
7. Final content is sent back to the user on Telegram  

---

## 🖼️ Screenshots

### 1️⃣ Workflow Diagram

<img width="1913" height="878" alt="n8n Workflow Diagram" src="https://github.com/user-attachments/assets/6b083954-78af-4bed-b0a9-d3a76b56c588" />

---

### 2️⃣ Social Media Post Generation

![Social Media Post Output](https://github.com/user-attachments/assets/a3b627e8-d197-4fe3-880a-1162f5a95eb1)

---

### 3️⃣ Blog Post Generation

![Blog Post Output](https://github.com/user-attachments/assets/c89c8b17-5a55-461f-80bc-043febed42a6)

---

## 🛠️ Tech Stack

- **n8n** – Workflow automation  
- **Google Gemini AI** – Content understanding & generation  
- **Telegram Bot API** – User interaction  
- **Twitter / X (via Nitter RSS)** – Trend analysis  
- **News API** – Real-world context ingestion  

---

## 📂 Project Structure

```bash
.
├── workflow/
│   └── Twitter_to_post.json
├── README.md
```


## 🚨 Security & Privacy

* ✅ All API keys removed from repository
* ✅ Telegram tokens are NOT committed
* ✅ Safe, sanitized workflow JSON used
* ✅ Credentials must be added locally in n8n

---

## ⚙️ Setup Instructions (High Level)

1. Import the workflow JSON into **n8n**
2. Add credentials:

   * Telegram Bot
   * Gemini API
   * News API
3. Start the workflow
4. Send a topic to your Telegram bot
5. Select genre & content type
6. Receive AI-generated content 🎉

---

## 💡 Use Cases

* Content creators
* Bloggers & marketers
* Social media managers
* AI automation learners
* Workflow & GenAI experiments

---

## 📜 License

MIT License – Free to use, modify, and share.

---

## 🙌 Acknowledgements

* n8n
* Google Gemini
* Telegram Bot API

---

⭐ If you found this useful, **give the repo a star!**

---
