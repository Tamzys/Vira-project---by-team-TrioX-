# VIRA – Offline Concierge AI Agent

**VIRA** is a lightweight, offline multi-agent assistant built entirely in a Kaggle/Jupyter Notebook. It behaves like a personal concierge — remembering user details, answering questions, handling preferences, doing calculations, and responding naturally — all without using *any* external APIs or internet-based models.

The goal behind VIRA is simple:  
**Show how far a transparent, rule-based agent system can go when each agent has a clear responsibility.**

### What VIRA Can Do
- **Remember your preferences** (name, likes, hobbies, etc.)  
- **Recall information** when you ask questions like “What do I like?”  
- **Perform math calculations** even inside normal sentences  
- **Respond naturally** to greetings and general chat  
- **Render clean chat bubbles** with timestamps for a modern UI  
- **Run 100% offline** — no external tools, no API keys, no model calls

### How It Works
VIRA is powered by a small, modular agent architecture:
- **Router Agent** – Decides what the user wants  
- **Memory Agent** – Stores and recalls user-specific information  
- **Responder Agent** – Handles conversation and fallback replies  
- **Calculator Agent** – Extracts and evaluates arithmetic expressions  
- **UI Layer** – Displays messages in a neat bubble-style interface  

Together, they create a simple but capable assistant that feels personal and interactive without relying on cloud-based AI.

### Why This Project?
VIRA was created for the Google AI Intensive (Kaggle) competition to demonstrate a practical, easy-to-understand, multi-agent system. It isn’t perfect — and it doesn’t try to be. Instead, it focuses on clarity, explainability, and offline functionality.

### Team
- **Tanmay** — Lead developer  
- **Atharva** — Design & code support  
- **Nishant** — Research & testing
