<div align="center">

# सारथी · Saarthi

**Your charioteer to paid open source.**

[Connect your agent](#start-in-one-step) · [What to ask](#what-to-ask-once-youre-connected) · [Programs](#the-programs) · [Feedback](#this-repo-is-for-feedback)

</div>

---

## What Saarthi is

You're not behind. You're just unaimed.

Saarthi is an AI mentor that lives **inside the AI editor or chat you already use** — not another
dashboard, not another site to log into. You add one endpoint, sign in with GitHub, and then just
ask, in plain English. Saarthi reads your real GitHub history, points you at the paid mentorship
projects that genuinely fit the skills you have, and shows its evidence every time. Never a guess.

Never written a line of open source? That's exactly who this is for.

In the Gita, Arjuna is the warrior — Krishna is his charioteer. He doesn't fight the battle. He holds
the reins, steadies the horses, and aims Arjuna at the right target. **You're still the one who
ships the code.** Saarthi just makes sure you're aimed at something worth hitting.

## What you get

Not a feature list — the outcome:

- **Aimed at the right project.** No more spray-and-pray across fifty orgs. Every project ranked
  *Ready*, *Short ramp*, or *Stretch* against the skills you actually have, with a straight answer
  on the effort.
- **A first merged PR.** Real beginner issues in the real upstream repo, plus how to talk to
  maintainers without burning the first impression — so you apply with merged proof, not promises.
- **A proposal that holds up.** An outline, accepted samples to learn the shape from, a
  project-tailored resume, and a readiness score that tells you the truth instead of what you want
  to hear.

Mentors judge your contributions first, then your proposal. Saarthi's whole job is to get both ready
before the window closes.

## Start in one step

Add Saarthi to your agent as an MCP server. **The endpoint is:**

```
https://saarthi-p03q.onrender.com/mcp
```

That's the only thing you need to paste. Below, **"the endpoint"** means exactly that URL. Signing
in with GitHub happens automatically in your browser the first time your agent connects — there's no
separate account to create.

| Your client | What to do |
| --- | --- |
| **Antigravity** — free, no subscription | Agent panel → **⋯** → **Manage MCP Servers** → **View raw config**. Add a `saarthi` server with **`serverUrl`** set to the endpoint, then hit refresh. (Antigravity uses `serverUrl`, not `url`.) |
| **Cursor** | **Settings → MCP → Add new server.** Add a `saarthi` server with **`url`** set to the endpoint. |
| **Codex** | Run `codex mcp add saarthi --url` followed by the endpoint. Then run `/mcp` inside Codex to check it connected. |
| **Claude Code** | Run `claude mcp add --transport http saarthi` followed by the endpoint. Then run `/mcp` to sign in. |
| **Claude Desktop** | **Settings → Connectors → Add custom connector.** Paste the endpoint. |
| **VS Code** | Needs GitHub Copilot with MCP enabled. Add a `saarthi` server of type `http` with the endpoint as its `url`. |
| **Windsurf** | Add a `saarthi` server with **`serverUrl`** set to the endpoint, then reload the MCP list. (Windsurf uses `serverUrl`, not `url`.) |

Any MCP-capable client works — these are just the ones with instructions written down.

Once you're connected, **[finish your profile](https://saarthi-p03q.onrender.com/onboarding)** — it
takes a minute, and it's what makes the recommendations about *you* rather than about nobody.

Stuck on setup? There's a **[full walkthrough](https://saarthi-p03q.onrender.com/guide)**.

## What to ask once you're connected

Speak plain English. Your agent picks the right tool — there are **27** of them, and you never need
to know their names.

Roughly in the order you'll want them:

> **"Am I onboarded? What's missing on my profile?"**

> **"What even is open source, and why should I contribute? What is LFX, and how much is the
> stipend?"**

> **"Recommend 3 LFX projects for my skills. Explain the top one."**

> **"Find me starter issues I could actually finish."**

> **"Make a contribution plan for issue #42 and walk me through the first PR."**

> **"Outline my proposal for this project. Show me accepted samples. Am I ready?"**

Four things worth knowing:

- Saarthi cites its evidence or tells you what's missing. It will never invent mentor approval.
- Copy the *structure* from accepted samples, not the text.
- Ship at least one small PR **before** you submit a proposal. It's the one claim you can't fake.
- A readiness score is feedback, not a prediction. Nobody can predict acceptance, and Saarthi
  won't pretend to.

## The programs

Paid open source is real. That's the whole point.

| Program | Status | What it pays |
| --- | --- | --- |
| **CNCF LFX Mentorship** | **Live in Saarthi** | $1,000 – $6,600 per ~12-week term, PPP-adjusted |
| **C4GT** (India) | Coming next | ₹1,00,000 on successful completion, ~3 months |
| **Google Summer of Code** | Coming next | $750 – $6,600, by project size, PPP-adjusted |

These are educational grants / program stipends — **not** salaries. Every figure comes from the
program's own published policy, **[linked on the site](https://saarthi-p03q.onrender.com/#programs)**.

Today, project ranking and starter issues are live for **CNCF LFX**. C4GT and GSoC are next.

## This repo is for feedback

**The code isn't here.** This repo is the public tracker — issues and feedback only. You already
have a GitHub account (you signed in with it), so feedback goes where it can actually be tracked, in
the open, where you can see what happened to it.

Three ways in:

- 💬 **[Give feedback](https://github.com/jayesh9747/saarthi-community/issues/new?template=feedback.yml)**
  — what worked, what didn't, what confused you. Blunt is more useful than polite. If Saarthi wasted
  your time, say so.
- 🐛 **[Report a bug](https://github.com/jayesh9747/saarthi-community/issues/new?template=bug.yml)**
  — wrong answer, broken tool call, or a setup step that doesn't work.
- ✨ **[Request a feature](https://github.com/jayesh9747/saarthi-community/issues/new?template=feature.yml)**
  — want a program, a tool, or a check that doesn't exist yet? Ask.

For anything you'd rather not put in a public issue — including security reports — email
**jsavaliya.tech@gmail.com**. Please report vulnerabilities privately rather than opening an issue.

> **Issues here are public.** Strip tokens and `Authorization: Bearer …` headers before you paste
> logs.

## Support

Students shouldn't have to pay to find paid work. Saarthi is free for the people it's built for, and
the intention is to keep it that way.

**If you're a student: you owe nothing. Go get the stipend.** The
**[support page](https://saarthi-p03q.onrender.com/support)** is for everyone else — mentors,
maintainers, and orgs who benefit from better-prepared contributors.

The cheapest way to help costs nothing: tell one person who needs this, or file one real bug report.

---

<div align="center">

**You're Arjuna. Saarthi just holds the reins.**

</div>
