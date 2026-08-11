# BUILD REAL PROOF — the core workstream

> *"A tool people use" > "a thing I made."*

This is the lane you correctly identified as the real blocker. Everything here exists to convert
`profile/claims-to-earn.md` → `profile/facts.md`, honestly.

**The market backs your instinct.** A 2025 CodePath survey of 200+ engineering leaders found
**side projects / portfolios were the #1 hiring criterion (38%)** — above internship experience (35%)
and public code portfolios (34%), while degree/academic focus came in at 23%. In 2026 hiring tilts
toward **proof over promise**: links, demos, metrics.
Your CS degree is table-stakes now. **The proof is the differentiator.**

---

## Step 0 — Instrument BEFORE you promote (do this first, it's ~1 hour)

Promoting an uninstrumented tool wastes the traffic. You get one good launch per channel — if you
can't measure it, the users arrive, leave, and **you still can't prove anything.**

| Need | Tool | Why |
|---|---|---|
| Usage analytics | **GoatCounter** (or Plausible) | Cookieless, tracks no unique identifiers, **no GDPR banner needed**, ~1KB script, free non-commercial tier. **Returning-visitor + retention curves are the real proof** — not pageviews. |
| Feedback capture | **Tally** | Free forever, unlimited submissions. One form: "what were you trying to do / what broke?" |
| Feature requests | **Canny** (optional) | Public, auditable, votable board = hard-to-fake proof. ⚠️ free tier caps ~25 tracked users. |
| Session replay | **Microsoft Clarity** (optional) | Free heatmaps/replays — shows *where users struggle*, which becomes your "iterated on feedback" story. |

**Also:** keep a `proof/feedback-log.md`. Every launch-thread comment, every email, every DM — saved
with date and source. Launch threads (Show HN / Product Hunt / Reddit) are **public, timestamped
evidence** that real humans engaged with your work. That log *is* portfolio material.

---

## Step 1 — The fastest 0→1: people you already know

**Do this before any public launch.** The 0→any-users jump is the single biggest credibility gain,
and you have warm access right now:

- **Your STEM tutoring students** and **SCC classmates** → Job Radar is *literally built for them.*
- **Natomas USD coworkers** → they job-hunt too; district staff turn over constantly.
- **General Assembly cohort** → job-seekers by definition, and they'll give real feedback.

Ask plainly: *"I built a job-search tool. Would you use it for a week and tell me what's broken?"*
**8 real users you can name and quote beats 500 anonymous pageviews** for interview purposes.

> This alone unlocks: *"Piloted Job Radar with 8 job-seekers over 2 weeks; shipped 3 changes from
> their feedback."* That sentence is worth more than either project's entire feature list.

---

## Step 2 — Channel strategy, by project

### 🩺 Lighthouse Open Health — *the higher-yield project. Prioritize it.*

Open + health-data + self-hostable is an unusually good fit for communities that **welcome** makers:

| Channel | Members / reach | Rules — read carefully | Realistic yield |
|---|---|---|---|
| **r/selfhosted** | Large, very active | Self-promo **allowed in context**: lead with value, open-source strongly preferred, **provide GitHub link + Docker/compose + easy local deploy**, and be responsive in comments. Promo-only posts removed. | **Highest-yield channel available to you.** Cited as a top single source of stars/users in month one — *dozens* of stars + a meaningful chunk of first users. |
| **r/QuantifiedSelf** | ~89,400 | Community is explicitly **makers + users** of self-tracking tools. Frame as *"I built this to track X, feedback wanted"* — not an ad. | Niche but highly targeted; a few to low-tens of genuine signups. |
| **Open Humans** | 11,982 members, 54 tools | **Purpose-built** for exactly this — registering a project/activity is the intended use, not a rules violation. Be transparent about data handling. | Small, high-trust, research-oriented. Registered projects are **platform-visible and hard to fake** = excellent proof. |
| **r/opensource** | ~210k | Must be genuinely open source; substantive post (what/license/repo), not marketing. | Moderate — dozens of visitors, a handful of stars. |
| **quantifiedself.com + QS Slack** | Intl. community | Maker-friendly by design; favors a genuine build/learning story. | Low volume, very high relevance — **best for testimonials.** |

**→ Make Lighthouse trivially self-hostable (Docker + compose + a real README) before posting to
r/selfhosted.** That single prep step is what converts that post from ignored to high-yield.

### 🎯 Job Radar — *harder. The job subs are hostile to promo.*

