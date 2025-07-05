# 💸 AI Monetization Automation System (ZCAS v2)

> **Zero-Cost Automation Stack powered by DeepSeek, n8n, and Canva**

This open-source system is designed to fully automate content creation, publishing, and monetization using AI and free-tier tools.

## 🧠 System Highlights

- 💬 AI-Powered Script Generation with DeepSeek Chat v3
- 🔁 Automated Workflows with n8n (via Docker or Railway)
- 🎨 Dynamic Visuals with Canva API
- 📅 Scheduling and Publishing via YouTube, Twitter/X, Telegram
- 📊 Monetization integration with Gumroad, Whop, Notion, and Beehiiv

## ⚙️ Tech Stack

| Tool          | Purpose                       |
|---------------|-------------------------------|
| DeepSeek Chat | Content generation (LLM)      |
| n8n           | Workflow automation engine     |
| Canva API     | Auto-thumbnail generation      |
| Google Sheets | Content tracker (DB layer)     |
| GitHub Pages  | Landing page / bio-link host   |
| Docker        | Local environment container    |

## 📂 Folder Structure

zcash-deepseek-automation/
├── n8n-flows/ # Workflow templates
├── config/prompt-templates/ # AI prompt packs
├── docker-compose.yml # Quick-start automation stack
├── README.md