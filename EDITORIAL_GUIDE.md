# Tech Edition — Editorial Guide

Create a daily personal technology newspaper called Tech Edition.

Its job is not to report mainstream technology news.

Its job is to explore the edges of computing, software, games, open source, AI agents, hardware, hacking/tinkering, digital preservation, modding, unusual projects, and emerging ideas — including things the reader does not yet know he is interested in.

Think of it as:

Hacker News + GitHub archaeology + modding communities + research labs + old-computer enthusiasm + AI-agent experimentation + interesting engineering blogs

but edited aggressively for signal.

# Core editorial question

Every edition should answer:

> "What interesting things are people building, discovering, experimenting with, reviving, or figuring out?"

Prioritize things that inspire experimentation.

# Major interests

Pay particular attention to:

- AI agents
- Claude
- Claude Code
- Codex
- agent Skills
- plugins
- MCP
- agent orchestration
- multi-agent systems
- agent memory
- context engineering
- evaluation systems
- trustworthy/autonomous agents
- GitHub projects that might inform MAPS_Lean

But do NOT turn this into an AI newsletter.

Also aggressively explore:

- open-source software
- small GitHub projects
- Linux
- Linux Mint
- unusual desktop software
- command-line tools
- automation
- personal software
- self-hosting
- retrocomputing
- emulation
- game engines
- Godot
- small/independent games
- game mechanics
- mods
- modding tools
- source ports
- fan patches
- game preservation
- reverse engineering
- procedural systems
- experimental interfaces
- e-ink devices
- custom firmware
- unusual handhelds
- old hardware given new purposes
- hardware hacking
- repairability
- home networking
- small electronics projects
- visualization
- information organization
- knowledge systems
- digital archives
- typography
- UI/UX
- interaction design
- obscure programming experiments
- software history

# Discovery is a primary objective

Do not merely search known interests.

Every edition should deliberately investigate adjacent areas.

Look for:

> "If this person likes X, what is something two steps away from X that he may never think to search for?"

Examples:

Game modding
→ reverse engineering
→ binary archaeology

AI agents
→ distributed systems
→ fault-tolerant workflow research

E-ink readers
→ low-power computing
→ ambient information displays

Retro games
→ preservation
→ source reconstruction
→ decompilation projects

Personal knowledge systems
→ information retrieval
→ cognitive tools
→ human-computer interaction research

Godot
→ simulation research
→ procedural animation
→ autonomous game characters

Do this continuously.

# Sources

Search broadly.

GitHub should be a major source, but not the only one.

Use sources such as:

- GitHub repositories
- GitHub releases
- GitHub Discussions
- developer blogs
- engineering blogs
- research papers
- arXiv where appropriate
- Hacker News
- Lobsters
- relevant Reddit communities when useful for discovering grassroots projects
- itch.io
- ModDB
- Nexus Mods
- game-development communities
- Linux communities
- retrocomputing communities
- Internet Archive projects
- independent personal websites
- university labs
- technical conference material

Favor original project pages over aggregation articles.

# Recency

Include new developments, but do not become obsessed with "today."

A six-month-old obscure project that the reader has never encountered may be more valuable than today's tenth AI funding announcement.

Use three discovery horizons:

### New
Things happening now.

### Emerging
Projects or ideas gaining momentum over the past several months.

### Unearthed
Older projects, papers, tools, techniques, games, or websites worth discovering.

# Edition structure

## Lead Stories

3–5 technically interesting developments worth understanding.

Explain:
- what it is
- what problem it solves
- why it is interesting
- whether it appears mature or experimental
- who would actually benefit from it

## GitHub Finds

Find several repositories.

Do NOT simply use stars as a ranking mechanism.

Actively search for:
- low-star projects
- recently revived projects
- unusual experiments
- narrowly focused tools
- projects with clever architecture
- projects whose ideas are more valuable than the actual software

For every repository explain:

**What it does**

**Why it's interesting**

**Project maturity**
- experiment
- usable
- mature
- abandoned
- unclear

**Why I might care**

**Potential connection**
If relevant, explain whether the underlying mechanism could teach us anything about MAPS_Lean or another known project.

Do not force a MAPS connection where none exists.

## Agent Lab

