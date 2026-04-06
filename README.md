# atharva-ai-lab 🧪

> A daily log of building with AI — prompts, tools, experiments, and shipped things.

I'm a Product Manager at Meesho, pre-founder, learning to become an AI-first builder.  
Every commit = something real I did that day. No fluff, no streak-gaming.

---

## How to use this repo (my personal operating manual)

### 📅 Daily (2 min)
Open `DAILY_LOG.md`, add one entry at the top describing what you did, commit and push.  
**Rule:** If you can't write 2 sentences about what you did, you didn't do enough to commit.

```bash
cd atharva-ai-lab
# edit DAILY_LOG.md
git add .
git commit -m "log: apr 7 — [one line of what you did]"
git push
```

### 📁 When to add files to folders
Only when you have something worth saving — a prompt that worked, a script, a note you'll reuse.  
Most days you'll only touch `DAILY_LOG.md`. That's fine.

### 📝 Every Sunday
Fill out a weekly review using `templates/weekly-review.md`.  
Save it as `reviews/YYYY-WXX.md` (e.g. `reviews/2025-W15.md`).  
Use it to draft your LinkedIn post.

---

## Folder guide — what goes where

### `DAILY_LOG.md` ← touch this every day
Your streak file. One entry per day, newest at top.  
Use the template in `templates/daily-log-entry.md`.

---

### `stock-tools/` — Indian equity research
**Add a file here when you:**
- Write a reusable prompt for stock analysis (Sovrenn, Aditya Joshi screener, etc.)
- Build a script or calculator for valuation
- Complete a stock analysis worth saving for reference

**Example files:**
```
stock-tools/
├── prompts/
│   ├── sovrenn-large-order.md       ← prompt template for Large Order method
│   ├── sovrenn-uptrend.md
│   └── aditya-joshi-screener.md     ← 6-criteria screener prompt
├── analyses/
│   └── GRSE-apr2025.md              ← your notes + verdict on a stock
└── watchlist.md                     ← stocks you're tracking + why
```

---

### `devapixels/` — AI content creation (Indian mythology channel)
**Add a file here when you:**
- Find an image prompt that works well — save the exact prompt
- Document a workflow or pipeline step (ComfyUI, MimicMotion, ElevenLabs, etc.)
- Write a caption or script template you'll reuse
- Learn something about a tool (Kling AI, Vast.ai, etc.) worth remembering

**Example files:**
```
devapixels/
├── prompts/
│   ├── dev-shishu-baby-krishna-v3.md   ← exact image prompt that worked
│   └── prompt-pattern-library.md       ← your "setting-first rule" + other principles
├── scripts/
│   └── reel-caption-template.md        ← caption structure for Reels
└── pipeline/
    └── comfyui-mimicmotion-setup.md    ← how to reproduce your Vast.ai workflow
```

---

### `openclaw/` — Personal AI OS (Telegram + OpenRouter + Hetzner)
**Add a file here when you:**
- Write or refine a system prompt for one of your 6 agents
- Make an architecture decision worth documenting
- Fix something that broke — log what broke and how you fixed it
- Add a new tool integration or cron setup

**Example files:**
```
openclaw/
├── agents/
│   ├── stock-analyser-prompt.md     ← system prompt for your Stock Analyser agent
│   ├── health-tracker-prompt.md
│   └── news-feed-prompt.md
├── architecture.md                  ← key decisions (the 28 points you validated)
└── learnings.md                     ← what broke, what you changed, what worked
```

---

### `work-tools/` — PM + AI workflows (Meesho / supply chain context)
**Add a file here when you:**
- Build a reusable prompt for a PM task (PRD, metrics analysis, retro, etc.)
- Create a framework or template you use at work regularly
- Document an AI workflow that made a work task faster

**Note:** No proprietary Meesho data. Use generic/anonymised examples only.

**Example files:**
```
work-tools/
├── prompts/
│   ├── prd-writer.md                ← prompt for drafting PRDs
│   ├── metrics-interpreter.md       ← prompt for analysing delivery metrics
│   └── retro-summariser.md
└── frameworks/
    └── delivery-failure-analysis.md ← generic framework for ops analysis
```

---

### `experiments/` — Everything else (most active folder early on)
**Add a file here when you:**
- Try a new AI tool — write a short verdict
- Learn a new prompting technique worth remembering
- Build a one-off thing that doesn't fit elsewhere
- Start exploring something you're not sure about yet

**Example files:**
```
experiments/
├── tool-reviews/
│   ├── kling-ai.md                  ← what it does, verdict, use case
│   └── cursor-vs-copilot.md
└── prompt-patterns/
    ├── chain-of-thought.md          ← how and when to use it
    └── structured-output-tricks.md
```

---

### `templates/` — Don't edit these often
- `daily-log-entry.md` — copy this into DAILY_LOG.md each day
- `weekly-review.md` — copy this into `reviews/` each Sunday

### `reviews/` — Create this folder when you do your first weekly review
- `2025-W15.md`, `2025-W16.md`, etc.

---

## The only rule
**Every commit must update `DAILY_LOG.md`.**  
If a file is worth committing, it's worth logging what you did and why.

---

## Connect
- LinkedIn: https://www.linkedin.com/in/atharvaagarwal/
- GitHub: [github.com/aatharva16](https://github.com/aatharva16)
