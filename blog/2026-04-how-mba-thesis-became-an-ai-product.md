---
title: "How an MBA Thesis Became an AI-Powered Project Management Product in 6 Months"
date: 2026-04-16
author: Aleksandr Grebeshok
tags: [AI, ProjectManagement, Construction, MBA, Startup]
summary: "From a thesis analyzing PMBOK in Arctic conditions to a production system running 5 AI agents on real infrastructure projects — with 693% ROI."
repo: https://github.com/alexgrebeshok-coder/ceoclaw-docs
---

# How an MBA Thesis Became an AI-Powered Project Management Product in 6 Months

Six months ago, I was defending my MBA thesis at RANEPA, analyzing why standard project management frameworks fail in the Russian Arctic. Today, that thesis is a running product — CEOClaw — with five AI agents managing real construction projects worth over a billion rubles.

This is the story of how academic research turned into production software, and why I think the construction industry is the next frontier for applied AI.

## The Problem: Construction in a Place That Shouldn't Have Construction

I've spent 24 years in construction. The last two years I've been with **Severavtodor**, a company operating in the Yamalo-Nenets Autonomous Okrug (YNAO) — the Russian Arctic. Our annual revenue exceeds 1 billion rubles (~$11M). We run 58 people across 7+ concurrent projects building roads, infrastructure, and industrial facilities.

Here's what makes this region brutal:

- **Construction season: 2–3.5 months.** The ground thaws, you work frantically, then everything freezes again.
- **Logistics via zimniks.** Winter ice roads are your supply lifeline. When they melt, you're cut off.
- **Talent desert.** Finding qualified engineers who want to live 150km north of the Arctic Circle is... a challenge.

In this environment, every day of delay costs real money. And we were bleeding.

**The numbers were ugly:**
- **+25% budget overruns** across the project portfolio
- **+25% schedule slippage** on average
- **50+ million rubles lost per year** (~$550K) — straight into the gap between plan and reality

These aren't abstract risks. This is a company where a single delayed material delivery can cascade into missing the entire construction window, pushing an entire project into the next year's season.

## The Thesis: Why PMBOK Doesn't Work at -40°C

For my MBA at the Russian Presidential Academy of National Economy and Public Administration (RANEPA), I chose to study project management — not as an academic exercise, but as a survival problem.

I analyzed the three major frameworks:

| Framework | Strength | Problem in Arctic |
|-----------|----------|-------------------|
| **PMBOK** (PMI) | Comprehensive knowledge base | Too generic for extreme conditions |
| **PRINCE2** | Process-driven governance | Doesn't handle seasonal compression |
| **IPMA** (ICB) | Competence-based | Assumes a normal labor market |

None of them accounted for what I'll call the "Arctic project management gap" — the structural mismatch between standard methodologies and operating conditions where:

1. Your planning horizon is measured in weeks, not months
2. Supply chain lead times are measured in seasons
3. Labor availability follows inverse logic — fewer people, more remote work
4. Risk is not a theoretical exercise but a daily operational reality

My thesis proposed a **Corporate Project Management System (КСУП)** adapted to these constraints — integrating elements from all three frameworks but calibrated for Arctic conditions. The financial model showed:

- **ROI: 171%**
- **Payback period: 4–5 months**
- **NPV: 206 million rubles over 5 years**

Solid numbers on paper. But a thesis is a PDF file. I needed a system.

## From Thesis to System: The 40-Document Sprint

Building the corporate project management system (КСУП) meant creating the institutional infrastructure first — not code, but the operational backbone that software would later support:

- **40 documents** covering processes, templates, roles, and integration protocols
- **580+ pages** of methodology, procedures, and guidelines
- **~1,700 test scenarios** validating every workflow

This wasn't bureaucracy for its own sake. Each document mapped to a real operational gap. When your company is running 7+ concurrent projects with 58 people across a territory the size of Western Europe, informal coordination doesn't scale.

The documentation phase took roughly 3 months. During this time, I also identified the key integration points that any software system would need:

- **1C:ERP** — financial accounting and enterprise resource planning
- **1C:PM** — project management module
- **GPS/GLONASS** — equipment and vehicle tracking
- **Video surveillance** — construction site monitoring
- **FGIS TS** — Federal State Information System for construction industry compliance

Every Russian construction company runs on these systems. The question was how to sit on top of them intelligently rather than replace them.

## The AI-PMO: Five Agents, One Mission

That's where the idea for **AI-PMO** came in — an AI-powered Project Management Office that doesn't replace the PMO team but augments it with five specialized agents:

### 1. PMO Director Agent
The orchestrator. Understands portfolio-level priorities, resolves conflicts between projects, and escalates what needs human attention. Think of it as the AI deputy that never sleeps and has perfect memory of every project status.

### 2. Planning Agent
Handles schedule optimization, critical path analysis, and resource allocation. In Arctic conditions, this means understanding seasonal constraints, zimnik logistics windows, and crew rotation schedules. It doesn't just plan — it re-plans continuously as conditions change.