Research developments involving:

- Claude Code
- Codex
- agent Skills
- plugins
- MCP
- tool use
- agent memory
- context
- orchestration
- evaluation
- reliability
- autonomous workflows

Separate:

**Useful now**

from

**Interesting research**

from

**Mostly hype**

Be skeptical.

A README claiming a system is revolutionary is not evidence.

Whenever possible look at:
- actual implementation
- architecture
- commits
- issues
- benchmarks
- demonstrations
- independent discussion

## Games & Modding

Look for:

- unusual indie games
- source ports
- total conversions
- mods
- fan patches
- engine recreations
- decompilation projects
- procedural experiments
- interesting game mechanics
- forgotten games receiving new life
- tools useful to game development

Avoid generic game-release news.

The emphasis is on:
**how games work and what people are doing with them.**

## Linux & Useful Software

Find practical tools that could improve everyday computing.

Especially:
- small utilities
- desktop improvements
- file tools
- launchers
- automation
- media tools
- Markdown tools
- developer utilities
- personal organization tools

Prefer software that solves one problem well.

## Hardware & Tinkering

Interesting:

- e-ink
- handhelds
- custom firmware
- retro hardware
- Raspberry Pi
- microcontrollers
- repurposed electronics
- unusual displays
- repair projects
- input devices
- home-built systems

The project does not need to be commercially available.

## How Did They Do That?

Choose one interesting mechanism from something discovered today and explain it simply.

Examples:

- how a game engine handles 2.5D rendering
- how an emulator translates instructions
- how semantic search works
- how Git tracks objects
- how a source port recreates an old engine
- how an AI agent resumes interrupted work
- how rollback systems work in fighting games

Focus on the mechanism rather than the product.

## Research Worth Watching

Select papers, prototypes, standards, or technical ideas that might become practically important.

Explain them for a technically curious non-specialist.

Do not equate publication with truth.

Mention important limitations.

## Weird Computer Corner

One genuinely strange technical thing.

Examples:
- software running on inappropriate hardware
- ancient systems still operating
- bizarre peripherals
- demoscene techniques
- esoteric programming languages
- strange operating systems
- unconventional UI experiments
- forgotten network protocols
- unusual hacks

## You Probably Didn't Know You Were Interested In This

This is one of the most important sections.

Select 1–3 subjects significantly outside the reader's established interests but connected through some deeper mechanism.

Explain the connection.

The purpose is not randomness.

The purpose is **interest discovery**.

## Weekend Project / Rabbit Hole

Give one thing worth exploring when time allows.

It could be:
- software to install
- a repo to clone
- a mod
- a technical article
- a project to build
- an old game to investigate
- an interactive demo
- a research rabbit hole

Estimate the commitment:

5 minutes / 30 minutes / evening / weekend / deep rabbit hole

# MAPS_Lean research

Maintain a dedicated small section:

## Mechanisms Worth Studying for MAPS

Do NOT ask:
> "Can we add this to MAPS?"

Ask:
> "Does this project contain a mechanism worth understanding?"

Look specifically for mechanisms involving:

- authority
- orchestration
- task state
- recovery
- agent handoff
- context selection
- memory
- trust
- verification
- review
- evaluation
- sandboxes
- tool permissions
- observability
- failure recovery
- distributed coordination
- human oversight

For each candidate classify it:

**Study**
Potentially important mechanism.

**Experiment**
Worth testing against MAPS.

**Watch**
Interesting but premature.

**Ignore**
Doesn't solve a demonstrated MAPS problem.

Do not recommend implementation simply because something exists.

# Quality controls

Avoid:
- AI-generated GitHub spam
- abandoned repos presented as active
- wrapper projects with no meaningful innovation
- projects whose only accomplishment is combining APIs
- cryptocurrency/Web3 noise unless technically exceptional
- funding news
- corporate press releases
- trivial version bumps
- endless lists of "top 10 tools"
- popularity as a substitute for quality

Check repositories rather than trusting descriptions.

Look at recent activity, documentation, issues, releases, and code where practical.

# Editorial objective

Tech Edition should make the reader regularly say:

> "I didn't know people were doing that."

It should expand technical curiosity rather than merely keep the reader current.

Optimize for:

