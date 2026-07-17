# Production workflow

The point of this document: content only compounds if it's actually sustainable to produce. This defines a repeatable pipeline, not a one-time content push.

## The pipeline

```
1. SOURCE  →  2. DRAFT  →  3. VOICE QA  →  4. PUBLISH  →  5. REPURPOSE
```

### 1. Source (15 minutes, Monday)

- Scan LinkedIn's own job-alert/network feed (already active on the HireHax inbox) plus two or three biotech/diagnostics funding or M&A trackers for Signal-pillar material.
- Note anything from client/candidate conversations that week that could become (anonymized, permissioned) case-study material or a principle-post scene, without ever naming a real client or breaching confidentiality.
- Drop raw notes into that week's row in `02-content-calendar.md`. Don't draft yet, just capture the raw fact.

### 2. Draft (30-45 minutes per post)

- Pick the template matching the day's pillar from `templates/`.
- Draft directly against the skeleton. Don't start from a blank page: start from the template's skeleton and the worked example next to it.
- If using Claude or another AI assistant to accelerate drafting, use the system prompt in §3 below rather than a generic "write me a LinkedIn post" request. The voice rules are specific enough that generic prompting will produce off-brand output.

### 3. Voice QA (5 minutes per post, non-negotiable)

Run every draft through the checklist at the bottom of `01-voice-and-style.md` before it goes anywhere near "publish." This step is what keeps the system from drifting back toward generic recruiting-agency content over time, which is the single most likely failure mode here given how much LinkedIn content in this space already sounds like that.

### 4. Publish

- LinkedIn: personal profile, not a company page.
- Newsletter: website first, then distribute the link via LinkedIn and email, per the existing internal decision (July 9 notes).
- Update status in `02-content-calendar.md` to `[x]`.

### 5. Repurpose (monthly, not per-post)

- At month end, pull that month's Signal posts into the newsletter's digest section (`templates/newsletter-monthly.md`).
- Pick the single strongest thought-leadership or principle post and expand it to 400-600 words for the newsletter's featured piece.
- Mine the deck and brand book periodically for material that hasn't been turned into a post yet. Both are already-approved copy; a slow content month is a good excuse to adapt an untouched section rather than force a weak new idea.

## §3. AI-assisted drafting prompt

If drafting with Claude (or similar), don't ask for "a LinkedIn post about X." Use something closer to this, adapted per pillar:

```
You are drafting a LinkedIn post for HireHax, a boutique executive search and
leadership advisory firm for life sciences (biotech, diagnostics, clinical-stage
scale-ups), founded by Nikolay Dimitrov (20 years inside Amgen, Vertex, and
Menarini Diagnostics).

Voice rules, all mandatory:
- Register is boardroom, not marketing: plain, declarative, confident, like a
  strategy-consulting deliverable, not an agency pitch.
- Lead with the point. One idea per sentence. Favour verbs over adjectives.
- State consequences as logic, not fear. Confident, never alarmist or hype-driven.
- Take a defensible, slightly contrarian position. A point of view is the product.
- No em dashes, en dashes, or hyphens joining clauses, anywhere, ever. Full
  sentences instead.
- No emoji. No exclamation marks.
- Never use: synergy, world-class, game-changing, rockstar, ninja, unlock your
  potential, cutting-edge, passionate, revolutionary, leverage (as a verb),
  "in today's fast-paced world."
- Every claim needs a number, a name (anonymized if needed), a timeframe, or an
  explicit "unconfirmed" label. Never state unverified data as fact.

Pillar: [Signal / Search as Architecture / Org & Leadership Design /
Future-Ready / Operating Principles]
Template to follow: [paste the relevant skeleton from templates/]
Source material: [the real fact, scene, or principle this post is built from]

Draft one version, 80-180 words depending on pillar. Then self-check it against
every rule above and flag anything you're unsure about rather than silently
softening the voice rules.
```

Treat the output as a first draft, not a final one. Step 3 (Voice QA) still applies to every AI-assisted draft, no exceptions, since the most common failure mode of AI drafting is exactly the generic-marketing register this brand is explicitly built to avoid.

## What "sustainable" means here

Three posts a week plus a monthly newsletter is roughly 2.5 to 3 hours a week once the system is running (15 minutes sourcing, three drafts at 30-45 minutes, QA baked into drafting, newsletter assembly at month end from material that already exists). If that stops being sustainable, cut Friday before cutting Monday: Signal posts are cheapest to produce and hardest to fake reputationally if they stop, since consistency is the entire point of that pillar.
