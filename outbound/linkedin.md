# Outbound — LinkedIn

Two-surface template. Use **Path A** (connection request + first message) OR **Path B** (Sales Nav / Premium InMail) — never both. Pair with `email.md` for a multi-channel sequence; follow up with `proposal.pdf` if the prospect asks for an artifact.

---

## Path A — Connection request + first message (free / Basic LinkedIn)

### Step 1 · Connection request note (~200 chars)

**Variant 1 — Curiosity hook (recommended)**

> [Name] — curious if you've cracked how to measure whether AI training actually moves the needle. I just built that for ToTheNew alongside the curriculum. Would value your read.

**Variant 2 — Direct**

> [Name] — I just designed an AI-engineering training for ToTheNew (10 days, curriculum + observability dashboard). The structure is worth ~20 min of your time even if you don't run it. Open to connecting?

### Step 2 · First message (send after they accept)

> Thanks for connecting, [Name].
>
> Quick context on why I reached out: I just shipped a 10-day AI-engineering engagement at ToTheNew that I think is a different shape from what most services firms are running. Two pieces, deliberately coupled:
>
> 1) Curriculum — Hands-on, Claude Code + Cursor. Built for engineers who already use Copilot casually and need to become productive with agentic workflows on brownfield codebases. Not "intro to AI."
>
> 2) Observability dashboard — Measures whether the training moved the needle. DORA cycle time, CLAUDE.md coverage, AI-touch ratio on bugs, post-merge bug rate. The half nobody else ships.
>
> Worth a 30-minute walkthrough? No pitch — just sharing the framework. If something resonates, we can take it from there.

---

## Path B — Sales Navigator / Premium InMail

### Subject line — pick one

- How I'd train your engineers on AI — and prove it worked
- A different AI-upskilling shape, working at ToTheNew right now
- Curriculum + observability — what I built for ToTheNew

### Body

> [Name] — short InMail since I imagine your inbox is busy.
>
> I just shipped a 10-day AI-engineering engagement at ToTheNew that I think is a different shape from what most services firms are running. Two pieces, deliberately coupled:
>
> 1) Curriculum — Hands-on, Claude Code + Cursor. Built for engineers who already use Copilot casually and need to become productive with agentic workflows on brownfield codebases. Not "intro to AI."
>
> 2) Observability dashboard — DORA cycle time, CLAUDE.md coverage, AI-touch ratio on bugs, post-merge bug rate. Measures whether the training moved the needle. The half nobody else ships.
>
> Worth a 30-minute walkthrough? No pitch — just sharing the framework. If something resonates, we can take it from there.

---

## Notes for the sales team

- **Path A vs Path B.** Connection-request route is free but takes 1–3 days for acceptance + reply. InMail is immediate but costs Sales Nav seats. Run Path A by default; reserve Path B for prospects you're willing to spend a seat-month on.
- **Never both.** Don't InMail someone after they ignored a connection request (or vice versa). It reads as desperate and services VPs talk.
- **Plain text only.** LinkedIn does not render markdown bold or italics — `**bold**` shows as literal `**bold**`. The template above uses em-dashes and numbered structure for plain-text emphasis. Paste exactly as written.
- **Personalize in 30 seconds.** Skim the prospect's last 2 posts. If they've recently talked about AI / dev productivity / engineering hiring, reference it in one line above your message. LinkedIn is a relationship surface, not just a channel — manufactured personalization is worse than none.
- **Mobile read.** Most LinkedIn messages get opened on mobile. Keep paragraphs to 2–3 sentences. Numbered lists render fine; tables don't.
- **Follow-up cadence.** If no acceptance within 7 days on a connection request, walk away — it's a no. If accepted but no reply to the first message, send a one-line bump after 5 working days: *"[Name] — circling back, still curious if this might be a fit."* No more after that.
- **TTN as proof.** If your prospect's firm competes with or is adjacent to ToTheNew (digital engineering / services in India), the name carries weight; lead with it. If they're at a Big Four or US-headquartered firm where TTN isn't a household name, swap for "a digital-engineering firm of similar profile" in the connection note (Variant 2 lends itself to this).

---

*Source repo: this file lives alongside the canonical pre-engagement framework at `/Users/lexai/Documents/tothenew/index.html` and the email template at `outbound/email.md`. Sync the language across all three when the framework evolves.*
