# Getting Started

## What is CEOClaw?

**CEOClaw** is an AI-powered project management platform built specifically for construction companies. It combines traditional PM methodology (EVM, critical path, risk management) with modern AI capabilities (predictive analytics, automated reporting, intelligent agents).

## Who is it for?

| Role | How CEOClaw helps |
|------|-------------------|
| **Project Manager** | Automated reporting, delay prediction, EVM dashboards |
| **PMO Director** | Portfolio overview, strategic KPIs, resource allocation |
| **Financial Controller** | Budget tracking, variance analysis, cost forecasting |
| **CFO / CEO** | Executive dashboards, ROI tracking, decision support |
| **Engineer / Foreman** | Task management, photo documentation, mobile access |

**Target company size:** 50 to 500+ employees in construction, mining, or infrastructure.

## What problems does it solve?

### Problem 1: Tool Fragmentation
> "We use WhatsApp for communication, Excel for budgets, email for approvals, and paper for site documentation."

**CEOClaw:** Single platform — tasks, budgets, documents, communication, and AI analysis in one place.

### Problem 2: Late Problem Detection
> "We find out about budget overruns 2 months too late."

**CEOClaw:** Real-time EVM analytics with AI-powered delay prediction. Problems flagged before they escalate.

### Problem 3: Reporting Overhead
> "Our PMs spend 40% of their time writing reports instead of managing projects."

**CEOClaw:** Automated weekly/monthly reports in one click. AI generates narratives from project data.

### Problem 4: No Arctic/Remote Tools
> "Nothing works well when you're 200km from the nearest cell tower."

**CEOClaw:** Designed for harsh environments — offline mode, GPS/GLONASS integration, photo documentation with geotags.

## System Requirements

### For Users
| Requirement | Minimum | Recommended |
|-------------|---------|-------------|
| Browser | Chrome 90+, Firefox 88+, Safari 14+ | Chrome 120+, Firefox 120+ |
| Internet | 10 Mbps (online mode) | 50+ Mbps (AI features) |
| Storage | 100 MB (offline mode) | 500 MB |
| Language | RU/EN/ZH | All supported |

