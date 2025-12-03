
# 🚀 AI-Powered News to Blog & Post Automation using n8n

An end-to-end **AI-driven automation workflow** built with **n8n** that:
- Takes user input from **Telegram**
- Fetches real-time news from multiple sources
- Extracts top keywords using AI
- Allows users to choose **Blog or Post mode**
- Generates AI-written content
- Sends the final output back to Telegram automatically

This project demonstrates how **AI + APIs + Workflow Automation** can be combined to build powerful real-world systems.

## 🔥 Features

- ✅ Telegram Bot Integration  
- ✅ Real-time News Scraping (NewsData & GNews APIs)  
- ✅ Keyword Extraction Automation  
- ✅ Blog or Post Mode Selection  
- ✅ AI Content Generation  
- ✅ Automatic Telegram Response Delivery  
- ✅ Error Handling & Fallback Logic  
- ✅ Fully No-Code / Low-Code Automation  

---

## 🧠 Workflow Overview

1. User sends a keyword to the Telegram bot  
2. Workflow fetches real-time news  
3. Top keywords are extracted  
4. User selects **Blog or Post**  
5. AI generates content dynamically  
6. Final content is formatted  
7. Output is sent back via Telegram  

---

## 🖼️ Screenshots


  ### Workflow Overview
  <img width="1919" height="878" alt="Screenshot 2025-12-03 010328" src="https://github.com/user-attachments/assets/3a9cfab1-53d4-4b50-9d7d-a9f682df17c8" />

  ### Telegram Bot Output For Post
  <img width="542" height="1310" alt="image" src="https://github.com/user-attachments/assets/403c868d-f924-40a5-80be-ffbab120684d" />

  ### Telegram Bot Output For Blog
  <img width="208" height="1040" alt="image" src="https://github.com/user-attachments/assets/3283774c-d30d-4cce-9a0e-161d38a47ed2" />

---

## ⚙️ Tech Stack

* **n8n** – Workflow Automation
* **Telegram Bot API** – User Interaction
* **NewsData API & GNews API** – News Scraping
* **AI API (Gemini / OpenAI)** – Content Generation
* **JavaScript** – Data Processing in n8n Code Nodes



## 📂 Project Structure

```
n8n-ai-news-automation/
│
├── workflow.json
├── README.md
└── screenshots/
```

---

## 🛠️ Installation & Setup

### 1️⃣ Install n8n

```bash
npm install n8n -g
```

or use Docker:

```bash
docker run -it --rm n8nio/n8n
```

---

### 2️⃣ Import Workflow

1. Open n8n dashboard
2. Click **Import Workflow**
3. Upload `workflow.json`

---

### 3️⃣ Setup API Keys

Add the following credentials in n8n:

* Telegram Bot Token
* NewsData API Key
* GNews API Key
* AI API Key (Gemini / OpenAI)

---

### 4️⃣ Run the Workflow

* Start the Telegram trigger
* Message the bot:

```
Elon Musk
```

* Select:

```
blog
```

or

```
post
```

✅ The AI-generated content will be delivered automatically.

---

## 📊 Example Output

```
✅ Analysis Complete!
🔍 Search Term: Elon Musk
📄 Articles Found: 10
🏆 Top Keywords: Tesla, AI, SpaceX

📝 Generated Blog Sent to Telegram Successfully
```

---

## ❗ Common Issues & Fixes

| Issue            | Cause                   | Solution                                  |
| ---------------- | ----------------------- | ----------------------------------------- |
| Message too long | Telegram limit exceeded | Truncate message before sending           |
| Mode always blog | IF node misconfigured   | Use exact match `=` instead of `contains` |
| API 400 error    | Invalid query           | Sanitize search input                     |

---

## 🚀 Use Cases

* AI News Aggregation Bots
* Automated Content Marketing
* Social Media Automation
* Research Assistants
* Digital Marketing Tools

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to fork this repo and submit a pull request.

---

## 👨‍💻 Author

**Mithun S**

* 🔗 LinkedIn: [mithun-s-732939280](https://www.linkedin.com/in/mithun-s-732939280)
* 💻 GitHub: [mithun-27](https://github.com/mithun-27)

---

## ⭐ Support

If this project helped you, please ⭐ **star this repository** — it really motivates me to build more automation systems!


---
