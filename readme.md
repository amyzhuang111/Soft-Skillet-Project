<div align="center">

# Soft Skillet — Event Playbook

**A data-driven sales playbook built from 10 real booth conversations at the NYC Restaurant Show.**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-playbook.amyzhuang.me-7ac4eb?style=for-the-badge&logo=vercel&logoColor=white)](https://playbook-two-chi.vercel.app)
[![Built With](https://img.shields.io/badge/Built%20With-HTML%20%2F%20CSS%20%2F%20JS-0E1C37?style=for-the-badge)](#)

<br/>

<img src="https://img.shields.io/badge/Conversations%20Analyzed-10-0E1C37?style=flat-square" />
<img src="https://img.shields.io/badge/ICP%20Leads%20Identified-7-7ac4eb?style=flat-square" />
<img src="https://img.shields.io/badge/Actionable%20Frameworks-6-10b981?style=flat-square" />

</div>

---

## What This Is

An interactive event sales playbook for **Soft Skillet**, a fictitious restaurant technology company. Every recommendation is grounded in evidence extracted from 10 transcribed sales conversations — not theory.

The playbook answers one question: **How do you turn a trade show booth into a pipeline machine?**

---

## What's Inside

### Playbook (Interactive Web App)

| Section | What It Covers |
|---|---|
| **Funnel Analysis** | Full-funnel breakdown: 10 conversations → 7 ICP → 6 interested → 3 demo-ready → 1 scheduled. Where pipeline breaks and why. |
| **Pipeline Math** | Rigorous conversion math with working assumptions. NYC actual (~0.1 deals) vs. playbook target (~0.3 deals). |
| **ICP Scoring** | 6-factor, 10-point framework. Every NYC prospect scored and tiered. |
| **Growth Loop Insight** | The review app → reservations cross-sell opportunity hiding in the data. |
| **3-Phase Playbook** | Pre-event targeting, during-event tactics (discovery, objection handling, closing), post-event follow-up. |
| **Battle Card** | Step-by-step booth conversation script with branching logic. |
| **Top 3 Accounts** | Day-by-day follow-up plans for Daljeet, Dee, and Brian with specific actions. |
| **10 Real Mistakes** | Every failure pattern from the NYC show, with fixes. |

### Operational Tools

| Tool | Purpose |
|---|---|
| **Conversation Timer** | 5-phase guided timer (Open → Mirror → Pitch → Objections → Close) with overtime alerts |
| **Pitch Matcher** | Tap a buyer's pain, get the matching talk track instantly |
| **Post-Conversation Scorecard** | 6-dimension scoring (discovery, pitch match, jargon, close, stakeholder, time) |
| **Lead Capture Form** | Full-field lead logging with localStorage persistence + CSV export |
| **Follow-Up Email Generator** | 4 templates (Smooth Revenue, Operator, Champion Handoff, Cross-Sell) with live preview |

---

## Key Findings

```
The pipeline doesn't break at interest — it breaks at conversion.

6 of 10 prospects expressed strong interest.
Only 1 left with a locked next step.

The fix isn't better pitching. It's better closing mechanics.
```

**Three structural issues identified:**

1. **Pitch sequencing** — Reps defaulted to AI Seating regardless of buyer pain. Smooth Revenue converted better but was underused.
2. **Weak closes** — "I'll email you info" was accepted as a next step. It isn't one.
3. **Champion bypass** — Pushing past enthusiastic contacts to reach decision-makers killed momentum.

---

## Tech Stack

- **Zero dependencies** — Single HTML file, no frameworks, no build step
- **Vanilla JS** — All interactivity (timer, scorecard, lead management, email generation)
- **localStorage** — Lead data persists across sessions
- **Responsive** — Mobile-optimized for use at actual event booths
- **Design System** — Inspired by [Clipboard Health](https://clipboardhealth.com): `#d7f1fe` backgrounds, `#7ac4eb` primary blue, pill-shaped controls, Montserrat + DM Sans typography

---

## Project Structure

```
.
├── playbook/
│   └── index.html          # Interactive playbook + all tools (single file)
├── SoftSkillet_Event_Playbook.md   # Full playbook in markdown
├── SoftSkillet_Report.md           # Detailed rep evaluations + account analysis
└── README.md
```

---

## Run Locally

No install required. Just open the file:

```bash
open playbook/index.html
```

Or serve it:

```bash
npx serve playbook
```

---

<div align="center">

Built for the Clipboard Health hiring assessment.

**[View Live](https://playbook-two-chi.vercel.app)**

</div>
