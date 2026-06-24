# PeopleLens — HR Intelligence Platform

A browser-based HR intelligence platform built for IT services and GCC environments. Runs entirely in the browser — no backend, no database, no installation. Data loads from Excel files parsed at runtime.

🔗 **Demo:** Deploy `PeopleLens-Demo.html` directly to any static host (Vercel, Netlify, GitHub Pages)

---

## What it does

PeopleLens gives HR leaders and account managers a single-pane view of their workforce — bench resources, active employees, upcoming rolloffs, resignations, and open positions — with AI-powered intelligence layered on top.

### Core modules

**Employee Intelligence**
- Full employee profiles: skills, project history, appraisal data, manager feedback
- AI-generated HR Intelligence Briefs per employee (Claude API)
- Cross-skill finder — search any skill and surface who has it

**Bench & Talent Hub**
- Live bench tracking with aging indicators (days on bench, risk bands)
- Automated skill-match scoring against open client positions
- Coverage finder — "if we release this person, who can cover?"
- Resume verification flags — alerts where resume on file may not match actual skills

**Workforce Overview**
- KPI cards: headcount, bench count, open positions, upcoming rolloffs
- Resignation tracker with last working days
- Upcoming rolloff pipeline by client and date

**Practice Area View**
- Workforce segmented by practice (QA, Dev, Integration, Data, Cloud, BI, etc.)
- Headcount and bench count per practice
- Build/Buy/Borrow/Bot analysis integration

---

## How it works

- Single HTML file — all logic, CSS, and UI in one place
- Data is loaded from localStorage (paste from Excel or import JSON)
- Claude API powers the AI Intelligence Brief feature
- No login, no server, no dependencies to install

---

## Built for

GCC and IT services HR teams managing:
- Bench utilisation and billability risk
- Skill-to-requirement matching across accounts
- Workforce visibility for account managers and leadership
- Performance and appraisal data in one view

---

## Tech

`HTML` `JavaScript` `CSS` `Claude API` `localStorage`

---

## Note

This is a demo version with anonymised sample data. Built as part of an HR AI tools portfolio — see [github.com/Sukeshni31](https://github.com/Sukeshni31) for the full suite.
