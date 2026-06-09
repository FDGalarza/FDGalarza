---
name: github-profile-readme-spec
version: 2.0
date: 2026-06-09
status: active
---

# GitHub Profile README — Design Specification

## Objective

Position Fabricio Galarza's GitHub profile as a Senior Backend Engineer targeting Staff Engineer,
Principal Engineer, Tech Lead, and Senior Backend Engineering roles — at international companies,
SaaS products, fintechs, and remote-first engineering organizations.

The profile must function as a professional credential, not a skills showcase. Every section
must be defensible in a technical interview and credible to a Staff Engineer reading it peer-to-peer.

---

## Target Roles

Senior Backend Engineer · Staff Engineer · Principal Engineer · Tech Lead

## Target Audience

| Audience | What they evaluate | Signal they need |
|---|---|---|
| Technical Recruiter | Level, stack, specialization | Clear title, specific technologies, Senior signal in < 10 seconds |
| Hiring Manager | Depth, ownership, scope | Domain expertise, production experience, business awareness |
| Engineering Manager | Collaboration, leadership, process | Cross-functional language, mentorship, technical direction |
| Staff / Principal Engineer | Real depth, honest claims, intellectual rigor | Specific technical language, trade-off awareness, philosophy |
| Software Architect | System thinking, architecture decisions | System design, data layer depth, distributed systems |

---

## Core Design Rules

1. **Credibility over marketing** — no inflated claims, no buzzwords without substance
2. **Depth over breadth** — fewer technologies, more specialization
3. **Every claim must be interview-defensible** — if it can't be backed up in a technical conversation, it doesn't belong
4. **Prose over bullet lists** — prose signals maturity; excessive bullets signal junior thinking
5. **Production language** — "execution plan analysis", "revenue-critical systems", "without service interruption" — not "I work with databases"
6. **No junior anti-patterns** — no skill meters, no Frontend/Backend splits, no trophy sections, no Top Languages card

---

## Content Architecture

### Section 1 — Header
`# Name` + one-line subtitle with title and 4 core domains (not a laundry list).
Rule: 4 domains maximum. Chosen for: Python (ecosystem), Django (framework depth), PostgreSQL (differentiator), System Design (scope signal).

### Section 2 — Professional Introduction
Two short paragraphs. First paragraph: years, domains, and the "production reality" framing.
Second paragraph: honest breadth signal (Python + PHP ecosystems, enterprise migrations).

**Recruiter read:** Confirms level and specialization immediately.
**Hiring Manager read:** "Production-grade", "business constraints", "hold up over time" = ownership mentality.
**Staff Engineer read:** Honest, specific, no inflation.

### Section 3 — What I'm Working On
Current work described at platform level, not project level. Ends with a learning signal.

**Why this section exists:** Shows active, self-directed initiative. A Senior engineer who is building
something on their own time — and engineering it properly — is a stronger signal than a list of past employers.

### Section 4 — Areas of Specialization
Four domains. Each described in 2-3 sentences using production-grade technical language.
Each domain has a key phrase that signals depth over surface familiarity.

| Domain | Depth signal phrase |
|---|---|
| PostgreSQL & Data Engineering | "SQL is not just a tool — it is a domain" |
| REST API Design | "contracts that evolve without breaking the services and teams that depend on them" |
| System Design | "decisions that compound positively over time" |
| Technical Analysis | "Translating business constraints into sound engineering decisions" |

### Section 5 — Engineering Philosophy
Three first-person principles. This is the primary Staff/Principal differentiator.

Rules for philosophy statements:
- Must be opinion, not description
- Must be grounded in the engineer's actual domain
- Must be defensible in an architecture discussion
- Must not be generic ("I write clean code" is not a philosophy)

### Section 6 — Technical Stack
Badges: primary stack only (Python, Django, DRF, PostgreSQL, Docker, Git).
Additional experience listed as plain text — intentionally de-emphasized.

**Why:** Top Languages card excluded because public repos reflect historical PHP/C# work
that would misrepresent current expertise. Badges for primary stack only avoids the
"technology collector" anti-pattern.

### Section 7 — Featured Project
Structured as a product brief with a table. Shows architecture thinking, not just "I built X."
The phrase "not a prototype" is intentional — it signals engineering rigor.

### Section 8 — Currently Exploring
One horizontal line of topics, no bullets. Signals intellectual direction without inflating claims.
Kept short deliberately — this is forward-looking context, not a credentials section.

### Section 9 — GitHub Activity
One stats card: contributions + commits, private commits counted, no Top Languages.
Excluded: streak counter, trophies, top languages, stars.

### Section 10 — Connect
LinkedIn badge. Closing CTA targeting remote international opportunities explicitly.

---

## International Remote Optimization

The following elements are specifically calibrated for international remote opportunity targeting:

- **English throughout** — no ambiguity for international recruiters
- **"distributed teams building serious backend systems"** — signals remote-readiness and team-level thinking
- **"revenue-critical systems"** — language understood in any engineering organization globally
- **"without service interruption"** — migration experience described at business impact level
- **Philosophy section** — international senior engineering hiring processes weight engineering thinking heavily
- **"cross-functional collaboration"** — maps to how distributed orgs describe teamwork
- **Explicit CTA** — "remote opportunities" stated clearly; many international recruiters filter on this

---

## Anti-Patterns Explicitly Avoided

| Anti-pattern | Reason avoided |
|---|---|
| Top Languages card | Shows PHP/C#/JS from historical repos; misrepresents current expertise |
| Skill progress bars | Subjective, undefendable, junior signal |
| GitHub trophies | Vanity metric with no professional signal |
| Streak counter | Depends on public activity; not meaningful for senior roles |
| Frontend section | Misframes the engineer as a generalist |
| Bootstrap / HTML / CSS icons | Strong junior signal |
| Instagram link | Irrelevant to professional engineering profile |
| "I love coding" language | Signals inexperience |
| Excessive emoji | Reduces professional credibility |
| Long bullet lists of technologies | Technology collector anti-pattern |

---

## Placeholders

| Placeholder | Value |
|---|---|
| GitHub username | `fdgalarza` |
| LinkedIn URL | `https://www.linkedin.com/in/fabricio-galarza-7bb174b9/` |
