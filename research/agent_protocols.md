# 🤖 Agent Communication Protocols

## Overview
This document defines how Project Chimera agents communicate with:
1. Other agents (on MoltBook)
2. External services (via APIs)
3. Internal tools (via MCP)
4. Human supervisors

## 1. MCP (Model Context Protocol)

### Purpose: Internal Tool Communication
```text
Chimera Agent → MCP → Factory Tools
↓ ↓
"Search web" Web Search Tool
"Save data" Database Tool
"Post content" Social Media Tool
```

