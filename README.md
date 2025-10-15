<div align="center">
  <a href="https://brightdata.com/ai/mcp-server">
    <img src="https://github.com/user-attachments/assets/c21b3f7b-7ff1-40c3-b3d8-66706913d62f" alt="Bright Data Logo">
  </a>

  <h1>The Web MCP</h1>
  
  <p>
    <strong>🌐 Give your AI real-time web superpowers</strong><br/>
    <i>Seamlessly connect LLMs to the live web without getting blocked</i>
  </p>

  <p>
    <a href="https://www.npmjs.com/package/@brightdata/mcp">
      <img src="https://img.shields.io/npm/v/@brightdata/mcp?style=for-the-badge&color=blue" alt="npm version"/>
    </a>
    <a href="https://www.npmjs.com/package/@brightdata/mcp">
      <img src="https://img.shields.io/npm/dw/@brightdata/mcp?style=for-the-badge&color=green" alt="npm downloads"/>
    </a>
    <a href="https://github.com/brightdata-com/brightdata-mcp/blob/main/LICENSE">
      <img src="https://img.shields.io/badge/license-MIT-purple?style=for-the-badge" alt="License"/>
    </a>
  </p>

  <p>
    <a href="#-quick-start">Quick Start</a> •
    <a href="#-features">Features</a> •
    <a href="#-pricing--modes">Pricing</a> •
    <a href="#-demos">Demos</a> •
    <a href="#-documentation">Docs</a> •
    <a href="#-support">Support</a>
  </p>

  <div>
    <h3>🎉 <strong>Free Tier Available!</strong> 🎉</h3>
    <p><strong>5,000 requests/month FREE</strong> <br/>
    <sub>Perfect for prototyping and everyday AI workflows</sub></p>
  </div>
</div>

---

## 🌟 Overview

**The Web MCP** is your gateway to giving AI assistants true web capabilities. No more outdated responses, no more "I can't access real-time information" - just seamless, reliable web access that actually works.

