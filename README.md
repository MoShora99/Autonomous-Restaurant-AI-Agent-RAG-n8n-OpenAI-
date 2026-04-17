# 🤖 Autonomous Restaurant AI Agent

An intelligent AI-powered customer service system that automates restaurant interactions through a Telegram chatbot.
The platform combines **AI Agents, workflow automation, and Retrieval-Augmented Generation (RAG)** to provide instant, context-aware responses and automated order management.

This project demonstrates how conversational AI can transform traditional restaurant customer support into a **scalable, fully automated service system**.

---

# 🚀 Features

* 🤖 **AI Agent for Natural Conversations**
  Understands and responds to customer queries using advanced AI models.

* 📲 **Telegram Chatbot Integration**
  Customers interact with the restaurant directly through Telegram.

* 🧠 **Retrieval-Augmented Generation (RAG)**
  Retrieves restaurant data, FAQs, and menu information to generate accurate responses.

* ⚙️ **Workflow Automation with n8n**
  Automates chatbot logic, service flows, and backend integrations.

* 🌍 **Multilingual Support**
  Handles both **Arabic and English** customer queries.

* 🍽️ **Automated Restaurant Services**

  * Menu inquiries
  * Order placement
  * Order modification
  * Order cancellation

* 🗄️ **Database Order Tracking**

  * Each order stored with unique ID
  * Full interaction history
  * Order lifecycle tracking

* ⚡ **Instant Customer Support**
  Eliminates manual intervention for routine requests.

---

# 🏗️ System Architecture

```
User
  │
  ▼
Telegram Bot
  │
  ▼
n8n Automation Workflow
  │
  ├── AI Agent (OpenAI)
  │        │
  │        ▼
  │   Natural Language Understanding
  │
  ├── RAG System (Google Gemini)
  │        │
  │        ▼
  │   Restaurant Knowledge Base
  │
  ▼
Database
  │
  ▼
Order Processing & Tracking
```

---

# 🧠 AI Architecture

The system is designed using a **modern AI Agent + RAG architecture**:

### AI Agent

Responsible for:

* Intent detection
* Conversation handling
* Task execution

### RAG Pipeline

Enhances responses using:

* Restaurant knowledge base
* Menu information
* Frequently asked questions

### Automation Layer

n8n manages:

* Workflow orchestration
* API communication
* Order processing logic

---

# 🛠️ Tech Stack

### AI & LLM

* OpenAI Models
* Google Gemini

### Automation

* n8n Workflow Automation

### Communication

* Telegram Bot API

### Backend

* Database for order storage
* Interaction logging

### AI Techniques

* AI Agents
* Retrieval-Augmented Generation (RAG)
* Natural Language Understanding
* Multilingual NLP

---

# 📦 Project Structure

```
restaurant-ai-agent
│
├── workflows/
│   ├── n8n-automation.json
│
├── knowledge-base/
│   ├── menu-data
│   ├── faq-data
│
├── bot/
│   ├── telegram-integration
│
├── database/
│   ├── order-schema
│
└── README.md
```

---

# ⚙️ Setup & Installation

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/restaurant-ai-agent.git
```

### 2️⃣ Configure Environment Variables

Create a `.env` file:

```
OPENAI_API_KEY=your_key
GEMINI_API_KEY=your_key
TELEGRAM_BOT_TOKEN=your_token
DATABASE_URL=your_database
```

### 3️⃣ Import n8n Workflow

1. Open **n8n**
2. Import the workflow JSON
3. Configure API credentials

### 4️⃣ Start the Bot

Run the workflow and connect the Telegram bot to begin processing requests.

---

# 📊 Example Use Cases

### Customer asks for the menu

```
User: Show me the menu
Bot: Here is today's menu...
```

### Customer places an order

```
User: I want two chicken burgers
Bot: Your order has been placed successfully.
Order ID: #A1024
```

### Customer modifies an order

```
User: Change my order to one burger
Bot: Your order has been updated.
```

---

# 🎯 Project Goals

* Demonstrate **real-world AI automation**
* Build **AI-powered customer service systems**
* Integrate **LLMs with workflow automation**
* Apply **RAG in production scenarios**

---

# 🔮 Future Improvements

* Voice ordering support
* WhatsApp integration
* Payment gateway integration
* Real-time kitchen dashboard
* AI-powered recommendation system

---

# 🤝 Contributing

Contributions are welcome.
Please open an issue or submit a pull request.

---

# 📄 License

MIT License

---

# ⭐ Show Your Support

If you like this project, consider giving it a ⭐ on GitHub.
