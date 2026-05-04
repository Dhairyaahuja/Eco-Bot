# Eco-Bot
Automated Multi-Platform Price Intelligence System
# Eco-Bot: Intelligent RPA Price Monitoring System

##  Project Overview
**Eco-Bot** is an end-to-end Robotic Process Automation (RPA) solution built to demonstrate advanced browser automation, data management, and full-stack integration. Unlike traditional scrapers, Eco-Bot mimics human behavior to monitor e-commerce prices, store historical data, and provide a visual dashboard for price intelligence. 

This project was developed to satisfy requirements for roles involving **RPA tools (UiPath, Power Automate)** by implementing the underlying automation logic using the **Python-Playwright** framework.

##  Tech Stack
*   **RPA Engine:** Playwright (Python-based automation)
*   **Backend:** Flask (Python)
*   **Database:** SQLite (SQLAlchemy ORM)
*   **Frontend:** HTML5, CSS3 (Bootstrap), JavaScript
*   **IDE:** VS Code

##  Key Features
*   **Human-Mimicry Automation:** Uses Playwright to navigate dynamic web pages, handle asynchronous loading, and extract unstructured data.
*   **Data Persistence:** Stores product metadata and price history in a relational database.
*   **Price Intelligence:** Automatically compares real-time scraped data against user-defined thresholds.
*   **Web Dashboard:** A clean UI to manage tracked products and view current status.

##  Project Structure
```text
├── app.py              # Flask Backend & Database Logic[cite: 1]
├── bot.py              # RPA Worker (The Playwright Robot)[cite: 1]
├── templates/
│   └── index.html      # Frontend Dashboard[cite: 1]
├── static/
│   └── style.css       # Custom Styling[cite: 1]
└── eco_bot.db          # SQLite Database (Auto-generated)[cite: 1]
