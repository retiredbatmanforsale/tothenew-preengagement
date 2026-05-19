# Outbound Email — VP of Engineering, Tech Services

A peer-to-peer cold/warm email. Goal is not to pitch — it's to make the VP recognize a pain pattern, feel heard, and reply. The substance lives in `proposal.pdf`, which only gets sent if the VP asks for it.

---

## Subject line — pick one (A/B if you have volume)

- are your engineers actually using AI?
- an AI-rollout observation from the trenches
- what your AI rollout probably looks like from the ground

Lowercase is deliberate — reads less like a marketing campaign and more like a peer thinking out loud. If your prospect's company tone is formal, capitalize.

## Body

> Hi [Name],
>
> Quick observation, not a pitch.
>
> Every services-firm engineering org I sit with has an AI rollout on paper — Copilot licenses, a "best practices" doc, a workshop or two last quarter. But the actual usage pattern looks like this: a few senior engineers who like it use it deeply, most mid-level engineers use it for autocomplete, and juniors are either over-relying on it or quietly avoiding it.
>
> And nobody — not the managers, not the VP — has a real picture of which bucket their org sits in. So when a client asks "what's your AI productivity story," the answer ends up anecdotal.
>
> I've been working on a different frame for this — instrument the org first, then teach what the instrumentation says is actually missing. Piloting it now with a digital engineering firm; the data from the first cohort has been interesting enough that I wanted to share the shape.
>
> Curious whether this rings true for [Company]. If it does, I'd love to compare notes — what's working at your end, what's not.
>
> Best,
> [Sender]

---

## Notes for the sales team

### What this email is doing (and what it's not)

This is **not** a proposal email. It does three things, in order:
1. **Names the pain pattern** with enough specificity that the VP recognizes their own org in it.
2. **Suggests a different angle of thinking** — "instrument first, then teach" — without explaining the full mechanic. Curiosity, not closure.
3. **Asks for a peer exchange**, not a meeting.

Things it deliberately does NOT contain:
- Day counts, hour counts, tool names (Claude Code, Cursor, etc.)
- Metric names (DORA, CLAUDE.md, AI-touch ratio)
- A "30-min call, no pitch" CTA
- Mentions of `proposal.pdf`

All of that lives in `proposal.pdf` and gets sent **only if the VP replies asking for more**. Front-loading the detail kills the email's tone.

### Cold vs warm fork

- **Cold.** Send as written. The "Quick observation, not a pitch" opener is calibrated specifically for inbox scanning — it disarms.
- **Warm** (mutual connection, shared event, replied to one of your posts). Replace the opening with one line referencing the warm context, then drop into the "Every services-firm" paragraph: *"[Mutual] mentioned you've been thinking about this — wanted to share an observation."*

### Personalize in 30 seconds (or skip)

Glance at the prospect's last 2–3 LinkedIn posts. Two patterns to look for:
- They've posted about AI / dev productivity / hiring → reference it in one line above the body: *"Saw your post on X — wanted to share something adjacent."*
- They've posted about delivery pressure / client demands → use it as the hook instead of the generic "every services-firm" opener.

If nothing obvious turns up, **send as-is**. Manufactured personalization ("loved your post about leadership!") reads worse than no personalization at all.

### When to name ToTheNew by name

The current draft says "a digital engineering firm." Two cases for swapping in "ToTheNew" by name:
- **The prospect competes with or is adjacent to TTN** (digital engineering, India-headquartered, similar client mix). Naming TTN adds peer-credibility.
- **You have a mutual connection at TTN** and have permission to drop the name.

Otherwise keep it abstract — naming the wrong client to the wrong reader can read as either "showing off" or "I have one engagement and I'm milking it."

### Follow-up cadence

- **Day 4** — one-line bump: *"Circling back on this — curious if the pattern rings true at [Company]."* Same email thread, no new subject line.
- **Day 10** — second bump with optional attachment: *"Last bump on this one. If a written shape is more useful than a back-and-forth, attaching a short proposal."* Attach `proposal.pdf` here, not before.
- **No third bump.** Services VPs talk to each other. Three is the line between "thoughtful" and "vendor."

### If they reply

- **"Yes this rings true, tell me more."** → Reply with 3–4 specific sentences about the instrumentation-first frame, then offer a 30-min call. Send `proposal.pdf` only if they ask for "something written up."
- **"Interesting — what does your engagement look like?"** → They're asking for the proposal. Send `proposal.pdf` with a one-line note: *"Here's the shape — happy to talk through any of it on a call."*
- **"Not for us right now."** → One-line gracious close, ask if they'd be open to a check-in in 6 months. Most "not now" replies become "yes" in 3–9 months when the client pressure ramps.

---

*Source repo: this file sits alongside the LinkedIn template (`linkedin.md`) and the proposal PDF (`proposal.pdf`). When the underlying engagement shape evolves, keep all three in sync.*
