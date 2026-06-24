# PeopleLens — HR Intelligence Platform

A browser-based HR intelligence platform built for IT services and GCC environments. Runs entirely in the browser — no backend, no database, no installation.

🔗 **Live Demo:** [sukeshni31.github.io/PeopleLens-Demo](https://sukeshni31.github.io/PeopleLens-Demo/)

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
- Build/Buy/Borrow/Bot analysis integration

---

## How it works

- Single HTML file — all logic, CSS, and UI in one place
- Data loaded via localStorage (paste from Excel or import JSON)
- Claude API powers the AI Intelligence Brief feature
- No login, no server, no dependencies

---

## Built for

GCC and IT services HR teams managing bench utilisation, skill-to-requirement matching, workforce visibility, and appraisal data in one view.

---

## Tech

`HTML` `JavaScript` `CSS` `Claude API` `localStorage`

---

> Demo version with anonymised sample data. Part of an HR AI tools portfolio — [github.com/Sukeshni31](https://github.com/Sukeshni31)
