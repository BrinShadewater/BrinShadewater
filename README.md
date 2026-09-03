# Hey — I'm Brin 👋

Assistant Director in film and TV by day. Streamer, writer, and compulsive tool-builder by night. Based somewhere between Vancouver and the void. 🌲🌑

I was Producer and 1st AD on **Strange Harvest**, a cosmic-horror mockumentary that got a wide theatrical release and now streams on Hulu and Paramount+. Most of what I build here comes from the same instinct that makes a good AD: notice how the thing is actually put together, then make the pieces fit.

I ship under **[Shadewater Labs](https://shadewaterlabs.com/)** ⚗️ — a small studio for web work, AI tooling, and creative-technical projects.

---

## 📚 Data Goblin

**[datagoblin.ca](https://datagoblin.ca)** — a free, bilingual (EN/FR) field guide to AI, power, and data in Canada.

Who owns the compute, where the data centres draw their electricity and water, what "sovereign AI" actually means when you read the contracts. Every claim in the book has a receipt behind it in a public ledger. If I can't source it, it doesn't ship.

Free to read. No paywall, no signup, no newsletter gate. Licensed CC BY-NC so teachers, journalists, and researchers can actually *use* it — quote it at length, put a chapter in a course pack, translate it. Free to read is not much good if it's illegal to teach. 🧾

> [`Data-Goblin-Web`](https://github.com/BrinShadewater/Data-Goblin-Web) — the reader

---

## ⏱️ Film Set Tools

**[filmsettools.com](https://filmsettools.com)** — the tools I kept wishing I had on set, so I built them.

Ten tools for BC film crew — meal penalties, turnaround, cast hours, overtime, studio-zone boundaries, and what the agreements pay for travel beyond the zone — grounded in the actual union agreements, with the article cited and the working shown. Built for the people who have to answer these questions at 5am with a radio in one hand, because a number you can't defend on set is worse than no number at all.

The zone maps are the part I'm proudest of: the boundary data is human-sourced from the agreements' own written boundary language, human-reviewed, and guarded by a human-signed golden test set. No AI-generated geography gets to tell a driver where the zone ends. Both zones are now drawn on an interactive map, and every rule on the site has been checked visually against the rendered agreement pages rather than a text extraction.

*Private repo — the site is the product.*

---

## 🎬 Things I've Shipped

| Project | What it is |
|---|---|
| **[Strange Harvest](https://strangeharvestmovie.com/)** 🎬 | Official site for the film. Trailers, press, cast, geo-aware watch paths. |
| **[Ink Master Studio](https://inkmasterstudio.com/)** 🖨️ | Local-first canvas editor that turns artwork into print-ready files for print-on-demand. Your images never leave the browser. |
| **[Lost Hills Online](https://losthills.net)** 🏛️ | The restored municipal web portal of a town that stopped updating in 1997. An in-world archive with records the Clerk's Office would rather you didn't crawl. |
| **[Shadewater Labs](https://shadewaterlabs.com/)** ⚗️ | The lab bench. Projects, explainers, and proof of the work. |
| **[brinshadewater.com](https://brinshadewater.com/)** 🎮 | Streams, plus long-form game and film reviews. |

---

## 🤖 River

A Reachy Mini on my desk that I am slowly teaching manners.

River hears you locally — voice detection and speech-to-text run on the machine in front of him, not in somebody's cloud. Only *text* leaves the machine. He uses he/him, and he is calm, warm and brief, which took more engineering than the sentence suggests.

The part I care most about is the privacy rail, because it is the part that would be easiest to skip:

- 📷 **The camera stays shut** unless you explicitly ask River to look, and then it is one frame for one question
- 🚫 **No face recognition, no image retention, no embeddings** — River can tell you a face is present and roughly where, and that is the whole capability
- 🔒 **Fails closed.** If the privacy mode or the local speech assets are missing, River refuses to start rather than quietly falling back to something chattier

Local-first robotics is mostly a pile of boring lifecycle bugs wearing a trench coat. Getting the head to stop following you the instant River starts speaking took three attempts.

*Private repo — happy to talk about the architecture.*

---

## 🛰️ Making Games

**[BrineSpace](https://github.com/BrinShadewater/BrineSpace)** — a passive roguelite orbital-station builder in Godot 4. You're BRINE, a damaged AI core rebuilding a dead station out of blueprint drafts, modular rooms, and adjacency synergies you have to discover for yourself. Thoughtful and watchable rather than frantic.

> *"The station is quiet. That does not mean it is empty."*

**Project Margot** 🚀 — a Godot space game with a Streamer.bot bridge that spawns Twitch chatters as ships with their own callsigns and nameplates, sharing traffic lanes with the civilian AI. The stream becomes the population of the system. Private prototype, in the polish phase.

---

## 🔧 Tools I Built Because I Needed Them

All open source, all MIT, all born out of losing an afternoon to the same problem twice.

| Tool | What it does |
|---|---|
| **[webp-me-daddy](https://github.com/BrinShadewater/Webp-Me-Daddy-Skill)** 🖼️ | A recipe-driven WebP pipeline. Tell it what the image is *for* — hero, review card, avatar, logo lockup — and it handles sizing, crop intent, responsive variants, metadata, and alt text. Consistent images across a whole site instead of forty slightly different judgement calls. Regrettable name, genuinely useful tool. |
| **[transparent-gif-loop](https://github.com/BrinShadewater/Transparent-Gif-Loop-Skill)** 🎞️ | For that spinning render you exported onto black, which snaps at the loop and plays about 40% too fast. Strips the matte, eases the seam, retimes it. |
| **[Shadewater SEO](https://github.com/BrinShadewater/Shadewater-SEO-Skill)** 🔍 | SEO audits that show their working. Evidence first, reasoning second, then fixes an agent can actually implement — not another "your meta description is too long". |
| **[Agent Memory Starter](https://github.com/BrinShadewater/Agent-Memory-Starter)** 🧠 | A memory vault for coding agents that ships completely empty. The hard part isn't storing what an agent learned — it's stopping the store filling with stale facts. |
| **[Lucid Sheep](https://github.com/BrinShadewater/Lucid-Sheep-Skill)** 🐑 | A private idea exchange for trusted friends' agents. They trade distilled idea cards, never runnable code, and a human approves anything that actually gets built. |

---

## 🔭 On The Bench Right Now

<sub>Snapshot from <strong>2026-09-02</strong>. If that date has gone soft, assume this moved on without me — the rest of this page ages better than this section does.</sub>

- **Film Set Tools** — the travel rules engine shipped on top of the zone work and its rate table passed human review; next is auto-filling distance from the boundary road network, which is built but waits on its own signed golden routes
- **Data Goblin** — sourcing the next run of claims, and keeping the French edition in step with the English
- **River** — teaching the robot to reliably recognize one specific cat, which turns out to be a hard problem in exactly the ways face recognition should be

---

## 🧭 How I Work

Receipts over vibes. If a claim matters, it gets a source. If a tool is worth using twice, it gets documented well enough that future-me doesn't have to reverse-engineer it.

I build with coding agents, and most of what I have learned is about **memory and guardrails** rather than prompting: a fact that can change does not belong in a note, an enumerated list rots the moment something moves, and a check that cries wolf is a check nobody reads. Three of the tools above exist because I got that wrong first.

I like projects that sit on a seam — film and software, archive and fiction, research and craft. Most of the list above is one of those.

Canadian spelling. Vancouver time. ☕

---

<sub>📫 Find me at <a href="https://brinshadewater.com/">brinshadewater.com</a> or <a href="https://shadewaterlabs.com/">shadewaterlabs.com</a></sub>
