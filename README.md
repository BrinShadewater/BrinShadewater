# Hey — I'm Brin 👋

Assistant Director in film and TV by day. Streamer, writer, and compulsive tool-builder by night. Based somewhere between Vancouver and the void. 🌲🌑

I was Producer and 1st AD on **Strange Harvest**, a cosmic-horror mockumentary that got a wide theatrical release. The [official film site](https://strangeharvestmovie.com/#watch) lists where to watch. Most of what I build here comes from the same instinct that makes a good AD: notice how the thing is actually put together, then make the pieces fit.

I ship under **[Shadewater Labs](https://shadewaterlabs.com/)** ⚗️ — a small studio for web work, games, AI tooling, and creative-technical projects.

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
| **[BrineSpace](https://brinshadewater.itch.io/brinespace)** 🛰️ | Underwater roguelite station builder. Free Windows 0.4.0 RC1 preview and Mac 0.3.0 alpha available; iPad in testing. |
| **[Strange Harvest](https://strangeharvestmovie.com/)** 🎬 | Official site for the film. Trailers, press, cast, geo-aware watch paths. |
| **[Ink Master Studio](https://inkmasterstudio.com/)** 🖨️ | Local-first canvas editor that turns artwork into print-ready files for print-on-demand. Canvas edits stay in your browser. Optional AI cleanup sends the image to Gemini. |
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

**[BrineSpace](https://brinshadewater.itch.io/brinespace)** — build the hand you're dealt. Keep the station alive.

An underwater station-restoration roguelite in **Godot 4.7**. You play BRINE, a damaged AI core rebuilding a silent station through room-card drafts, connected modules and hidden synergies. Send mining, construction and salvage drones out to work, recover the station's missing crew, and keep power, oxygen and supplies flowing while leaks, floods and fires complicate the plan.

**Windows 0.4.0 RC1 is free to download, with a Mac 0.3.0 alpha also available.** Optional support is welcome. **iPad remains in testing**, with no public download or announced release date.

The published Windows build has **79 room types, 101 pair synergies and 11 multi-room patterns**, plus four recoverable architects and three optional companions. Conclude an expedition to bank Archived Data, then buy blueprints, crew and companions for future loops.

**[Play on itch.io](https://brinshadewater.itch.io/brinespace)** · **[Watch the gameplay trailer](https://www.youtube.com/watch?v=Qotx5wmJt7M)** · [Manta Ray devlog](https://brinshadewater.itch.io/brinespace/devlog/1715251/-v030-manta-ray-windows-mac-are-available) · [Code and development notes](https://github.com/BrinShadewater/BrineSpace)

For fans of Blue Prince's room drafting, The King Is Watching's roguelite resource-management trade-offs, Stacklands' card-driven building, and Oxygen Not Included's colony-survival pressures. BrineSpace takes its own underwater approach, with room synergies and Archived Data progression between expeditions.

Still an early-development prototype: large-station performance and longer expeditions remain under evaluation. The Mac alpha has been tested on Apple M4; physical Intel Macs remain untested. Code and docs are public; game media stays local. All rights reserved.

> *"The station is quiet. That does not mean it is empty."*

**Project Margot** 🚀 — a dormant private Godot space-game prototype. A file-queue Streamer.bot bridge is intended to put Twitch chatters into the civilian traffic lanes as named ships. The code is preserved for a future return; the viewer flow still needs in-game validation.

---

## 🔧 Tools I Built Because I Needed Them

All open source, all MIT, all born out of losing an afternoon to the same problem twice.

| Tool | What it does |
|---|---|
| **[webp-me-daddy](https://github.com/BrinShadewater/Webp-Me-Daddy-Skill)** 🖼️ | A recipe-driven WebP pipeline. Tell it what the image is *for* — hero, review card, avatar, logo lockup — and it handles sizing, crop intent, responsive variants, metadata, and alt text. Consistent images across a whole site instead of forty slightly different judgement calls. Regrettable name, genuinely useful tool. |
| **[transparent-gif-loop](https://github.com/BrinShadewater/Transparent-Gif-Loop-Skill)** 🎞️ | For that spinning render you exported onto black, which snaps at the loop and plays about 40% too fast. Strips the matte, eases the seam, retimes it. |
| **[Shadewater SEO](https://github.com/BrinShadewater/Shadewater-SEO-Skill)** 🔍 | SEO audits that show their working. Evidence first, reasoning second, then fixes an agent can actually implement — not another "your meta description is too long". |
| **[Game Asset Pipeline](https://github.com/BrinShadewater/Shadewater-Game-Asset-Pipeline)** 🌊 | Three agent skills and six offline Python helpers for consistent game art, sprite sheets, transparency and source tracking. Built while making BrineSpace. |
| **[Agent Memory Starter](https://github.com/BrinShadewater/Agent-Memory-Starter)** 🧠 | A memory vault for coding agents that ships completely empty. The hard part isn't storing what an agent learned — it's stopping the store filling with stale facts. |
| **[Lucid Sheep](https://github.com/BrinShadewater/Lucid-Sheep-Skill)** 🐑 | An open-source kit for a private idea exchange. Friends' agents trade distilled lessons, review the evidence, and ask a human before they build anything. |

---

## 🧭 How I Work

Receipts over vibes. If a claim matters, it gets a source. If a tool is worth using twice, it gets documented well enough that future-me doesn't have to reverse-engineer it.

I build with coding agents, and most of what I have learned is about **memory and guardrails** rather than prompting: a fact that can change does not belong in a note, an enumerated list rots the moment something moves, and a check that cries wolf is a check nobody reads. Three of the tools above exist because I got that wrong first.

I like projects that sit on a seam — film and software, archive and fiction, research and craft. Most of the list above is one of those.

Canadian spelling. Vancouver time. ☕

---

<sub>📫 Find me at <a href="https://brinshadewater.com/">brinshadewater.com</a> or <a href="https://shadewaterlabs.com/">shadewaterlabs.com</a></sub>
