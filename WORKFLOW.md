# WORKFLOW — hub and spokes

**This chat is the hub (brainchild).** Strategy, loose thoughts, decisions, course corrections.
Spoke chats do the actual labor. Each spoke starts by pasting `BRIEF.md`.

Why: a spoke chat with one job stays fast and cheap. The hub holds the thinking. The repo is the
shared memory between them, so nothing gets lost when a chat ends.

---

## The spokes

| Spoke | Job | Cadence | Runs from phone? |
|---|---|---|---|
| **Daily sweep** | Find new postings (Indeed/LinkedIn/district/hospital/state job boards). Output: a short ranked list w/ apply-or-skip calls. | Daily, morning | ✅ yes |
| **Tailor & apply** | Take one posting → tailored resume + cover note → ready to submit. | Per application | ⚠️ review at home |
| **Networking / warm channels** | Recruiter follow-ups, LinkedIn outreach, referrals, alumni, RH consultants. **Highest leverage.** | 2–3×/week | ✅ yes |
| **CalCareers** | Exams, eligibility lists, state applications (STD 678). Slow burn, background bet. | Weekly | ⚠️ needs focus |
| **Proof / real users** | Get Job Radar + Lighthouse in front of real people; log feedback. | Weekends | ❌ evenings |
| **Skill gaps** | SQL mainly (near-universal analyst screen, and not something I practice). | 20–30 min/day | ✅ yes |

---

## Daily rhythm (fits the school day)

**Morning (before 8:15)** — open the Daily Sweep spoke, ask for today's list.

**During work (8:15–2:45, low engagement)** — phone work, small chunks:
- Skim the sweep list, mark which to pursue
- Fire off voice-to-text asks ("tailor me for this one," "draft a follow-up to X")
- Send one networking message
- 20 min of SQL

**Evening (home)** — the heavy lifting:
- Review + actually submit applications
- Interview prep
- Proof work (weekends mostly)

**Rule:** don't try to do heavy judgment work during the school day. Use those hours for *volume
and queueing*; use evenings for *decisions and submissions*.

---

## Priority order, honestly

Ranked by expected payoff on a **3-month** clock:

1. **Networking / warm channels** — Brooke got me to final two; a portal never has. Cold-apply
   yield has been poor. This is the diagnosed gap: not enough people, not enough exposure,
   not knowing when to play my cards.
2. **Targeted applications** — fewer, better, tailored. Districts, healthcare, state, MSPs,
   staffing firms. Contract-to-hire counts.
3. **Skill gap: SQL** — cheap, daily, unlocks the analyst lane which is more attainable than SWE.
4. **CalCareers** — real but slow (months of latency). Background bet, not the primary plan.
   Worth doing because the exam is cheap to redo and I previously ranked **1 in Data Analytics**.
5. **Proof / real users** — matters for the dev/data pivot and for interview answers, but won't
   land a job inside 3 months by itself.

---

## Shared state (the repo)

- `search/applications.csv` — every application, status, next action. **Single source of pipeline truth.**
- `profile/facts.md` — verified facts. Nothing goes on a resume unless it traces here.
- `profile/claims-to-earn.md` — things I want to say but can't defend yet.
- `proof/feedback-log.md` — real user feedback as it comes in.
- `sources.md` — market data + how much each figure can be trusted.

**When a spoke chat produces something durable** (a new lead, an application sent, a contact made,
a real user), it goes in the repo. That's how the hub stays current without re-reading everything.
