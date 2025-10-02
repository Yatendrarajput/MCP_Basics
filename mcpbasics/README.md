# 🌦 Weather Alerts MCP Server

A simple **MCP (Model Context Protocol)** server built with **Python**, **httpx**, and **FastMCP**.  
This project demonstrates how MCP servers can connect tools and AI agents, starting with a small but useful example: fetching **real-time weather alerts** for US states from the **National Weather Service (NWS) API**.

---

## 🚀 Features
- Get active weather alerts by US state (e.g., CA, NY).
- Fetch data from [NWS API](https://api.weather.gov) with error handling.
- Format alerts into clean, human-readable responses.
- Includes a simple `echo_resource` for testing MCP resource usage.

---

## 🛠️ Tech Stack
- **Python 3.10+** 🐍  
- **httpx** → async API calls  
- **FastMCP** → MCP server framework  

---

## ⚡ Installation & Setup

### Step 1: Create and activate a virtual environment
```bash
python -m venv .venv
# Linux / Mac
source .venv/bin/activate
# Windows
.venv\Scripts\activate
