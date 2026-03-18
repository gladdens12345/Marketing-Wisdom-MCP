# 🧠 Marketing Wisdom MCP

> **A free MCP server that gives any AI assistant instant access to a vector database of AI-processed insights from 1,000+ podcast episodes.**

Search business ideas, growth tactics, revenue models, and founder stories from two of the best business podcasts on YouTube — right inside your AI tool of choice.

| 🎙️ Show | 📊 Episodes | 🎯 Focus |
|---------|------------|---------|
| **My First Million** | 911 | Business ideas, trends, growth tactics, deal structures |
| **Starter Story** | 129 | Founder journeys, revenue milestones, business models |

Every episode has been broken down into structured insight categories and embedded into a vector database. This isn't keyword matching — it understands what you're actually looking for.

---

## ⚡ Connect

MCP server works with **any compliant AI client** — you connect once and it works everywhere.

### Claude.ai

Add this URL as an integration:

```
https://marketingwisdommcp.com/api/mcp
```

**Settings → Integrations → Add MCP → paste the URL → sign in with Google or GitHub**

That's it. No API keys, no setup, no cost. 🎉

> Requires a paid Claude plan (Pro, Team, or Enterprise)

### Claude Code

```bash
claude mcp add --transport http marketing-wisdom https://marketingwisdommcp.com/api/mcp
```

### Cursor, Windsurf, VS Code, Claude Desktop & More

Add this to your MCP config file:

```json
{
  "mcpServers": {
    "marketing-wisdom": {
      "command": "npx",
      "args": ["-y", "mcp-remote", "https://marketingwisdommcp.com/api/mcp"]
    }
  }
}
```

> Uses [`mcp-remote`](https://www.npmjs.com/package/mcp-remote) to handle OAuth authentication locally.

### ChatGPT

Connect via **Settings → Connectors → Add MCP** and paste the URL.

---

## 🔌 Compatible Platforms

| Category | Platforms |
|----------|----------|
| 💬 **AI Chat** | Claude.ai, Claude Desktop, ChatGPT, Google Gemini CLI |
| 💻 **AI Coding** | Cursor, Windsurf, VS Code (Copilot), Cline, Zed, Replit, JetBrains |
| 🏢 **Enterprise** | Microsoft Copilot Studio, Amazon Bedrock, Azure OpenAI |
| 🔧 **CLI & Dev** | Claude Code, Goose, any app using the MCP TypeScript or Python SDK |

---

## 🔧 Tools

Once connected, your AI gains 4 tools:

| Tool | What It Does |
|------|-------------|
| 🔍 `search_insights` | Search the full knowledge base by topic — ask about any business concept and get structured insights with episode sources |
| 📖 `get_episode` | Get the complete breakdown for a specific episode by title |
| 📋 `list_episodes` | Browse all available episodes by date |
| 📊 `get_stats` | Database statistics and category breakdowns |

---

## 📦 What's Inside Each Episode

Every episode was processed into 8 structured categories tailored to each show's format.

### 🎙️ My First Million — 8 Categories

| # | Category | What's Extracted |
|---|----------|-----------------|
| 1 | 💡 **Business Ideas & Opportunities** | Specific ideas discussed, target customer, market size, validation signals |
| 2 | 📈 **Trends & Emerging Markets** | Macro trends, industries gaining momentum, timing signals |
| 3 | 🚀 **Growth & Marketing Tactics** | SEO, cold outreach, partnerships, what's working now, overrated vs underrated |
| 4 | 💰 **Revenue Models & Monetization** | How businesses make money, pricing strategies, revenue numbers, creative angles |
| 5 | 🤝 **Acquisition & Deal Structures** | Acquisition targets, deal terms, multiples, roll-up strategies |
| 6 | 📣 **Content & Audience Building** | Newsletter/podcast/YouTube growth, audience monetization, platform tactics |
| 7 | 🧩 **Frameworks & Mental Models** | Repeating frameworks, decision heuristics, rules of thumb |
| 8 | 👤 **Key People & Companies Referenced** | Name-drops, case studies, books/resources, specific stats cited |

### 🎙️ Starter Story — 8 Categories

| # | Category | What's Extracted |
|---|----------|-----------------|
| 1 | 📣 **Distribution / Marketing** | Primary channels, first customers, paid vs organic, what worked |
| 2 | 💼 **Business Model** | How they make money, pricing structure, revenue streams, deal size |
| 3 | 🌱 **Origin Story / Unfair Advantage** | What gave them their edge, how they found the idea, what they did before |
| 4 | ⚙️ **Operations & Tools (Tech Stack)** | Software used, automation, team size, delegation |
| 5 | 📈 **Revenue Milestones & Timeline** | When they hit $1K/$10K/$100K months, how long it took, inflection points |
| 6 | 🎁 **Offer / Product Design** | What they sell, packaging, differentiation, how they niched down |
| 7 | 🧠 **Mindset & Key Lessons** | Biggest mistakes, what they'd do differently, repeated advice |
| 8 | 🏖️ **Lifestyle Design** | Hours worked, daily structure, location, overhead, profit margins |

---

## 💬 Example Queries

Try asking your AI things like:

> 🔹 *"What are the best cold email strategies for getting first customers?"*
>
> 🔹 *"How do one-person businesses scale past $500K?"*
>
> 🔹 *"What are the most common frameworks for evaluating business ideas?"*
>
> 🔹 *"How are people monetizing newsletters right now?"*
>
> 🔹 *"What growth tactics are working for SaaS companies?"*
>
> 🔹 *"What does a typical day look like for a solopreneur making $50K/month?"*

---

## 🛠️ Technical Details

| | |
|---|---|
| 🗄️ **Database** | Vector database with semantic embeddings |
| 📊 **Scale** | 1,000+ episodes → 6,700+ insight chunks |
| 📅 **Date Range** | 2015 – 2026 (over a decade of content) |
| 🌐 **Hosting** | Cloudflare Workers — fast globally, always on |
| 🔐 **Auth** | OAuth via Google or GitHub |
| 💸 **Price** | Free, no rate limits |

---

## ❓ Troubleshooting

- **Claude.ai** — Add it via Settings → Integrations (requires Pro, Team, or Enterprise plan)
- **Cursor / Windsurf / VS Code** — Make sure you have Node.js installed (needed for `npx mcp-remote`)
- **Auth issues** — Try disconnecting and reconnecting the integration
- **Still stuck?** — [Open an issue](https://github.com/gladdens12345/Marketing-Wisdom-MCP/issues)

---

<p align="center">
  Built with ❤️ by <a href="https://github.com/gladdens12345">@gladdens12345</a>
</p>
