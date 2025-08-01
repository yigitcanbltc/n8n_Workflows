# 🤖 Telegram AI Customer Service (n8n Workflow)

This workflow enables a **Telegram-based AI-powered customer service assistant** using [n8n](https://n8n.io).  
It accepts both text and voice messages, processes them using AI services, and maintains conversation context in a Supabase database.

## 🌟 Features

### 🧠 AI-Powered Interaction
- Uses **Mistral’s codestral-2411-rc5 model** via LangChain
- Customizable system prompt for company-specific response style
- Maintains short-term conversation memory with sliding window

### 🧾 Message History Management
- Saves messages and metadata to **Supabase**
- Aggregates conversation context for accurate AI replies
- Deletes processed messages after generating a response

### ✅ Multi-Input Support
- Handles text messages directly
- Transcribes voice messages using Hugging Face Whisper
- Sends error responses for unsupported input types

### 📬 Telegram Integration
- Receives messages using Telegram Trigger node
- Sends AI-generated responses in real-time
- Processes voice messages via Telegram → Whisper → JSON → AI chain


## 🧩 Requirements
You can use the workflows by importing the `.json` files into your [n8n](https://n8n.io) instance via the **Import File** option, and configuring the required API connections.

❗🍴 Some workflows may be incomplete — feel free to **fork** this project to add your own flows or improve the existing ones.  
Thanks for your contributions!

