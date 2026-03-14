<div align="center">

<br/>

# Soft Skillet — Event Playbook

### Turn a trade show booth into a pipeline machine.

<br/>

**A data-driven, interactive sales playbook built from 10 real booth conversations at the NYC Restaurant Show.** Every recommendation is grounded in transcript evidence — not theory.

<br/>

[![View Live Site](https://img.shields.io/badge/VIEW%20LIVE%20SITE-playbook--two--chi.vercel.app-7ac4eb?style=for-the-badge&logo=vercel&logoColor=white)](https://playbook-two-chi.vercel.app)

<br/>

<img src="https://img.shields.io/badge/Conversations%20Analyzed-10-0E1C37?style=flat-square&labelColor=f0f4f8" />
&nbsp;
<img src="https://img.shields.io/badge/ICP%20Leads%20Identified-7-7ac4eb?style=flat-square&labelColor=f0f4f8" />
&nbsp;
<img src="https://img.shields.io/badge/Demo--Ready%20Prospects-3-f59e0b?style=flat-square&labelColor=f0f4f8" />
&nbsp;
<img src="https://img.shields.io/badge/Actionable%20Frameworks-6-10b981?style=flat-square&labelColor=f0f4f8" />

<br/>
<br/>

---

</div>

<br/>

## The Core Insight

<table>
<tr>
<td>

```
The pipeline doesn't break at interest.
It breaks at conversion.

  10 conversations
   7 ICP matches
   6 expressed strong interest
   3 were demo-ready
   1 left with a locked next step

That's a 17% conversion rate from interest → demo.
```

</td>
<td width="400">

**The fix isn't better pitching. It's better closing mechanics.**

Three structural failures:

**1. Pitch sequencing** — Reps defaulted to AI Seating regardless of buyer pain. Smooth Revenue had higher resonance but was underused.

**2. Weak closes** — "I'll email you info" was accepted as a next step. It isn't one.

**3. Champion bypass** — Pushing past enthusiastic contacts to reach decision-makers killed momentum.

</td>
</tr>
</table>

<br/>

## What's Inside

### Interactive Playbook &nbsp;`playbook/index.html`

<table>
<tr><td width="220"><b>Funnel Analysis</b></td><td>Full-funnel visualization: 10 conversations → 7 ICP → 6 interested → 3 demo-ready → 1 scheduled. Identifies exactly where pipeline breaks and why.</td></tr>
<tr><td><b>Pipeline Math</b></td><td>Rigorous conversion math with labeled working assumptions. NYC actual (<code>7 x 0.20 x 0.25 x 0.40 = 0.14 deals</code>) vs. playbook target (<code>7 x 0.45 x 0.25 x 0.40 = 0.32 deals</code>). Roughly 2-3x improvement.</td></tr>
<tr><td><b>ICP Scoring Framework</b></td><td>6-factor, 10-point model. All 10 NYC prospects scored and tiered. Factors: reservations, incumbent platform, DM path, review app relationship, demand volatility, multi-location.</td></tr>
<tr><td><b>Growth Loop</b></td><td>The review app → reservations cross-sell opportunity. 3 of 10 visitors were review app users; 2 cited existing trust as the reason they were open to the pitch. This is Soft Skillet's unfair advantage.</td></tr>
<tr><td><b>3-Phase Playbook</b></td><td>Pre-event (tiered targeting, pitch certification, materials). During-event (90-second qualification, objection handling, 5-step close). Post-event (follow-up tiers, debrief framework).</td></tr>
<tr><td><b>Battle Card</b></td><td>6-step booth conversation script with branching logic, time allocations, and exact talk tracks. Printable for each rep.</td></tr>
<tr><td><b>Top 3 Accounts</b></td><td>Day-by-day follow-up plans for Daljeet (Masala King), Dee (Dinex Group), and Brian (BJ's) with specific actions and rationale for each.</td></tr>
<tr><td><b>10 Real Mistakes</b></td><td>Every failure pattern observed in the NYC transcripts, with evidence and specific fixes. From jargon overload to premature discounting.</td></tr>
<tr><td><b>Certification Drills</b></td><td>5 interactive role-play scenarios with reveal/hide answers. Tests pitch matching, objection handling, and ICP qualification.</td></tr>
</table>

### Operational Tools

<table>
<tr><td width="220"><b>Conversation Timer</b></td><td>5-phase guided timer (Open 90s → Mirror 60s → Pitch 90s → Objections 90s → Close 60s) with color-coded phases, progress bar, and overtime alerts.</td></tr>
<tr><td><b>Pitch Matcher</b></td><td>Tap a buyer's pain point, get the matching talk track instantly. Covers Smooth Revenue, Operator, AI Seating, and not-ICP exit.</td></tr>
<tr><td><b>Scorecard</b></td><td>6-dimension post-conversation scoring (discovery, pitch match, jargon control, close quality, stakeholder handling, time efficiency). Grades A through D with targeted feedback.</td></tr>
<tr><td><b>Lead Capture</b></td><td>Full-field form with temperature tagging, pain capture in buyer's exact words, stakeholder mapping. Persists via localStorage. CSV export.</td></tr>
<tr><td><b>Email Generator</b></td><td>4 follow-up templates (Smooth Revenue, Operator/Partnership, Champion Handoff, Cross-Sell) with live preview and one-click copy. Under 120 words each.</td></tr>
</table>

<br/>

## Tech

| | |
|---|---|
| **Architecture** | Single HTML file. Zero dependencies. No frameworks, no build step. |
| **Interactivity** | Vanilla JavaScript — timer, scorecard, lead CRUD, email generation, accordions, tabs |
| **Persistence** | localStorage for lead data across sessions |
| **Responsive** | Mobile-optimized for use at actual event booths |
| **Design** | Clipboard Health-inspired: `#d7f1fe` page background, `#7ac4eb` primary blue, pill-shaped controls, 20px card radius, Montserrat + DM Sans |

<br/>

## Project Structure

```
.
├── playbook/
│   └── index.html                  # Interactive playbook + all tools
├── SoftSkillet_Event_Playbook.md   # Full playbook (markdown)
├── SoftSkillet_Report.md           # Rep evaluations + account analysis
└── README.md
```

<br/>

## Run Locally

```bash
# No install required — just open the file
open playbook/index.html

# Or serve it
npx serve playbook
```

<br/>

---

<div align="center">

<br/>

Built for the **Clipboard Health** hiring assessment.

<br/>

[![View the Live Playbook](https://img.shields.io/badge/View%20the%20Live%20Playbook-playbook--two--chi.vercel.app-7ac4eb?style=for-the-badge&logo=vercel&logoColor=white)](https://playbook-two-chi.vercel.app)

<br/>
<br/>

</div>
