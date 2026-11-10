# ⚡ Slash Commands & MCP Cheat Sheet

> **Instant Reference for AI Coding Agents (Cursor, Claude, Windsurf, Antigravity)**

---

## 📋 The Modern AI Superpower Commands

| Slash Command | Category | When to Use | Output Artifact |
| :--- | :--- | :--- | :--- |
| **`/grill-with-docs`** | Discovery | Starting any new feature or refactor | Markdown QA checklist & glossary |
| **`/to-spec`** | Design | After grilling answers are complete | Formal technical spec & test cases |
| **`/tdd`** | Testing | Before writing application logic | Failing unit & integration tests |
| **`/implement`** | Coding | Once tests exist and fail | Passing production-ready code diff |
| **`/wayfinder`** | Navigation | Exploring unfamiliar repositories | Architectural component map |

---

## 🛠️ MCP Servers Configuration Reference

### Standard Root Configuration (`.mcp.json`)
```json
{
  "mcpServers": {
    "context7": {
      "command": "npx",
      "args": ["-y", "@upstash/context7-mcp@latest"]
    },
    "playwright": {
      "command": "npx",
      "args": ["-y", "@playwright/mcp@latest"]
    }
  }
}
```

### Cursor IDE Configuration (`.cursor/mcp.json` or Global)
Place in project root under `.cursor/mcp.json` or in `~/.cursor/mcp.json`.

### Claude Desktop Configuration
File locations:
- **macOS**: `~/Library/Application Support/Claude/claude_desktop_config.json`
- **Windows**: `%APPDATA%\Claude\claude_desktop_config.json`
- **Linux**: `~/.config/Claude/claude_desktop_config.json`

---

## ⚡ Instant Setup CLI Commands

```bash
# 1. Install Matt Pocock's AI skills
npx skills@latest add mattpocock/skills

# 2. Setup Context7 CLI & authentication
npx ctx7 setup

# 3. Test Playwright MCP server
npx -y @playwright/mcp@latest --help
```
