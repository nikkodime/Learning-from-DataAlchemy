# Production workflow

The point of this document: the knowledge base already has voice, format, and 22 scripts. What it didn't have is a repeatable pipeline that turns the topic bank into shot, published, cross-platform content on a sustainable cadence without silently repeating old topics. This closes that gap.

## The pipeline

```
1. SELECT  →  2. SCRIPT  →  3. VOICE QA  →  4. FILM  →  5. ADAPT  →  6. PUBLISH  →  7. TRACK
```

### 1. Select

- Open `02-content-bank.md`, find the next two `AVAILABLE` items per `03-content-calendar.md`'s rotation rule (slot 1 from Pillar A/B, slot 2 rotating C-F).
- If nothing in the due pillar is `AVAILABLE`, that pillar needs new topic-bank ideas before scripting continues — don't default to repeating a `DEVELOPED` item just to fill the slot.

### 2. Script

- Use `templates/video-script-master.md` — the knowledge base's own "Default output template." Fill in Audience, Pillar, and Central truth first; those constrain everything after.
- Write the spoken script before any platform copy. Everything downstream adapts from it.
- If drafting with Claude or another AI assistant, use the system prompt in §3 below rather than a generic "write me a post about X" request — the voice is specific enough that generic prompting drifts back toward generic LinkedIn-guru tone.

### 3. Voice QA (non-negotiable, before filming)

Run the script through the checklist at the bottom of `01-voice-and-style.md`:
- Hook survives with zero context in three seconds.
- Follows the five-beat structure.
- Names the uncomfortable truth directly.
- No HR jargon, generic inspiration, listicle filler, or process-first advice.
- Doesn't accidentally duplicate a `DEVELOPED` item in `02-content-bank.md`.

This is the step that keeps the account sounding like Nikko and not like generic recruiting-agency LinkedIn content, which per the brand's own positioning is exactly what it's trying not to be.

### 4. Film

Per Section 5 of the knowledge base:
- Default to a strong talking-head performance, 45-90 seconds, 9:16 with a safe LinkedIn crop.
- Only 5-6 B-roll clips as emphasis, not a full B-roll video.
- Hook must land within the first three seconds on camera, not just on paper.
- Build in a visual or verbal pattern break around the educational shift beat.
- Minimal on-screen text: hook, the three-part framework (if the script has one), or the final line only.
- B-roll bank to draw from: boardrooms, rewritten documents, unanswered emails, clocks and delays, leaders working through decisions, candidate communication, contrasting calm/crisis environments. Premium and real, never generic HR stock footage.

### 5. Adapt

Generate every platform version from the filmed/final script using `templates/platform-adaptation-cheatsheet.md`. Do this the same session as filming, not days later — see `00-strategy.md` §7 on why staggered adaptation weakens the effect.

### 6. Publish

- LinkedIn goes first (primary platform, deepest context).
- Other platforms follow within 24-48 hours, same underlying script, adapted per the cheatsheet.
- Update `03-content-calendar.md` status to `[x]` and move the item from `AVAILABLE` to a dated `SHOT` line in `02-content-bank.md`.

### 7. Track (monthly, not per-post)

- Which pillar produced qualified inbound conversations (per `00-strategy.md` §8), not just raw engagement.
- Feed that back into the next month's calendar: lean slightly toward what's converting, without abandoning the rotation rule entirely — a system that only ever does the last thing that worked stops being a system.

## §3. AI-assisted drafting prompt

```
You are drafting a HireHax video script using Nikko Dimitrov's established
voice: direct, sharp, candid, slightly rebellious but credible, truthful and
uncomfortable, cynical where useful but never merely negative, critical but
solutions-oriented, commercial and executive-level. Truth bombs, not
motivational filler. Gary Vee energy without hustle-culture platitudes or
hype.

The content exposes leadership and organisational causes, not recruitment
process mechanics. Never: HR jargon, generic inspiration, listicle filler,
process-first advice. Never soften the central truth until the piece becomes
forgettable.

Structure (mandatory, five beats):
1. Hook in the first three seconds — an uncomfortable truth or surprising
   contrast. Must work with zero context.
2. Call-out / reflection — the behaviour the audience recognises in itself.
3. Truth or reframing — what's actually happening underneath.
4. Educational shift — what a strong leader does instead, concretely.
5. Ending reflection / punchline — a line that earns the pause. Never end on
   the complaint alone.

Length: 45-90 seconds spoken (roughly 100-220 words).

Pillar: [A Hiring & Talent Decisions / B Leadership & Culture /
C Scaling & Org Design / D Executive Career & Onboarding /
E AI & Future-Ready Leadership / F Founder Story]
Audience: [specific primary-audience segment from 00-strategy.md §3]
Central truth: [one sentence]
Topic: [the specific item from 02-content-bank.md]

Output using the full template in templates/video-script-master.md: title,
audience, pillar, central truth, three hook options, final spoken script,
LinkedIn caption, IG/TikTok caption, YouTube Shorts title + description,
Threads/X version, pinned comment, 5-6 B-roll cues.

Before finalizing, self-check against every rule above and flag anything
uncertain rather than silently softening the voice.
```

Treat the output as a strong first draft. Step 3 (Voice QA) still applies to every AI-assisted script, no exceptions.

## What "sustainable" means here

Two scripts a week, each fully adapted across six platform formats, is roughly 3-4 hours a week once the pipeline is running: 20 minutes selecting and outlining, 45-60 minutes scripting and QA per piece, filming batched (film both weekly scripts in one sitting where possible), adaptation done same-session per script. If that stops being sustainable, drop to one script a week rather than skipping weeks entirely — consistency is what this format's compounding effect depends on.
