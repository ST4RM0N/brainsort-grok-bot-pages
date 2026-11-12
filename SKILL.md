---
name: brainsort
description: "Turn the Better Builds / NEXUS Prime desk workflow into living Grok Bot pages. Use when the user says turn my workflow into a skill, publish brainsort, brainsort grok-bot-pages, Better Builds desk, or needs a durable dashboard for registry health, MVP progress, harbor order, and reverse-entropy healing."
type: workflow
lifecycle: active
---

# Brainsort — Workflow to Grok Bot Page

Convert the operator's entire Better Builds desk workflow (live NEXUS health, registry snapshot, MVP tiles, harbor order, bookmark themes, reverse-entropy healing) into a durable, keep-current Grok Bot page.

Live source of truth: https://nexus-prime-os.connorpattern.workers.dev/#/home

## Core Workflow

1. **Fetch live state** — Open the cockpit. Record operator_access, version hash + cut time, ops_store ms, ll_cockpit ms, round-trip. Capture registry (built/planned/potential of total), MVP x/13, Tide vs ledger, board deck / building / review / shipped counts. Note next module (currently S4 NP-MEMORY-OPS). Do not freeze timings; they move.

2. **Map harbor and bookmarks** — Record current harbor order (08b Connor, 07 Kurt, 06 Connor). Map bookmark themes: knowledge library → S8 Ghost; graph → S1/S5; creator craft has no node; agent proof → S11 Ghost; audience → step 07. Four of five sit after S4. Seen is device-only, not approval. Pause is this device only. Partner cannot record L3. S5 tile stays Ghost (15 Oct note, no session id).

3. **Produce the page brief** — Output a clean copy-paste block for Grok Bot:

```
=== COPY START ===
Make a page titled "Better Builds Desk — Brainsort" that shows the live NEXUS cockpit health.

Sections:
- Headline strip: version, registry built/planned/potential of total, MVP x/13, Tide %, ledger, board status counts. Source every number from the live site. Mark anything unverified as missing.
- API health: operator_access, ops_store ms, ll_cockpit ms (note that timings move; do not freeze).
- Next and harbor: current next (S4 NP-MEMORY-OPS), harbor order with owners.
- Bookmark theme map and constraints (Seen device-only, Pause device-only, Partner cannot record L3, S5 Ghost).
- Healing queue: highest-leverage reverse-entropy moves (correct stale counts, surface ghosts, clarify blocked paths).
- Last updated timestamp + source link.

If a number is missing or out of date, say so instead of guessing.
=== COPY END ===
```

4. **Keep current** — After the page exists, supply the update phrase: "Update the existing Better Builds Desk — Brainsort page with the latest live counts from https://nexus-prime-os.connorpattern.workers.dev/#/home. Keep the same page. Mark unverifiable items as missing. Refresh Last updated."

## Anti-Patterns

- Do not invent node IDs, counts, or statuses.
- Do not create a new page when an update is requested.
- Do not freeze live timings.
- Prefer reverse-entropy: correct drift, surface ghosts, reduce operator decision entropy.

## References

See existing grok-bot-pages skill for full page templates. Prefer live browser extraction over memory.