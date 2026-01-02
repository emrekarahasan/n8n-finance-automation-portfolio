n8n Automation Portfolio

Hi, I'm Emre. I am a Business Administration student specializing in Finance. This repository contains automated workflows I built using *n8n* in order to solve real-world financial and operational problems easily.

---

## Projects

*Smart Debt Collector (Automated Dunning Process)*
**File:** `automatic-debt-collector.json`

An intelligent system that manages customer debts stored in Google Sheets. It calculates the debt in USD using real-time exchange rates and sends personalized email reminders based on the delay duration.

* **Core Features:**
    * **Data Merging:** Combines customer data (Sheets) with live Exchange Rates (Frankfurter API).
    * **Logic Switching:** Routes customers into 3 categories: Polite Reminder (1-7 days), Urgent Warning (7-30 days), Legal Action (>30 days).
    * **Error Handling:** Sends an emergency alert if the workflow fails.
    * **Reporting:** Generates a daily executive summary of processed debts.

*Daily Weather Reporter*
**File:** `daily-weather-reporter.json`

A utility bot that fetches daily weather forecasts via API and delivers a morning briefing via email. Demonstrates basic API integration and data transformation.

---

## 🛠️ Tech Stack
* **Platform:** n8n (Self-hosted / Cloud)
* **Integrations:** Google Sheets, Gmail, Frankfurter Currency API, Weather API.
* **Concepts:** Webhooks, JSON Manipulation, JavaScript (Code Node), Error Triggers.

---

## 👨‍💻 How to Use
1. Download the `.json` file of the workflow you want.
2. Open your n8n dashboard.
3. Click "Import from File" and select the json.
4. Update the credentials (Gmail/Sheets) with your own.
