# Jarvis Financial CFO - AI Budget Manager 📈💰

The Jarvis Financial CFO is a sophisticated autonomous agent designed to manage personal liquidity with the precision of a professional accountant. It bridges the gap between natural language interaction and structured SQL data management.



## 🏗️ Core Logic: NL2SQL
The heart of this project is the **Natural Language to SQL** engine. Instead of manual entry, the user interacts with the agent via Telegram. The agent:
1. **Parses** the intent (e.g., "I just spent 15€ on fuel").
2. **Generates** a valid MySQL `INSERT` or `SELECT` query.
3. **Executes** the command on the Jarvis MariaDB instance.
4. **Validates** the results against the 2026 liquidity targets.

## 🎯 Strategic Features
* **Pacing Engine:** Monitors spending habits and calculates the daily allowance required to reach the **€11,000 savings target** by the end of 2026.
* **Database Sovereignty:** All financial records are stored locally on a secured MariaDB instance, ensuring total privacy.
* **Automated Auditing:** Generates real-time balance summaries and categorical spending breakdowns upon request.

## 🛠️ Tech Stack
* **Orchestration:** n8n
* **LLM:** GPT-4o-mini (optimized for structured SQL generation)
* **Database:** MariaDB / MySQL
* **Interface:** Telegram Bot API

---
*This agent demonstrates high-level proficiency in prompt engineering for code generation and database integration.*
