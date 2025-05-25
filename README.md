# 🤖 AI Chat with Wikipedia using n8n


This project demonstrates how to build a powerful AI chatbot workflow using [n8n](https://n8n.io/) with OpenAI, Wikipedia integration, and memory support.

---

## 🧠 What It Does

> Ask questions to an AI agent and get rich answers powered by both OpenAI and Wikipedia. This chatbot uses memory to carry context and provide meaningful replies.

---

## 🛠️ Workflow Overview

### 🧩 Nodes Used:
- **Chat Trigger**: Starts the workflow when a chat message is received.
- **AI Agent**: The core node that connects with OpenAI and tools.
- **OpenAI Chat Model**: Provides the language generation capability (GPT-4o mini).
- **Wikipedia Tool**: Allows factual retrieval from Wikipedia.
- **Memory**: Remembers previous conversation context.

---

## 🔍 How It Works

1. **Start in the n8n workspace**.
2. Click on the **Templates** on the left sidebar to explore 1500+ workflows.
3. Search for AI templates or import this custom one.
4. Create a new **Workflow**.
5. Drag the following:
   - **Chat Trigger** → Initiates on message.
   - **AI Agent** → Connects to OpenAI + tools + memory.
   - Select model: **GPT-4o mini**
   - Add tool: **Wikipedia**
   - Add memory: **Simple buffer (last 10 messages)**

---

## 🧪 Example Usage

```plaintext
User: What is the capital of France?
AI: Paris
![Uploading image.png…]()


User: Tell me its history.
AI: [AI uses Wikipedia to explain history of Paris]
# ai-chat-wikipedia-n8n
An AI-powered chatbot using n8n, OpenAI, and Wikipedia tools.
