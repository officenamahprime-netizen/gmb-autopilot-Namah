<div align="center">

<!-- HERO BANNER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00ff88,50:00b4d8,100:6c63ff&height=220&section=header&text=GMB%20Autopilot&fontSize=72&fontColor=ffffff&fontAlignY=38&desc=Full-Stack%20Google%20My%20Business%20Automation%20Engine&descAlignY=58&descSize=20&animation=fadeIn" width="100%"/>

<br/>

<!-- BADGES ROW 1 -->
[![License: MIT](https://img.shields.io/badge/License-MIT-00ff88.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Built With Claude AI](https://img.shields.io/badge/Built%20With-Claude%20AI-6c63ff?style=for-the-badge&logo=anthropic)](https://anthropic.com)
[![Google My Business API](https://img.shields.io/badge/Google%20My%20Business-API%20v4-4285F4?style=for-the-badge&logo=google)](https://developers.google.com/my-business)
[![No Backend](https://img.shields.io/badge/No%20Backend-100%25%20Browser-00b4d8?style=for-the-badge)](https://github.com/konkomaji/gmb-autopilot)

<!-- BADGES ROW 2 -->
[![Stars](https://img.shields.io/github/stars/konkomaji/gmb-autopilot?style=for-the-badge&color=ffd700)](https://github.com/konkomaji/gmb-autopilot/stargazers)
[![Forks](https://img.shields.io/github/forks/konkomaji/gmb-autopilot?style=for-the-badge&color=00ff88)](https://github.com/konkomaji/gmb-autopilot/network)
[![Issues](https://img.shields.io/github/issues/konkomaji/gmb-autopilot?style=for-the-badge&color=ff6b6b)](https://github.com/konkomaji/gmb-autopilot/issues)
[![Made in India](https://img.shields.io/badge/Made%20in-India%20🇮🇳-FF9933?style=for-the-badge)](https://github.com/konkomaji)

<br/>

```
╔═══════════════════════════════════════════════════════════════╗
║  Reply to 1000 reviews · Post to 70+ profiles · Rank #1      ║
║  All from a single HTML file. No server. No subscriptions.   ║
╚═══════════════════════════════════════════════════════════════╝
```

**[🚀 Live Demo](https://konkomaji.github.io/gmb-autopilot)** &nbsp;·&nbsp; **[📖 Documentation](#-getting-started)** &nbsp;·&nbsp; **[🐛 Report Bug](https://github.com/konkomaji/gmb-autopilot/issues)** &nbsp;·&nbsp; **[💡 Request Feature](https://github.com/konkomaji/gmb-autopilot/issues)**

</div>

---

## ⚡ What is GMB Autopilot?

**GMB Autopilot** is a zero-backend, single-file intelligence engine that manages your entire Google My Business agency portfolio — automatically. Built for digital marketing agencies managing 10 to 100+ client profiles, it replaces hours of manual work with a fully automated AI pipeline that runs in your browser.

> *"The tool that agencies charging ₹50,000/month per client wish didn't exist."*

**No server. No database. No SaaS subscription. Just open the HTML file and connect your Google account.**

---

## 🗺️ System Blueprint

```
┌─────────────────────────────────────────────────────────────────────┐
│                        GMB AUTOPILOT v3                             │
│                    Agency Intelligence Engine                        │
└──────────────────────────────┬──────────────────────────────────────┘
                               │
          ┌────────────────────┼────────────────────┐
          │                    │                    │
          ▼                    ▼                    ▼
┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐
│  GOOGLE OAUTH   │  │   CLAUDE AI     │  │  LOCAL STORAGE  │
│  business.manage│  │ Haiku (fast)    │  │  Intelligence   │
│  All GMB APIs   │  │ Sonnet (deep)   │  │  Profile Cache  │
└────────┬────────┘  └────────┬────────┘  └────────┬────────┘
         │                    │                     │
         └────────────────────┼─────────────────────┘
                              │
                              ▼
         ┌────────────────────────────────────────┐
         │         CORE PROCESSING PIPELINE        │
         └────────────────────────────────────────┘
                              │
         ┌────────────────────┼────────────────────┐
         │                    │                    │
         ▼                    ▼                    ▼
┌─────────────────┐  ┌─────────────────┐  ┌─────────────────┐
│  ⚡ REVIEW       │  │  📸 CONTENT     │  │  🚀 PROFILE     │
│    ENGINE        │  │    STUDIO       │  │   OPTIMIZER     │
│                 │  │                 │  │                 │
│ • Fetch all     │  │ • Photo upload  │  │ • Description   │
│   unreplied     │  │ • Video upload  │  │   (SEO 750chr)  │
│ • AI profile    │  │ • Post types:   │  │ • Google Posts  │
│   analysis      │  │   Update/Offer/ │  │   (3 per loc)   │
│ • SEO keyword   │  │   Event/Photo   │  │ • Q&A Seeding   │
│   extraction    │  │ • AI captions   │  │   (5 Q&As)      │
│ • Personalised  │  │   per location  │  │ • Services List │
│   reply gen     │  │ • Bulk post     │  │ • Health Score  │
│ • Auto-post     │  │   to all GMBs   │  │   (0-100%)      │
│   to Google     │  │                 │  │                 │
└────────┬────────┘  └────────┬────────┘  └────────┬────────┘
         │                    │                     │
         └────────────────────┼─────────────────────┘
                              │
                              ▼
         ┌────────────────────────────────────────┐
         │        🧠 INTELLIGENCE LAYER            │
         │                                        │
         │  • Self-learning per-profile memory    │
         │  • Primary SEO keywords (7 per loc)   │
         │  • Local/geo keywords (4 per loc)     │
         │  • Service keywords (5 per loc)       │
         │  • Business tone & personality        │
         │  • USP & concern tracking             │
         │  • Never re-analyses a known profile  │
         └────────────────────┬───────────────────┘
                              │
                              ▼
         ┌────────────────────────────────────────┐
         │        📊 DAILY REPORT ENGINE          │
         │                                        │
         │  • Auto-generates at 8 PM (config)    │
         │  • Per-location performance           │
         │  • Profile health scores              │
         │  • AI-generated agency insights       │
         │  • Export to HTML for clients         │
         └────────────────────────────────────────┘
```

---

## ✨ Features at a Glance

<table>
<tr>
<td width="50%">

### ⚡ Review Engine
- Sequential processing — location by location
- Fetches ALL unreplied reviews automatically
- AI analyses business type, tone, USPs per profile
- Extracts **7+ local SEO ranking keywords** per profile
- Generates hyper-personalised replies referencing specific review details
- Handles negatives with empathy + resolution
- Auto-posts replies directly to Google
- Configurable delay to avoid rate limits

</td>
<td width="50%">

### 📸 Content Studio
- Drag & drop photo/video upload
- 4 post types: Update, Offer, Event, Photo
- AI generates unique captions **per location** using that business's keywords
- Bulk post to all 70+ profiles in one click
- Direct photo byte upload via GMB API
- Location-aware caption personalisation
- Offer/Event scheduling support

</td>
</tr>
<tr>
<td>

### 🚀 Profile Optimizer
- **Business Description** — AI writes SEO-rich 750-char description
- **Google Posts** — 3 posts per location (Update + Offer + Tips)
- **Q&A Seeding** — 5 keyword-rich Q&A pairs per profile
- **Services List** — keyword-optimised service names
- Per-location **Health Score** (0–100%)
- Runs fully sequentially, one location at a time

</td>
<td>

### 🧠 Self-Learning Intelligence
- Profile data learned and cached permanently
- Never re-analyses a profile it already knows
- Gets smarter with every run
- Viewable keyword map per location
- Business personality profiling
- Concern & USP tracking from reviews

</td>
</tr>
</table>

---

## 🚀 Getting Started

### Prerequisites

- A Google account with **Manager or Owner** access to your GMB profiles
- A free [Google Cloud Console](https://console.cloud.google.com) account
- A free [Anthropic](https://console.anthropic.com) account (comes with $5 free credit)
- A place to host the HTML file (GitHub Pages — free, 5 minutes)

---

### Step 1 — Fork & Deploy to GitHub Pages

```bash
# Option A: Use GitHub UI
1. Click the "Fork" button top-right of this page
2. Go to your forked repo Settings → Pages
3. Source: Deploy from branch → main → / (root) → Save
4. Your live URL: https://YOUR-USERNAME.github.io/gmb-autopilot
```

```bash
# Option B: Clone and push
git clone https://github.com/konkomaji/gmb-autopilot.git
cd gmb-autopilot
# Enable GitHub Pages in repo Settings → Pages
```

> ⚡ **Fastest alternative:** Drag the HTML file to [netlify.com/drop](https://app.netlify.com/drop) — live in 10 seconds.

---

### Step 2 — Google Cloud Setup

**2a. Create Project**
```
console.cloud.google.com → New Project → Name: "GMB Autopilot" → Create
```

**2b. Enable APIs** — Go to *APIs & Services → Library* and enable:
```
✅ My Business API
✅ My Business Account Management API  
✅ My Business Business Information API
```

**2c. OAuth Consent Screen**
```
APIs & Services → OAuth Consent Screen
→ External → Create
→ App name: GMB Autopilot
→ Add your email as Support Email
→ Test Users → Add your agency Gmail → Save
```

**2d. Create OAuth Client ID**
```
APIs & Services → Credentials → + Create Credentials → OAuth Client ID
→ Application type: Web application
→ Authorised JavaScript origins: https://YOUR-GITHUB-PAGES-URL
→ Create → Copy the Client ID
```

---

### Step 3 — Get Your Claude API Key

```
console.anthropic.com → Settings → API Keys → Create Key
Copy the key (starts with sk-ant-...)
```

> 💰 Free tier = ~$5 credit = ~10,000 replies. For 70 profiles with 10 reviews each = 700 replies/run ≈ practically free.

---

### Step 4 — Connect & Run

```
1. Open your GitHub Pages URL
2. Paste Google OAuth Client ID
3. Paste Anthropic API Key  
4. Click "Connect Google Account & Start"
5. Sign in with your agency Google account
6. All 70+ profiles load automatically
7. Click ▶ Run Reviews — watch the magic happen
```

---

## 🗂️ Project Structure

```
gmb-autopilot/
│
├── index.html          ← The entire application (single file)
├── README.md           ← This file
├── LICENSE             ← MIT License
└── .github/
    └── FUNDING.yml     ← Support the project
```

> **Why a single file?** Zero dependencies. Zero build steps. No Node.js, no npm, no webpack. Download, host, run. The entire intelligence engine is 1,500 lines of vanilla HTML/CSS/JS.

---

## 🔧 Configuration Options

| Setting | Default | Description |
|---------|---------|-------------|
| Reply Tone | Professional | Global default (overridden per-profile by AI) |
| Report Time | 20:00 | Daily auto-report generation time |
| Reply Delay | 3 seconds | Pause between API calls to avoid rate limits |
| Post Type | Photo | Default content studio post type |

All settings are stored locally in your browser — nothing is ever sent to any external server.

---

## 🔐 Privacy & Security

```
✅ All credentials stored in browser localStorage only
✅ No backend server — direct browser → Google API communication  
✅ No data collection, no analytics, no telemetry
✅ Open source — audit every line of code
✅ OAuth tokens auto-expire (Google standard)
✅ Your client data never leaves your browser
```

---

## 📊 What Gets Optimized (Optimizer Tab)

| Optimization | API Used | Impact |
|-------------|----------|--------|
| Business Description | Business Information API PATCH | 🔴 Critical for ranking |
| Google Posts (3x) | Local Posts API POST | 🟡 High engagement signal |
| Q&A Seeding (5x) | Questions API POST | 🟡 Long-tail keyword coverage |
| Services List | Business Information API PATCH | 🟢 Category relevance |
| Review Replies | Reviews API PUT | 🔴 Critical trust signal |
| Photo Upload | Media API POST | 🟢 Profile completeness |

---

## 🛠️ Tech Stack

```
Frontend:    Vanilla HTML5 + CSS3 + ES6 JavaScript
AI Engine:   Claude Haiku (claude-haiku-4-5-20251001) via Anthropic API
Auth:        Google Identity Services (GSI) OAuth 2.0
APIs:        Google My Business API v4
             My Business Account Management API v1
             My Business Business Information API v1
Storage:     Browser localStorage (no database)
Hosting:     Any static host (GitHub Pages, Netlify, Vercel)
Bundle:      Single .html file — zero dependencies
```

---

## 🗺️ Roadmap

- [ ] Scheduled auto-run (daily/weekly cron via browser alarm)
- [ ] Multi-language reply support
- [ ] Sentiment trend charts per location
- [ ] Competitor review benchmarking
- [ ] WhatsApp/email alert when negative review detected
- [ ] Client portal view (read-only shareable report links)
- [ ] Bulk CSV import for offline review management
- [ ] Chrome Extension version

---

## 🤝 Contributing

Contributions are what make the open source community amazing. Any contributions you make are **greatly appreciated**.

```bash
1. Fork the Project
2. Create your Feature Branch (git checkout -b feature/AmazingFeature)
3. Commit your Changes (git commit -m 'Add some AmazingFeature')
4. Push to the Branch (git push origin feature/AmazingFeature)
5. Open a Pull Request
```

---

## 🐛 Known Limitations

- **Services API** — Google's Services List API can be restrictive for some business categories. If it fails, add services manually in GMB dashboard.
- **Photo Upload** — Direct byte upload requires the GMB Media API which may need approval for some accounts. If blocked, use the Content Studio for text posts instead.
- **OAuth Token Expiry** — Tokens last ~1 hour. For very large portfolios (70+ locations), you may need to reconnect mid-run.
- **Rate Limits** — Google limits API calls. The built-in delay (3s default) handles this, but increase to 5-8s if you see errors.
- **App Verification** — For production use with live user data beyond test users, you'll need Google to verify your OAuth app (free, takes 1-7 days).

---

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 📬 Contact & Support

<div align="center">

**Konko Maji** — Digital Marketing Technologist

[![Email](https://img.shields.io/badge/Email-work.konkomaji%40gmail.com-EA4335?style=for-the-badge&logo=gmail)](mailto:work.konkomaji@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-konkomaji-181717?style=for-the-badge&logo=github)](https://github.com/konkomaji)

**Agency:** VK Creatives — Digital Marketing & GMB Specialists, West Bengal, India

*For bugs, feature requests, and questions: [Open an Issue](https://github.com/konkomaji/gmb-autopilot/issues)*

</div>

---

## 🙏 Acknowledgements

<div align="center">

Built with ❤️ by **[Konko Maji](https://github.com/konkomaji)** with the power of **[Claude AI by Anthropic](https://anthropic.com)**

*"Automating what agencies charge a fortune for — and giving it back to the community."*

<br/>

[![Star History](https://img.shields.io/github/stars/konkomaji/gmb-autopilot?style=social)](https://github.com/konkomaji/gmb-autopilot)

**If this tool saves you time, drop a ⭐ — it means the world.**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6c63ff,50:00b4d8,100:00ff88&height=120&section=footer" width="100%"/>

</div>