### For Enterprise Deployments
| Component | Specification |
|-----------|---------------|
| Hosting | Vercel (recommended) or AWS/Google Cloud |
| Database | PostgreSQL 14+ (managed: Supabase/Neon) |
| AI Providers | OpenRouter, Zhipu AI, OpenAI (multi-provider) |
| Storage | S3-compatible (AWS S3, Cloudflare R2) |
| SSL | Automatic (Let's Encrypt) |

### Offline Mode Requirements
- **OS:** Windows 10+, macOS 11+, Linux (Ubuntu 20.04+)
- **Disk Space:** 500 MB (cached data + documents)
- **GPS/GLONASS:** Android (built-in), iOS (external Bluetooth GPS recommended)

---

## Quick Start (5 Steps)

Follow these steps to start using CEOClaw today:

### Step 1: Create Account
1. Join [t.me/ceoclaw_beta](https://t.me/ceoclaw_beta) to request access
2. Receive your credentials via Telegram (or use demo credentials for quick test)
3. Confirm your email address

### Step 2: Complete Your Profile
1. Log in to [ceoclaw.vercel.app](https://ceoclaw.vercel.app)
2. Navigate to **Settings → Profile**
3. Add your:
   - Company name and logo
   - Default currency (RUB, USD, EUR, etc.)
   - Preferred language (RU/EN/ZH)
   - Timezone (Asia/Yekaterinburg, UTC+5 recommended)

### Step 3: Import Your First Project
1. Go to **Projects → New Project**
2. Fill in the basics:
   - **Name:** Project identifier (e.g., "Road Construction - Section 1")
   - **Budget:** Total planned cost (₽ or USD)
   - **Start/End dates:** Project timeline
   - **Location:** Project site address
3. Upload project documents (Excel, PDF, 1C exports)
4. AI automatically extracts:
   - Task hierarchy
   - Budget breakdown
   - Resource allocation
   - Dependencies

### Step 4: Connect Your Data
1. **1C Integration (optional but recommended):**
   - Go to **Settings → Integrations → 1C:ERP/PM**
   - Enter your 1C server URL and credentials
   - Select which entities to sync (projects, tasks, documents)
   - Schedule automatic data refresh (daily recommended)

2. **GPS/GLONASS (optional):**
   - For mobile apps and field tracking
   - Configure device permissions
   - Set up automatic position updates

3. **Yandex Maps (automatic):**
   - CEOClaw automatically geocodes project locations
   - Display on interactive map
   - Add photo markers

### Step 5: Explore AI Features
Once your project is set up, try these AI capabilities:

1. **Ask Questions (Chat):**
   > *"What are the critical path tasks for Project Alpha?"*
   > *"Generate a risk report for all projects in Q3."*
   > *"Compare budget variance between Road Construction and Bridge Project."*

2. **Get AI Insights:**
   - Navigate to **Dashboard** — AI highlights top risks and opportunities
   - Click on any metric for AI-generated explanations
   - View **Forecast** tab for predicted delays and overruns

3. **Automate Reporting:**
   - Create custom reports in **Reports → New Report**
   - AI writes narrative sections automatically
   - Export to PDF, Excel, or share link

**Success!** You're now using CEOClaw. Start by importing one project, then gradually add more.

---

## How to Get Access

CEOClaw is currently in **beta**:

1. **Join the Telegram channel:** [t.me/ceoclaw](https://t.me/ceoclaw)
2. **Request beta access:** [t.me/ceoclaw_beta](https://t.me/ceoclaw_beta)
3. **Email:** alex@ceoclaw.com

### Try Live Demo
No account needed! Experience CEOClaw instantly:
- **URL:** [https://ceoclaw.vercel.app](https://ceoclaw.vercel.app)
- **Email:** demo@ceoclaw.app
- **Password:** demo1234
- *Note: Demo data is reset daily. Real credentials recommended for production use.*

### Demo Credentials (Beta Access)
If you request beta access via Telegram, you'll receive:
- **Email:** Your email address
- **Password:** Temporary password (changes weekly)
- **Organization:** Your company (for multi-tenant isolation)

## Quick Tour

### Dashboard Overview
![Dashboard](../assets/images/screenshots/01_Dashboard.png)

**What you see:**
- Portfolio KPIs: total budget, active projects, risk score, AI summary
- Traffic light indicators for project health (green/yellow/red)
- AI-generated insights box with top 3 recommendations
- Quick access to recent projects and actions

**Try this:**
- Hover over any KPI to see detailed breakdown
- Click on projects with yellow/red indicators for quick view
- Use the **"Ask AI"** button for custom insights

### Project Management
![Projects](../assets/images/screenshots/02_Projects.png)

**What you see:**
- All projects in a clean card layout
- Status badges, budget progress bars, timeline indicators
- Quick actions: edit, export, duplicate, delete
- Filter by status, timeline, or team

**Try this:**
- Click any project to see detailed view
- Drag projects to reorder (personal preference)
- Use filter buttons to find projects by status

### Gantt Charts
![Gantt](../assets/images/screenshots/03_Gantt_Chart.png)

**What you see:**
- Timeline view with tasks and dependencies
- Critical path highlighted (red line)
- Current date marker
- Drag-and-drop to reschedule tasks
- AI suggestions for schedule optimization

**Try this:**
- Click and drag task bars to adjust dates
- Hover over tasks to see details (budget, owner, constraints)
- Click "AI Optimize" for automated scheduling

### EVM Analytics
![Analytics](../assets/images/screenshots/04_Analytics.png)

**What you see:**
- Earned Value Management (EVM) metrics: CPI, SPI, EAC, TCPI
- Trend charts for cost and schedule performance
- AI-powered forecasts (predicted completion date, cost overrun)
- Variance analysis (actual vs. planned)

**Try this:**
- Select different projects to compare metrics
- Click on any chart to see detailed breakdown
- Check the "AI Forecast" box for predictions

### AI Chat
![AI Chat](../assets/images/screenshots/05_AI_Chat.png)

**What you see:**
- Natural language chat interface
- AI responds with streaming text
- Context-aware: knows your current projects
- Multiple providers: OpenRouter, Zhipu AI, OpenAI

**Try this:**
- Ask: *"What are the biggest risks across all projects?"*
- Ask: *"Generate a report on budget variance."*
- Click "Regenerate" for alternative answers

### Risk Matrix
![Risks](../assets/images/screenshots/06_Risks_Matrix.png)

**What you see:**
- Risk matrix (probability × impact)
- AI-generated mitigation strategies
- Risk level colors: low (green), medium (yellow), high (red)
- Add, edit, and delete risks

**Try this:**
- Click on a risk to see detailed mitigation plan
- Drag risks to different probability/impact levels
- Use AI to generate new risk scenarios

### Kanban Board
![Kanban](../assets/images/screenshots/07_Kanban_Board.png)

**What you see:**
- Drag-and-drop task management
- Columns: Backlog, In Progress, Review, Done
- Task details: assignee, due date, priority
- Filter by project, assignee, or priority

**Try this:**
- Drag tasks between columns
- Click "Add Task" to create new ones
- Use filters to focus on specific work items

## Getting Help

| Need | Solution |
|------|----------|
| **Technical issues** | Join [t.me/ceoclaw](https://t.me/ceoclaw) and tag @KrabikkBot |
| **Feature requests** | Use the "Feedback" button in the app |
| **Integration help** | Email: alex@ceoclaw.com |
| **Enterprise sales** | Email: sales@ceoclaw.com |

**Documentation:** [Complete documentation](../index.md) | [API reference](../api.md) | [Changelog](../changelog.md)