### 3. Monitoring Agent
Ingests data from GPS/GLONASS trackers, video feeds, and progress reports. Flags deviations from plan in real-time. The key insight: in a 2.5-month construction season, discovering a two-week delay at the monthly review is discovering it too late.

### 4. Financial Control Agent
Tracks budget consumption against earned value. Connects to 1C:ERP for actuals and to the planning agent for forecasts. Produces the kind of financial visibility that normally requires a dedicated cost engineer — except it runs 24/7.

### 5. Knowledge Management Agent
This is the quiet powerhouse. Every project generates lessons — what worked, what didn't, what the supplier lead times actually were, how the crew handled that unexpected permafrost issue. This agent captures, structures, and retrieves institutional knowledge. The next project doesn't start from zero.

## CEOClaw v1.0.0: March 2026

By March 2026, we had **CEOClaw v1.0.0** — a web application with:

- **Dashboard** — real-time portfolio overview with financial, schedule, and risk metrics
- **Kanban boards** — task management for project teams
- **AI agent panel** — the five agents working behind the scenes, accessible through a unified interface
- **System integrations** — connected to 1C:ERP, 1C:PM, GPS/GLONASS, and video feeds

The system is running on **real projects right now**. Not a pilot, not a demo — production workloads with real budgets, real deadlines, and real consequences.

### Architecture decisions

The tech stack was driven by pragmatism, not hype:

- **React + TypeScript** for the frontend — fast iteration, strong typing
- **Node.js** backend with agent orchestration
- **Multi-model AI** — different agents can use different LLMs depending on the task (some need deep reasoning, others need speed and low cost)
- **Integration layer** — connects to existing enterprise systems via APIs rather than replacing them

The key architectural principle: **AI should be a layer, not an island**. Every agent works with the company's existing data systems, not in isolation.

## The Numbers

Let me be specific about what we're seeing:

### Corporate PM System (КСУП) — Non-AI baseline
| Metric | Value |
|--------|-------|
| ROI | 171% |
| Payback | 4–5 months |
| NPV (5 years) | 206M ₽ |

### AI-PMO Layer
| Metric | Value |
|--------|-------|
| Annual savings | 120M ₽/year (~$1.3M) |
| ROI range | 163%–693% |
| Payback | 11 months |

The 163%–693% ROI range reflects different scenarios — conservative (based on current project volumes) to optimistic (scaled across the full portfolio). Even at the conservative end, the economics are compelling.

The 11-month payback for the AI layer is longer than the 4–5 months for the base system — which makes sense. The base system fixes process gaps. The AI layer compounds those gains by automating monitoring, analysis, and knowledge transfer.

## What I Learned

**1. Domain expertise is the moat.** I could not have built this from the outside. Twenty-four years of construction experience — understanding what a zimnik is, why permafrost matters, how crew rotations actually work — this is what makes the system useful rather than theoretical.

**2. Don't replace, augment.** Every construction company already has ERP, PM tools, tracking systems. The value isn't in replacing them — it's in sitting on top and providing the intelligence layer that connects them.

**3. AI agents need domain guardrails.** A generic "project management AI" would give you generic advice. Our agents understand Arctic construction constraints. The Planning Agent knows about seasonal windows. The Monitoring Agent knows that GPS coordinates alone don't tell you if the work is quality — you need video. Context is everything.

**4. Start with the methodology, not the technology.** We spent months on the 40-document system before writing a line of AI code. The agents implement the methodology; they don't invent it. If your processes are broken, AI will just automate broken processes faster.

**5. Six months is possible when you have zero ambiguity about the problem.** I wasn't exploring a market or searching for product-market fit. I had specific numbers (50M ₽ in annual losses), specific constraints (Arctic conditions), and specific integration requirements (1C, GPS, FGIS). When the problem is that clear, execution speed follows.

## What's Next

The near-term roadmap:

- **Expanded integrations** — deeper 1C connectivity, weather data feeds, drone survey integration
- **Predictive analytics** — move from monitoring (what's happening) to prediction (what will happen) using historical project data
- **Multi-company deployment** — the methodology and system architecture are generalizable beyond Severavtodor
- **Mobile-first** — field teams need access through phones, not desktops

Longer-term, I believe construction project management is ripe for an AI platform play. The industry is fragmented, the software ecosystem is a mess of legacy systems, and the economic pain of poor project management is massive but largely invisible because it's normalized as "just how construction works."

It doesn't have to be.

## Build in Public

The CEOClaw source code and documentation are open-source. If you're building AI systems for construction, project management, or similar domains — or if you're just curious about how to turn domain expertise into production AI — take a look.

**Repository:** [github.com/alexgrebeshok-coder/ceoclaw-docs](https://github.com/alexgrebeshok-coder/ceoclaw-docs)

---

*If you found this interesting, I write about the intersection of construction, AI, and practical project management. Follow for more.*

**Tags:** `#AI` `#ProjectManagement` `#Construction` `#MBA` `#Startup` `#OpenSource`
