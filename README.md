# 📲 WhatsApp-MCP: Control WhatsApp using AI

![WhatsApp MCP](./2aa5f936-ba2f-4907-af8f-b18a7c9a6a65.png)

---

## 🔍 Overview

**Chat-Bridge** is a secure, local-first solution to bridge your WhatsApp messages with AI tools using a combination of `whatsapp-web.js`, SQLite, and AI agent communication through MCP (Message Control Protocol). The system empowers users to automate, filter, and respond to WhatsApp messages through natural language prompts.

---

## 💡 Features

- 🔐 Local session management via `mcp.json`
- 📬 Read/send messages through programmable tools
- 🧠 Integration with AI agents like Cursor or Claude
- 🗂️ Message logging, search, media handling
- 🧩 Easy to extend for custom automation and workflows

---

## ⚙️ Tech Stack

| Component         | Technology        |
|------------------|-------------------|
| WhatsApp Bridge   | `whatsapp-web.js` |
| Backend Logic     | Node.js (JavaScript) |
| Session Handling  | `mcp.json` |
| AI Agent Support  | MCP-compatible tools (Cursor, Claude, etc.) |

---

## 🚀 Quickstart

### 1. Install

```bash
npm install whatsapp-web.js