Be realistic: **r/jobs, r/cscareerquestions, r/recruitinghell, r/resumes all restrict or ban tool
links**, often behind mod approval or weekly threads. A bare link gets removed and can get you banned.

**Play it this way instead:**
- **Value-first commenting.** Answer real questions in advice threads; mention the tool only when it
  genuinely answers the question asked. Expect *a handful* of clicks — but they're high-intent.
- **r/SideProject (~180k)** — self-promo explicitly welcome, **but must show the actual working
  product** (no waitlist / email-gate). Audience is fellow builders → great for feedback + testers.
- **r/roastmystartup (~50k)** — post ~1–2×/month for blunt critique. Feedback, not acquisition.
- **Job-seeker Discords** (e.g. **LayoffWatch**, 10,400+ displaced tech workers, private Slack/Discord)
  — small but **extremely high-intent**. Become an active member first, then share in the
  #resources/#tools channel. **Ask a mod before posting.** Cold promo = removed.

### 🚀 Cross-cutting launches (when the product is genuinely ready)

- **Show HN** — ⚠️ **Bimodal: ~90% of Show HN posts get little or no attention.** Front page = 5,000–30,000
  visitors in 24h, but consumer conversion is often **<1%** (one documented case: 45 signups from
  ~5,000 visits). Hard rules: must be something people can **actually try/run/inspect** (no landing
  pages, waitlists, or signup gates), prefix `Show HN:`, **never solicit upvotes** (bannable), and
  **do not use an LLM to write or edit the post** — HN readers react badly to AI-sounding text.
  **Write it yourself, in your own voice.**
- **Product Hunt** — realistic for a solo builder with no audience: **~20–60 signups** (100–300
  visitors). Featured launches reach 1,000–5,000 visitors / 10–150 signups. **The one hard rule:
  never ask for upvotes** — ask people to "check it out and leave honest feedback." Self-hunting is
  fine. No voting rings or upvote-exchange groups (products get delisted).
- **Indie Hackers** — engagement has cooled since its 2019–21 peak and product discovery is weak.
  **Use it for feedback, testimonials, and Milestones — not acquisition.**

---

## The universal rule that keeps you un-banned

Reddit's **9:1 / 90-10 guideline**: no more than ~1 in 10 of your submissions should be your own
content. Per-subreddit rules **override** this and vary widely. Reddiquette puts it well:

> *"A redditor with a website" is fine. "A website with a Reddit account" is not.*

**Always check the live sidebar before posting** — the research could not verify verbatim rule text
for most subs (Reddit was egress-blocked), so treat every rule summary here as *"verify on-site first."*

---

## What actually counts as defensible proof

Ranked by how well it survives *"show me"* in an interview:

1. **Named testimonials** — first name + role + context, ideally linkable to their public post. Harvest
   these from launch comment threads.
2. **Returning-visitor / retention curves** from GoatCounter or Plausible — proves *repeat* use, not
   just a traffic spike.
3. **GitHub stars, forks, and especially issues/PRs** — open issues prove real people are *using and
   probing* the tool. (Realistic: the first ~100–300 stars typically come from your own network before
   organic conversion kicks in — that's normal, not cheating.)
4. **A public feedback board** with real votes/comments — auditable.
5. **Registered projects/connected accounts on Open Humans** — platform-visible, hard to fake.
6. **Your feedback log** — saved emails, DMs, form submissions showing real questions and use cases.

---

## Sequenced plan (the order matters)

| # | Action | Unlocks |
|---|---|---|
| 1 | Add GoatCounter + a Tally feedback form to **both** projects | Ability to measure anything at all |
| 2 | Hand Job Radar to **8–10 tutoring students / classmates / coworkers** | **The 0→1 jump.** "Piloted with N users" |
| 3 | Ship ≥1 change *because a user asked* — log it | *"Iterated based on user feedback"* — a real engineering story |
| 4 | Dockerize Lighthouse + write a real README | Makes the highest-yield channel viable |
| 5 | Post Lighthouse to **r/selfhosted** (value-first), then r/QuantifiedSelf + Open Humans | First organic users + GitHub stars |
| 6 | Job Radar → **r/SideProject** with the working product visible | Testers + blunt feedback |
| 7 | Collect 2–3 **named testimonials** from the above | Quotable proof |
| 8 | *Only when genuinely solid:* Show HN / Product Hunt | Volume — high variance |
| 9 | Move every earned claim → `profile/facts.md`; update résumé bullets | **The whole point** |

**Steps 1–3 are worth more than 5–9 combined**, and you can finish them this week without waiting on
strangers, algorithms, or launch-day luck. Start there.
