---
layout: page
title: Brightspace MCP Server
description: A Model Context Protocol server enabling Claude Desktop to interact with Purdue Brightspace
img: assets/img/Gemini_Generated_Image_1zr5f31zr5f31zr5.png
importance: 2
category: work
github: https://github.com/pranav-vijayananth/brightspace-mcp-server
related_publications: false
---

### Project Overview

A **Model Context Protocol (MCP)** server that allows Purdue students to access their Brightspace account through Claude Desktop. Ask Claude about your courses, assignments, and grades in natural language!

Since students can't access the official D2L Brightspace API, this project uses **Playwright** for web scraping to extract Brightspace data. It handles Duo Mobile 2FA authentication and integrates seamlessly with Claude Desktop through the Model Context Protocol.

---

### Features

- ✅ **Automated Duo Mobile 2FA** - Handles Purdue's two-factor authentication automatically
- ✅ **Course List Extraction** - Get all your enrolled courses with a simple query
- ✅ **MCP Integration** - Works seamlessly with Claude Desktop for natural language queries
- ✅ **Secure Credentials** - Environment-based credential management
- 🔄 **Assignment Scraping** - In development
- 🔄 **Grade Tracking** - Planned feature

---

### How It Works

**Authentication Flow:**
```
Brightspace Login Page
         ↓
Click "Purdue West Lafayette / Indianapolis"
         ↓
Enter Username & Password
         ↓
Approve Duo Mobile 2FA on Your Phone
         ↓
Authenticated Session Established
         ↓
MCP Server Can Now Access Your Data
```

**MCP Integration:**
```
You: "What courses am I taking?"
         ↓
Claude Desktop → MCP Server → Brightspace Scraper → Your Courses
         ↓
Claude: "You're enrolled in CS 47100, CS 47500, COM 21700..."
```

---

### Technical Stack

- **Python 3.12** - Core runtime
- **Playwright** - Browser automation for web scraping
- **MCP Python SDK** - Model Context Protocol integration
- **Claude Desktop** - AI assistant interface

---

### Example Usage

Once configured, you can ask Claude questions like:
- *"What tools do you have available?"*
- *"What courses am I enrolled in?"*
- *"Show me my upcoming assignments"*

---

### External Links

- [GitHub Repository](https://github.com/pranav-vijayananth/brightspace-mcp-server) - View the source code and documentation
- [Claude Desktop](https://claude.ai/download) - Download Claude Desktop to use with this MCP server

---

### Future Development

This project is actively being developed. Planned features include:
- Full assignment scraping with due dates
- Grade tracking and GPA calculations
- Calendar integration
- Course content access
