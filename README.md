# 🏠 MCP Client Lead Qualification Chatbot (n8n)

An AI-powered real estate **lead qualification and site visit booking chatbot** built using **n8n**, **Google Gemini**, and **MCP Client**.  
This project automates customer conversations for **Godrej Properties, Hinjawadi (Pune)** and converts interested users into scheduled site visits.

---

## 🚀 Project Overview

This chatbot acts as a virtual sales assistant named **Sarah**.  
Its primary responsibility is to answer property-related queries, qualify potential buyers, and book site visit appointments — all through a structured conversational workflow.

The bot strictly stays on-topic and politely redirects or ends conversations when users go off-topic.

---

## 🧠 Key Features

- AI-powered conversational agent using **Google Gemini**
- Real estate–focused lead qualification logic
- Automated site visit booking flow
- Context retention using **Simple Memory**
- Structured responses via **MCP Client**
- Off-topic handling with graceful redirection
- Fully automated workflow built in **n8n**

---

## 🛠️ Tech Stack

- **n8n** – Workflow automation platform  
- **Google Gemini Chat Model** – AI conversation engine  
- **MCP Client** – Tool-based structured data handling  
- **Simple Memory** – Conversation context storage  

---

## 🧩 Workflow Architecture

```
When Chat Message Received
        ↓
      AI Agent
   ┌──────────────────┐
   │ Google Gemini    │
   │ Simple Memory    │
   │ MCP Client Tool  │
   └──────────────────┘
        ↓
   Lead Qualification & Booking
```

---

## 🏢 Property Information

- **Project Name:** Godrej Properties  
- **Location:** Hinjawadi, Pune (IT Hub)  
- **Configurations:** 2BHK, 3BHK, 4BHK  

### 💰 Pricing
- 2BHK – ₹50 Lakhs onwards  
- 3BHK – ₹60 Lakhs onwards  
- 4BHK – ₹70 Lakhs onwards  

### 🏊 Amenities
- Clubhouse with swimming pool  
- Fully-equipped gym  
- 24/7 security  
- Children’s play area  
- Landscaped gardens  
- Power backup & covered parking  

**Availability:** Limited units remaining

---

## 🗣️ Conversation Rules

- Answers **only property-related questions**
- Always nudges toward **site visit booking**
- Keeps replies concise (2–3 sentences max)
- Redirects off-topic queries politely
- Ends conversation if the user is not interested

---

## 📅 Site Visit Booking Logic

1. User shows interest  
2. Bot offers available time slots  
3. User confirms date & time  
4. Bot collects name and mobile number  
5. Site visit is booked and confirmed  

### ⏰ Available Slots
- Weekdays: 10 AM – 6 PM  
- Weekends: 10 AM – 4 PM  
- Timezone: Asia/Kolkata (+05:30)

---

## 📤 Sample Output

```json
{
  "Name": "Gitesh",
  "Date": "2026-01-14",
  "Time": "11 AM",
  "Interest": "2BHK",
  "Summary": "Interested in 2BHK, site visit confirmed"
}
```

---

## ▶️ How to Run the Project

1. Import the workflow JSON into **n8n**
2. Configure:
   - Google Gemini API credentials
   - MCP Client connection
3. Activate the workflow
4. Open n8n Chat UI and start testing

---

## 🎯 Use Cases

- Real estate lead qualification
- Automated appointment scheduling
- AI sales assistant
- Customer engagement automation
- Pre-filtering CRM leads

---

## 🔮 Future Enhancements

- CRM integration (Zoho, HubSpot)
- WhatsApp & website chatbot deployment
- Lead analytics dashboard
- Multi-project real estate support

---

## 👤 Author

**Gitesh Desale**  
Built using **n8n + AI Automation**
