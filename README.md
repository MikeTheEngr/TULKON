```
████████╗  ██╗   ██╗  ██╗       ██╗  ██╗   ██████╗   ███╗   ██╗
╚══██╔══╝  ██║   ██║  ██║       ██║ ██╔╝  ██╔═══██╗  ████╗  ██║
   ██║     ██║   ██║  ██║       █████╔╝   ██║   ██║  ██╔██╗ ██║
   ██║     ██║   ██║  ██║       ██╔═██╗   ██║   ██║  ██║╚██╗██║
   ██║     ╚██████╔╝  ███████╗  ██║  ██╗  ╚██████╔╝  ██║ ╚████║
   ╚═╝      ╚═════╝   ╚══════╝  ╚═╝  ╚═╝   ╚═════╝   ╚═╝  ╚═══╝
```

### Travel Understanding, Knowledge Oriented Network

![TULKON Demo](https://raw.githubusercontent.com/MikeTheEngr/TULKON-V1/main/preview.gif)

> *Young people don't just travel to see places, they travel to change their lives. TULKON is the first app built around that truth.*

---

## What is TULKON?

TULKON is an AI-powered travel companion platform built for the generation that travels with purpose, not just tourists, but people chasing scholarships, careers, cultural exchange, and life-changing experiences across borders.

At its core is a deeply personal AI travel buddy that knows who you are, remembers your journey, searches the web in real time, and surfaces opportunities, visa pathways, scholarships, job markets, specific to your nationality and destination. Built around a social explorer network where travelers connect, level up through gamification, and eventually communicate across language barriers in real time.

---

## Core Intelligence

### AI Travel Buddy — 4-Layer Architecture

**Layer 1 — Identity**
Every conversation is personalised with the user's nationality, home country, languages, and travel goals. TULKON knows who it's talking to and frames every response around that specific person.

- Nigerian asking about Germany → visa requirements for Nigerian passport holders, DAAD scholarships, job seeker visa pathways
- Never generic. Every response is written for that exact traveler.

**Layer 2 — Real-time Intelligence**
Powered by Tavily web search, TULKON detects when a query needs current data, visa fees, scholarship deadlines, job openings, travel advisories — and fetches live results before responding.

- Trigger keywords: visa, scholarship, deadline, cost, fee, hiring, requirement, current, latest
- Search queries are augmented with the user's nationality for maximum relevance

**Layer 3 — Persistent Memory**
After every conversation, an LLM extraction pipeline reads the exchange and saves memorable facts to Supabase — destinations researched, career goals mentioned, travel plans discussed. On the next session, those memories are silently injected into the system prompt.

- TULKON remembers you asked about Germany last week
- TULKON remembers you mentioned you're a software engineer
- No prompting needed, it just knows

**Layer 4 — Proactive Intelligence** *(in development)*
Notices patterns across conversations and volunteers relevant information without being asked.

---

## Live Demo

🔗 **[TULKON](https://tulkon-v1.vercel.app/)**

---


## Key Features

- **AI Chat** — streaming travel companion with web search, memory, and full identity awareness
- **Translation** — text, cultural context, "show to local" mode, two-way voice translation
- **Cultural Explorer** — deep cultural insights, customs, etiquette, local tips by destination
- **Trip Planner** — create trips, build itineraries day by day, manage packing lists
- **Explorer Social Network** — mutual friend requests, discovery by shared travel goals and location
- **Gamification** — Tier 1 engagement badges (Seedling → World Citizen) + PLATINUM badge for verified international travel
- **Persistent Memory** — TULKON silently learns from every conversation and remembers you next time
- **Voice Translation** — speak in your language, TULKON translates and plays it aloud for the local
- **Dark mode** — full dark/light theme support across all pages

---

## Gamification System

### Tier 1 — Engagement Badges
Earned through activity on TULKON. Progress bar visible to the user.

| Badge | Points Required |
|---|---|
| 🌱 Seedling | 0 – 49 |
| 🧭 Explorer | 50 – 149 |
| 🌍 Wanderer | 150 – 349 |
| ✈️ Globetrotter | 350 – 699 |
| 🏆 World Citizen | 700+ |

Points are awarded for: chat messages, trips logged, translations made, friends added, profile completed, flight purchases.

### Tier 2 — PLATINUM 🏅
Exclusive badge earned only by verified international travel. Shows a counter of unique foreign countries visited.

Verification methods: flight purchase through TULKON (automatic), GPS location (automatic), boarding pass upload, passport stamp upload.

---

## Status

TULKON is an active work in progress — a living product being built in public.

Core features are functional and deployed, but the platform is still growing. Features currently in active development include real-time social chat with auto-translation, Stories, TIMOJI avatar builder, the Opportunity Finder (scholarships and work programs by destination), and a full migration from Render to GCP Cloud Run for production-grade reliability.

This is not a finished product. It is a vision being built one commit at a time.

Built by **MikeTheEngr** ([@MikeTheEngrr](https://x.com/MikeTheEngrr)) — AI Engineer & Full Stack Developer.


---

*TULKON — Travel Understanding, Knowledge Oriented Network · Built for the generation that travels to change their lives.*