Built by [Bright Data](https://brightdata.com), the world's #1 web data platform, this MCP server ensures your AI never gets blocked, rate-limited, or served CAPTCHAs.

<div align="center">
  <table>
    <tr>
      <td align="center">✅ <strong>Works with Any LLM</strong><br/><sub>Claude, GPT, Gemini, Llama</sub></td>
      <td align="center">🛡️ <strong>Never Gets Blocked</strong><br/><sub>Enterprise-grade unblocking</sub></td>
      <td align="center">🚀 <strong>5,000 Free Requests</strong><br/><sub>Monthly</sub></td>
      <td align="center">⚡ <strong>Zero Config</strong><br/><sub>Works out of the box</sub></td>
    </tr>
  </table>
</div>

---

## 🎯 Perfect For

- 🔍 **Real-time Research** - Get current prices, news, and live data
- 🛍️ **E-commerce Intelligence** - Monitor products, prices, and availability  
- 📊 **Market Analysis** - Track competitors and industry trends
- 🤖 **AI Agents** - Build agents that can actually browse the web
- 📝 **Content Creation** - Access up-to-date information for writing
- 🎓 **Academic Research** - Gather data from multiple sources efficiently

---

## ⚡ Quick Start


<summary><b>📡 Use our hosted server - No installation needed!</b></summary>

Perfect for users who want zero setup. Just add this URL to your MCP client:

```
https://mcp.brightdata.com/mcp?token=YOUR_API_TOKEN_HERE
```

**Setup in Claude Desktop:**
1. Go to: Settings → Connectors → Add custom connector
2. Name: `Bright Data Web`
3. URL: `https://mcp.brightdata.com/mcp?token=YOUR_API_TOKEN`
4. Click "Add" and you're done! ✨


<summary><b>Run locally on your machine</b></summary>

```json
{
  "mcpServers": {
    "Bright Data": {
      "command": "npx",
      "args": ["@brightdata/mcp"],
      "env": {
        "API_TOKEN": "<your-api-token-here>"
      }
    }
  }
}
```


---

## 🚀 Pricing & Modes

<div align="center">
  <table>
    <tr>
      <th width="33%">⚡ Rapid Mode (Free tier)</th>
      <th width="33%">💎 Pro Mode</th>
    </tr>
    <tr>
      <td align="center">
        <h3>$0/month</h3>
        <p><strong>5,000 requests</strong></p>
        <hr/>
        <p>✅ Web Search<br/>
        ✅ Scraping with Web unlocker<br/>
        ❌ Browser Automation<br/>
        ❌ Web data tools</p>
        <br/>
        <code>Default Mode</code>
      </td>
      <td align="center">
        <h3>Pay-as-you-go</h3>
        <p><strong>Every thing in rapid and 60+ Advanced Tools</strong></p>
        <hr/>
        <p>✅ Browser Control<br/>
        ✅ Web Data APIs<br/>
        <br/>
        <br/>
        <br/>
        <code>PRO_MODE=true</code>
      </td>
    </tr>
  </table>
</div>

> **💡 Note:** Pro mode is **not included** in the free tier and incurs additional charges based on usage.

---

## ✨ Features

### 🔥 Core Capabilities

<table>
  <tr>
    <td>🔍 <b>Smart Web Search</b><br/>Google-quality results optimized for AI</td>
    <td>📄 <b>Clean Markdown</b><br/>AI-ready content extraction</td>
  </tr>
  <tr>
    <td>🌍 <b>Global Access</b><br/>Bypass geo-restrictions automatically</td>
    <td>🛡️ <b>Anti-Bot Protection</b><br/>Never get blocked or rate-limited</td>
  </tr>
  <tr>
    <td>🤖 <b>Browser Automation</b><br/>Control real browsers remotely (Pro)</td>
    <td>⚡ <b>Lightning Fast</b><br/>Optimized for minimal latency</td>
  </tr>
</table>

### 🎯 Example Queries That Just Work

```yaml
✅ "What's Tesla's current stock price?"
✅ "Find the best-rated restaurants in Tokyo right now"
✅ "Get today's weather forecast for New York"
✅ "What movies are releasing this week?"
✅ "What are the trending topics on Twitter today?"
```

---

## 🎬 Demos

> **Note:** These videos show earlier versions. New demos coming soon! 🎥

<details>
<summary><b>View Demo Videos</b></summary>

### Basic Web Search Demo
https://github.com/user-attachments/assets/59f6ebba-801a-49ab-8278-1b2120912e33

### Advanced Scraping Demo
https://github.com/user-attachments/assets/61ab0bee-fdfa-4d50-b0de-5fab96b4b91d

[📺 More tutorials on YouTube →](https://github.com/brightdata-com/brightdata-mcp/blob/main/examples/README.md)

</details>

---

## 🔧 Available Tools

### ⚡ Rapid Mode Tools (Default - Free)

| Tool | Description | Use Case |
|------|-------------|----------|
| 🔍 `search_engine` | Web search with AI-optimized results | Research, fact-checking, current events |
| 📄 `scrape_as_markdown` | Convert any webpage to clean markdown | Content extraction, documentation |

### 💎 Pro Mode Tools (60+ Tools)

<details>
<summary><b>Click to see all Pro tools</b></summary>

| Category | Tools | Description |
|----------|-------|-------------|
| **Browser Control** | `scraping_browser.*` | Full browser automation |
| **Web Data APIs** | `web_data_*` | Structured data extraction |
| **E-commerce** | Product scrapers | Amazon, eBay, Walmart data |
| **Social Media** | Social scrapers | Twitter, LinkedIn, Instagram |
| **Maps & Local** | Location tools | Google Maps, business data |

[📚 View complete tool documentation →](https://github.com/brightdata-com/brightdata-mcp/blob/main/assets/Tools.md)

</details>

---

## 🎮 Try It Now!

### 🧪 Online Playground
Try the Web MCP without any setup:

<div align="center">
  <a href="https://brightdata.com/ai/playground-chat">
    <img src="https://img.shields.io/badge/Try_on-Playground-00C7B7?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZD0iTTEyIDJMMyA3VjE3TDEyIDIyTDIxIDE3VjdMMTIgMloiIHN0cm9rZT0id2hpdGUiIHN0cm9rZS13aWR0aD0iMiIvPgo8L3N2Zz4=" alt="Playground"/>
  </a>
</div>

---

## 🔧 Configuration

### Basic Setup
```json
{
  "mcpServers": {
    "Bright Data": {
      "command": "npx",
      "args": ["@brightdata/mcp"],
      "env": {
        "API_TOKEN": "your-token-here"
      }
    }
  }
}
```

### Advanced Configuration
```json
{
  "mcpServers": {
    "Bright Data": {
      "command": "npx",
      "args": ["@brightdata/mcp"],
      "env": {
        "API_TOKEN": "your-token-here",
        "PRO_MODE": "true",              // Enable all 60+ tools
        "RATE_LIMIT": "100/1h",          // Custom rate limiting
        "WEB_UNLOCKER_ZONE": "custom",   // Custom unlocker zone
        "BROWSER_ZONE": "custom_browser" // Custom browser zone
      }
    }
  }
}
```

---

## 📚 Documentation

<div align="center">
  <table>
    <tr>
      <td align="center">
        <a href="https://docs.brightdata.com/mcp-server/overview">
          <img src="https://img.shields.io/badge/📖-API_Docs-blue?style=for-the-badge" alt="API Docs"/>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/brightdata-com/brightdata-mcp/blob/main/examples">
          <img src="https://img.shields.io/badge/💡-Examples-green?style=for-the-badge" alt="Examples"/>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/brightdata-com/brightdata-mcp/blob/main/CHANGELOG.md">
          <img src="https://img.shields.io/badge/📝-Changelog-orange?style=for-the-badge" alt="Changelog"/>
        </a>
      </td>
      <td align="center">
        <a href="https://brightdata.com/blog/ai/web-scraping-with-mcp">
          <img src="https://img.shields.io/badge/📚-Tutorial-purple?style=for-the-badge" alt="Tutorial"/>
        </a>
      </td>
    </tr>
  </table>
</div>

---

## 🚨 Common Issues & Solutions

<details>
<summary><b>🔧 Troubleshooting Guide</b></summary>

### ❌ "spawn npx ENOENT" Error
**Solution:** Install Node.js or use the full path to node:
```json
"command": "/usr/local/bin/node"  // macOS/Linux
"command": "C:\\Program Files\\nodejs\\node.exe"  // Windows
```

### ⏱️ Timeouts on Complex Sites
**Solution:** Increase timeout in your client settings to 180s

### 🔑 Authentication Issues
**Solution:** Ensure your API token is valid and has proper permissions

### 📡 Remote Server Connection
**Solution:** Check your internet connection and firewall settings

[More troubleshooting →](https://github.com/brightdata-com/brightdata-mcp#troubleshooting)

</details>

---

## 🤝 Contributing

We love contributions! Here's how you can help:

- 🐛 [Report bugs](https://github.com/brightdata-com/brightdata-mcp/issues)
- 💡 [Suggest features](https://github.com/brightdata-com/brightdata-mcp/issues)
- 🔧 [Submit PRs](https://github.com/brightdata-com/brightdata-mcp/pulls)
- ⭐ Star this repo!

Please follow [Bright Data's coding standards](https://brightdata.com/dna/js_code).

---

## 📞 Support

<div align="center">
  <table>
    <tr>
      <td align="center">
        <a href="https://github.com/brightdata-com/brightdata-mcp/issues">
          <strong>🐛 GitHub Issues</strong><br/>
          <sub>Report bugs & features</sub>
        </a>
      </td>
      <td align="center">
        <a href="https://docs.brightdata.com/mcp-server/overview">
          <strong>📚 Documentation</strong><br/>
          <sub>Complete guides</sub>
        </a>
      </td>
      <td align="center">
        <a href="mailto:support@brightdata.com">
          <strong>✉️ Email</strong><br/>
          <sub>support@brightdata.com</sub>
        </a>
      </td>
    </tr>
  </table>
</div>

---

## 📜 License

MIT © [Bright Data Ltd.](https://brightdata.com)

---

<div align="center">
  <p>
    <strong>Built with ❤️ by</strong><br/>
    <a href="https://brightdata.com">
      <img src="https://idsai.net.technion.ac.il/files/2022/01/Logo-600.png" alt="Bright Data" height="30"/>
    </a>
  </p>
  <p>
    <sub>The world's #1 web data platform</sub>
  </p>
  
  <br/>
  
  <p>
    <a href="https://github.com/brightdata-com/brightdata-mcp">⭐ Star us on GitHub</a> • 
    <a href="https://brightdata.com/blog">Read our Blog</a>
  </p>
</div>
