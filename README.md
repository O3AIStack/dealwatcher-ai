# Dealwatcher AI

**Dealwatcher AI** is an automated price monitoring agent built with **Pydantic AI**, **Logfire**, and an **MCP server**. It tracks price fluctuations across e-commerce platforms by scraping product pages, extracting key information (title, description, price), storing data in a structured database, and triggering notifications when price changes are detected.

---

## 🚀 Features

- 🔎 Scrapes product title, description, and price from any product page URL  
- 🧠 Built with [Pydantic AI](https://pydantic.dev) for structured agent logic  
- 📊 Logs and traces with [Logfire](https://logfire.io) for observability  
- 🧩 Integrates with an MCP server for orchestration and extensibility  
- 📬 Sends customizable notifications (e.g., email, webhook) on price changes  
- 🗃️ Tracks and persists historical data via a local or remote database

---

## 🛠️ Tech Stack

- **Python 3.10+**
- **Pydantic AI** – For structured agent behavior and validation
- **Logfire** – Real-time observability and structured logging
- **MCP Server** – Agent orchestration and messaging layer
- **BeautifulSoup / Playwright** – Web scraping and automation
- **SQLite / PostgreSQL** – Product data persistence

---

## 📦 Installation

1. **Clone the repo:**

   ```bash
   git clone https://github.com/your-username/dealwatcher-ai.git
   cd dealwatcher-ai