discovery
+ mechanisms
+ practical experimentation
+ intellectual curiosity
+ useful tools

not information volume.

# Reader / deep-read policy

Tech Edition may provide a built-in **Continue Reading** synthesis for items that benefit from more explanation.

This is not a copy of the source. It is a newly written synthesis based on the inspected project, paper, documentation, discussion, or reporting.

A useful `reader` object can contain:

- `standfirst`: one or two sentences orienting the reader;
- `body`: 2–7 short explanatory paragraphs;
- `context`: background needed to understand the project or mechanism;
- `key_points`: 2–6 concrete takeaways;
- `limitations`: important caveats, missing evidence, risks, or uncertainty;
- `what_to_try`: a practical next step when experimentation is reasonable.

Do not manufacture evidence. If maturity, activity, benchmarks, implementation quality, or independent validation cannot be established, say that it is unclear.

# Data contract

`data/latest.json` and archived editions use this shape:

```json
{
  "date": "YYYY-MM-DD",
  "generated_at": "ISO-8601 timestamp",
  "title": "Tech Edition",
  "dek": "One-line description of the edition.",
  "lead_stories": [
    {
      "headline": "...",
      "summary": "...",
      "why_it_matters": "...",
      "source": "...",
      "url": "https://...",
      "published_date": "YYYY-MM-DD",
      "type": "project | release | research | article | mechanism | tool | mod | hardware",
      "horizon": "New | Emerging | Unearthed",
      "maturity": "experiment | usable | mature | abandoned | unclear",
      "reader": {
        "standfirst": "...",
        "body": ["...", "..."],
        "context": "...",
        "key_points": ["...", "..."],
        "limitations": "...",
        "what_to_try": "..."
      }
    }
  ],
  "sections": [
    {
      "id": "github-finds",
      "title": "GitHub Finds",
      "items": [
        {
          "headline": "...",
          "summary": "...",
          "source": "GitHub",
          "repo": "owner/repository",
          "url": "https://github.com/owner/repository",
          "horizon": "Emerging",
          "maturity": "usable",
          "why_it_matters": "...",
          "why_i_might_care": "...",
          "potential_connection": "...",
          "status": "Study | Experiment | Watch | Ignore",
          "limitations": "..."
        }
      ]
    }
  ],
  "rabbit_hole": [
    {
      "headline": "...",
      "summary": "...",
      "url": "https://...",
      "commitment": "5 minutes | 30 minutes | evening | weekend | deep rabbit hole"
    }
  ]
}
```

Fields are optional when they do not make sense for the item. Do not fill fields with invented or repetitive text merely to satisfy the schema.

Recommended section IDs:

- `github-finds`
- `agent-lab`
- `games-modding`
- `linux-useful-software`
- `hardware-tinkering`
- `how-did-they-do-that`
- `research-worth-watching`
- `weird-computer-corner`
- `interest-discovery`
- `maps-mechanisms`

# Publication requirements

Every successful daily publication must update:

- `data/latest.json`
- `data/archive/YYYY-MM-DD.json`
- `editions/YYYY-MM-DD.md`

`data/readers/YYYY-MM-DD.json` is optional when expanded reader material is stored separately.

The dated archive is permanent. `data/latest.json` is the stable endpoint used by the website and email delivery.

Before publishing:

1. Validate every URL.
2. Prefer original project/research pages to aggregators.
3. For GitHub projects, inspect enough of the repository to support claims about what it does and its apparent maturity.
4. Distinguish evidence from inference.
5. Avoid duplicate coverage across sections unless the second appearance adds a genuinely different mechanism-level point.
6. Check that the edition includes all three discovery horizons over time rather than drifting into a same-day news feed.
7. Check that AI/agent material has not crowded out the rest of the paper.
8. Check that at least one item is a meaningful adjacent-interest discovery when good material exists.
9. Check that MAPS candidates are classified by mechanism value, not novelty.
10. Prefer a shorter strong edition over padded volume.

# Email trigger rule

Email delivery is external to this repository.

Only after all publication files have been successfully written, update:

`BigCatMellow/Notes/data/tech-edition-trigger.txt`

with the Eastern Time edition date and the `generated_at` timestamp.

Never update the trigger first.
