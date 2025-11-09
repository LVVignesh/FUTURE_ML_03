# 🤖 FUTURE_ML_Task3: Customer Support Chatbot (Dialogflow)

## 🎯 Project Overview

This repository contains the completed solution for **Task 3 of the Machine Learning Internship**, which involved building a **smart customer support chatbot** using **Conversational AI principles**.

The chatbot is designed to handle common customer support queries, manage conversational flow, and provide robust escalation and smart fallback mechanisms.

### 🧠 Key Highlights
- **Tool Used:** Google Dialogflow ES  
- **Skills Applied:** Conversational Design, Intent/Entity Recognition, Required Parameter Prompts, and Chatbot Deployment.

---

## ✅ Live Deployment

The fully functional chatbot is deployed and accessible via the **Dialogflow Web Demo** link below:

### 🔗 **[Customer Support Bot Live Demo](https://bot.dialogflow.com/bc9473ba-28a8-4bb4-a0a6-ceef7608046c)**

You can integrate the chatbot into any webpage using this HTML snippet:

```html
<script src="https://www.gstatic.com/dialogflow-console/fast/messenger/bootstrap.js?v=1"></script>
<df-messenger
  intent="WELCOME"
  chat-title="Customer-Support-Bot-ML-"
  agent-id="bc9473ba-28a8-4bb4-a0a6-ceef7608046c"
  language-code="en"
></df-messenger>

⚙️ Deliverables & Conversational Design

The Dialogflow agent includes all required components — dedicated support flows, FAQs, and smart fallback handling.

🗂️ Intents Overview
Intent Name	Purpose	Key Implementation Details

Track_Order_Status :	Primary Support Flow	Uses a Required Prompt and @sys.number-integer entity to gather the Order ID.
Request_Refund : Secondary Support Flow	Uses @sys.any entity with a Required Prompt to capture the specific refund reason.
FAQ_General	: General Information	Handles multiple static responses for business-related FAQs.
Speak_To_Agent :	Escalation Path	Provides a simple fulfillment response for human agent transfer.
Default Fallback Intent :	Smart Fallback Handling	Customized to guide users toward specific services when an intent is not matched.

🖼️ Visual Proof (Screenshots)

Screenshots included in this repository serve as evidence of successful completion and functionality:

intent list overview Screenshot (60).png → Proof of all custom intents created (Intents List Overview)

order tarcking Screenshot (62).png → Proof of Required Parameter Prompt functionality for order tracking

refund order image_e52a48.png → Proof of @sys.any entity and Required Parameter configuration for refund flow

💾 Dialogflow Agent Export

The complete configuration of the Dialogflow agent is included for review and redeployment:

File: Customer-Support-Bot-ML-.zip
