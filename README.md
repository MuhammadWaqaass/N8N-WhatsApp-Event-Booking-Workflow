# WhatsApp Voice AI Event Booking Bot (n8n)

An **AI-powered WhatsApp Search & Appointment Booking Bot** built using **n8n**, supporting **both voice and text conversations**.
The system automatically understands user intent, searches availability, and books appointments in real time.

<img width="623" height="302" alt="booking" src="https://github.com/user-attachments/assets/80d7f564-b17f-45b0-9075-7533016bbf37" />

## 🚀 Overview

This project demonstrates how to build a **production-ready WhatsApp AI assistant** that can:

* Talk to users via **text and voice**
* Understand natural language queries
* Detect intent automatically
* Search structured data
* Book appointments on Google Calendar
* Store and manage records efficiently

The architecture is **Meta-compliant**, using a **single WhatsApp trigger** to handle all interactions.

---

## ✨ Key Features

* 📱 **WhatsApp AI Bot** (Text + Voice)
* 🧠 **Automatic Intent Detection** using AI
* 🎙️ **Voice Support** with Speech-to-Text
* 📊 **Google Sheets** as a searchable database
* 📅 **Google Calendar** for real-time appointment booking
* 🔁 Fully automated **end-to-end workflow**
* ⚡ Low-latency responses using Groq LLMs
* 🧩 Modular and scalable n8n design

---

## 🧠 AI Capabilities

* Natural language understanding (NLU)
* AI-based **text classification**
* Context-aware responses
* Voice-to-text processing
* Intelligent routing based on user intent

---

## 🛠️ Tech Stack

* **n8n** – Workflow orchestration
* **WhatsApp Cloud API** – Messaging interface
* **LangChain** – AI agent framework
* **Groq** – High-speed LLM inference
* **ElevenLabs** – Speech-to-Text (voice input)
* **Google Sheets** – Doctor / Event database
* **Google Calendar** – Appointment scheduling

---

## 🧩 Workflow Architecture

1. **WhatsApp Cloud API Trigger**

   * Receives incoming text or voice messages
2. **Voice Handling (Optional)**

   * Voice messages converted to text using ElevenLabs
3. **AI Intent Classification**

   * Determines user intent (search, book, reschedule, query, etc.)
4. **Data Lookup**

   * Searches Google Sheets for doctors / events / availability
5. **Booking Logic**

   * Confirms slots and books appointments in Google Calendar
6. **Response Generation**

   * AI-generated confirmation sent back via WhatsApp (text or voice)

---

## 📌 Supported Intents

* Search doctor / service
* Check availability
* Book appointment
* Ask general questions
* Voice-based interaction
* Text-based interaction

---

## ✅ Meta-Compliant Design

* Uses **one WhatsApp trigger**
* No duplicate webhook registrations
* Scalable for production deployment
* Designed to handle high message volume

---

## 📈 Use Cases

* Healthcare appointment booking
* Event scheduling
* Service-based businesses
* Customer support automation
* Voice-enabled AI assistants on WhatsApp

---

## 🔮 Future Enhancements

* Multilingual support
* Appointment rescheduling & cancellation
* Payment gateway integration
* User profile memory
* Analytics dashboard

---

## 🏁 Conclusion

This project showcases how **AI Agents + n8n + WhatsApp** can be combined to build a **real-world, voice-enabled booking system** that is fast, scalable, and production-ready.
