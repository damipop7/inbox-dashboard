# 📬 Dami's Inbox Dashboard

A live, AI-organized Gmail inbox dashboard hosted on GitHub Pages. Built with Claude AI — automatically reads, categorizes, and summarizes emails into a clean visual interface.

![Dashboard Preview](https://img.shields.io/badge/status-live-brightgreen) ![Built with Claude](https://img.shields.io/badge/built%20with-Claude%20AI-7c6ef7)

## 🔗 Live Dashboard

👉 **[View Dashboard](https://YOUR-USERNAME.github.io/inbox-dashboard)**

> Replace `YOUR-USERNAME` with your GitHub username after deploying.

---

## ✨ Features

- **Inbox digest** — all recent emails summarized at a glance
- **Priority alerts** — surfaces emails that need your attention or reply
- **Smart labels** — emails auto-sorted into:
  - 🟢 Job Alerts
  - 🟣 Newsletters
  - 🟠 Events
  - 🔵 Work / Action
- **Visual stats** — donut chart breakdown + top senders bar chart
- **Dark mode** — sleek dark UI with animated accents

---

## 🚀 How to Deploy (GitHub Pages)

1. **Create a new repo** on GitHub — name it `inbox-dashboard`, set to **Public**
2. **Upload** `index.html` and `README.md` to the repo root
3. Go to **Settings → Pages**
4. Under *Branch*, select `main` and `/ (root)` → click **Save**
5. Your dashboard will be live at:
   ```
   https://YOUR-USERNAME.github.io/inbox-dashboard
   ```
   *(Takes ~60 seconds to go live)*

---

## 🔄 Keeping It Updated

The dashboard is a static snapshot. To refresh it with your latest emails:

1. Open Claude at [claude.ai](https://claude.ai)
2. Say **"show my inbox"** — Claude will read your live Gmail
3. Ask Claude to **"regenerate the dashboard"** with the latest data
4. Re-upload the new `index.html` to this repo

> 💡 Tip: You can also ask Claude to draft replies, create new labels, or filter specific senders at any time.

---

## 🛠️ Tech Stack

| Layer | Tool |
|---|---|
| AI | Claude Sonnet (Anthropic) |
| Email | Gmail MCP connector |
| Frontend | HTML + CSS + Vanilla JS |
| Hosting | GitHub Pages |
| Charts | Canvas API (no dependencies) |
| Fonts | Syne + DM Mono (Google Fonts) |

---

## 📁 File Structure

```
inbox-dashboard/
├── index.html    # Main dashboard (all-in-one, no build step)
└── README.md     # This file
```

---

*Auto-organized by Claude AI · damipop7@gmail.com*
