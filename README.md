# 🤖 Gemini AI Telegram Publisher

**Gemini AI Telegram Publisher** is an automated workflow built using **Make.com** that generates and posts short Arabic messages about **Artificial Intelligence** directly to a **Telegram** channel — all without any manual work.

---

## 🚀 Project Overview

The goal of this project is to automate the process of creating and sharing AI-related Arabic content every day.  
Each post includes:
- 🧠 A new concept or idea in Artificial Intelligence  
- 💡 Practical tips or recent news  
- ✨ A short, engaging, and well-formatted writing style for Telegram  

All generated posts are automatically sent to the Telegram channel:
> `@AI_News_Alaasar`

---

## ⚙️ Workflow Components

This workflow consists of **two main modules**:

### 1️⃣ Gemini AI (Text Generation)
- Uses the **Gemini 2.5 Pro** model to generate a short Arabic Telegram post.  
- A carefully designed prompt ensures the output includes:
  - A catchy one-line title  
  - 3–6 clear bullet points  
  - No links, and between 120–180 words.  
- The output is a clean, ready-to-publish text.

### 2️⃣ Telegram (Auto Publishing)
- Uses the **Telegram Bot API** to send the generated post to a specified channel.  
- Secure connections are handled through your **Make.com** account.

---

## 🧩 How to Use

1. Create a free account on [Make.com](https://www.make.com).  
2. Create a new **Scenario**.  
3. Import the provided JSON file from this repository.  
4. Connect your own integrations:
   - 🔑 **Gemini AI connection**
   - 🤖 **Telegram Bot connection**
5. Set up a schedule trigger (e.g., daily at 10:00 AM).  
6. Save and activate the scenario ✅

---

## 🔒 Security

- This file contains **no API keys or access tokens**.  
- All connections are securely stored inside Make.com.  
- You may replace internal connection IDs with placeholders before sharing publicly.

---

## 🌟 Possible Improvements

- Generate and attach an AI-generated image to each post.  
- Add post categories (e.g., tips, news, definitions).  
- Support additional languages beyond Arabic.  
- Create a small dashboard to manually trigger or customize posts.

---

## 📄 License
Released under the **MIT License** — feel free to use, modify, and distribute it with proper credit.

---

## 👨‍💻 Author

**Muhammad Al-Aasar**  
🎓 B.Sc. in Computer Science, Tanta University  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/muhammad-al-aasar-455b78329)  
📞 +20 1015088811

---
