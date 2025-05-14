# 🌤️ Weather Report - n8n Workflow

This is an automated [n8n](https://n8n.io) workflow that fetches weather data from the Open-Meteo API, extracts the high and low temperatures for the day, and sends a summary email using Gmail.

---

## 🖼️ Workflow Preview

![Workflow Screenshot](https://github.com/Harshitha547/weather_report/blob/main/Screenshot%202025-05-14%20143332.png)

---

## 🧩 Workflow Summary

### 🔧 Nodes Used

- **Manual Trigger / Schedule Trigger** – Starts manually or runs every day at 6 AM
- **HTTP Request** – Calls Open-Meteo weather API
- **Code Node** – Processes hourly temperatures to find the high and low
- **Gmail Node** – Sends the daily summary via email

---

## 📨 Email Output Format

Example message sent:

