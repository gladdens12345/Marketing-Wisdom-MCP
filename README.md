# 🧠 Marketing Wisdom MCP

> **A free MCP server that gives Claude instant access to a vector database of AI-processed insights from 1,100+ podcast episodes.**

Search business ideas, growth tactics, revenue models, and founder stories from two of the best business podcasts on YouTube — right inside Claude.

| 🎙️ Show | 📊 Episodes | 🎯 Focus |
|---------|------------|---------|
| **My First Million** | 979 | Business ideas, trends, growth tactics, deal structures |
| **Starter Story** | 130 | Founder journeys, revenue milestones, business models |

Every episode has been broken down into structured insight categories and embedded into a vector database. This isn't keyword matching — it understands what you're actually looking for.

---

## ⚡ Quick Start

Add this URL as an integration in Claude.ai:

```
https://marketingwisdommcp.com/api/mcp
```

**Settings → Integrations → Add MCP → paste the URL → sign in with Google or GitHub**

That's it. No API keys, no setup, no cost. 🎉

---

## 🔧 Tools

Once connected, Claude gains 4 tools:

| Tool | What It Does |
|------|-------------|
| 🔍 `search_insights` | Semantic search across all episodes — ask about any business topic and get relevant insights with sources |
| 📖 `get_episode` | Pull the full structured breakdown for a specific episode by title |
| 📋 `list_episodes` | Browse all available episodes with pagination |
| 📊 `get_stats` | Database statistics and category breakdowns |

---

## 📦 What's Inside Each Episode

Every episode was processed into 8 structured categories tailored to each show's format.

### 🎙️ My First Million

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

### 🎙️ Starter Story

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

Try asking Claude things like:

> 🔹 *"What are the best cold email strategies from My First Million?"*
>
> 🔹 *"Find episodes about one-person businesses making over $500K"*
>
> 🔹 *"What frameworks does Sam Parr use to evaluate business ideas?"*
>
> 🔹 *"Show me Starter Story episodes about SaaS businesses"*
>
> 🔹 *"What growth tactics are working right now according to MFM?"*
>
> 🔹 *"Find insights about newsletter monetization"*

---

## 🛠️ Technical Details

| | |
|---|---|
| 🗄️ **Database** | Vector database with semantic embeddings |
| 📊 **Scale** | 1,100+ episodes → 6,700+ insight chunks |
| 🌐 **Hosting** | Cloudflare Workers — fast globally, always on |
| 🔐 **Auth** | OAuth via Google or GitHub |
| 💸 **Price** | Free, no rate limits |

---

## ❓ Troubleshooting

- Make sure you're adding it in **Claude.ai → Settings → Integrations** (not Claude Code or the API)
- If auth fails, try disconnecting and reconnecting the integration
- Works with Claude Pro, Team, and Enterprise plans

---

<p align="center">
  Built with ❤️ by <a href="https://github.com/gladdens12345">@gladdens12345</a>
</p>
