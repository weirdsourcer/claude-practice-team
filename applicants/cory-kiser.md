# Cory Kiser — Skills Profile

---

## Name / Handle
Cory Kiser — GitHub: `corydkiser`

---

## Contact Information

- **Email:** corydkiser@gmail.com
- **LinkedIn / Twitter / other:** https://www.linkedin.com/in/corydkiser/

---

## Core Identity
Strategic and Engineering Manager bringing AI into one of the least-digitized industries there is — heavy-highway construction, asphalt, and aggregates mining. I came up on the operational side as an engineer, and I now act as the internal force getting Claude into the hands of a multi-division, mostly non-technical workforce. I find the real problem on the ground and ship the agent, skill, or tool that solves it. I've been working with neural nets since 2012 — back when that meant hand-rolling convolutional networks — so for me the LLM era is a continuation, not a pivot.

---

## What You're Good At
- Turning messy operational problems — haul-cycle analysis, plant inventory, equipment selection, parcel/site data — into AI tooling that non-technical teams actually use.
- Authoring Claude Code Skills that encode hard-won domain knowledge and pull live data at runtime instead of hardcoding stale numbers.
- Building real software with Claude Code despite a non-traditional dev background: CLI tools, MCP servers, browser automation.
- GIS / surveying / CAD workflows — state plane coordinates, DXF/DWG, ArcGIS REST services.
- Driving org-wide adoption: standing up company-wide skills and workflows and embedding them across divisions, not just prototyping for myself.

---

## How You Use AI Right Now
- **Claude Code as my primary build environment** — writing and porting software with proper verification loops/harnesses, lean CLAUDE.md conventions, subagents, and plugins.
- **Authored a company-wide equipment-performance Skill.** It reads manufacturer data (Caterpillar Performance Handbook, Komatsu, John Deere, Volvo, etc.) and runs haul-cycle and fleet-matching analysis — e.g. what combination of loaders and haul trucks hits 400 tph at a limestone mine — retrieving current specs at run time rather than relying on remembered numbers.
- **Automated internal plant-inventory pulls.** Built Selenium browser automation against our production system, then distilled it into a reusable, parameterized prompt so anyone can rerun it for any plant.
- **Shipped `ohio-parcel-extractor`** — a CLI that pulls parcel lines from Ohio DNR ArcGIS services and exports DXF/DWG from a state-plane bounding box.
- **Built a Blue Iris MCP server** (TypeScript) to drive a video-surveillance system from Claude.
- **Wrote a personal research Skill** with a strict anti-hallucination, live-verification workflow (nothing ships unless it's confirmed against a real source).
- **Formal AI credentials** — MIT professional-education certificates in reinforcement learning, plus working toward Anthropic's (the Academy courses and the Claude Certified Architect – Foundations exam).

---

## Current or Recent Projects
- **Eurorack synth design harness (`eurorackdesignerbot`)** — a Claude Code toolkit that turns a one-line synthesiszer module idea into a fabricable Daisy Seed Eurorack module in a single pass: it picks cost-optimized parts (favoring JLCPCB Basic/Preferred and auto-splitting the BOM into machine-placed SMT vs. hand-soldered panel parts), generates the full hardware design in KiCad (SKiDL schematic → netlist, PCB outline + placement, front-panel SVG), and writes the bare-Daisy-Seed firmware that compiles to a flashable `.bin` — all orchestrated across a numbered ~17-subagent pipeline with a mandatory pre-fab verification gate. Inspired by Anthropic's recent Opus 4.8 hackathon.
- **AI-ready plant-automation standards** — helping deploy data and automation standards across our heavy-industry plants so LLMs can interpret plant processes and sensor data, building toward smart-manufacturing goals that fuse that operational knowledge with the rest of the company's data.
- **Enterprise Wide Skills** — company-wide skills for our construction, asphalt, and aggregates divisions.
- **`ohio-parcel-extractor`** — Ohio parcel → DXF/DWG tool. (https://oh-parcels.com/)
- **Speading Up Integrations** — I am working on a Project identifying in the company where traditional integrations are needed versus using Claude hooked up to the relevant data to deliver things on the fly. I've also had a lot of luck in speeding up traditional integrations and making them much less error prone when rolling them out with AI.
- **Blue Iris MCP server** — MCP integration for video surveillance.

---

## What You Want to Build Here
I want to help define what "AI-first" actually looks like outside of tech — in heavy industry, mining, and construction, where the leverage is enormous and almost nobody is building. I'd contribute domain-specific skills and a strong background in implementing AI in non-tech industries, share what genuinely drives adoption with non-technical operators (the part most builders never see), and learn from other people who take things from idea to shipped tooling fast.

---

## Superpower
I turn hard-won operational knowledge from a blue-collar industry into AI skills and agents that non-technical teams actually adopt.
