# Lab-in-a-Box Product Ecosystem — Status & Coordination
*Last updated: 2026-03-19*

---

## Overview
Lab-in-a-Box is the brand coordinator for all subsidiary products. Each product has its own Claude project for focused development. This file is the master ledger — load it at the start of any Lab-in-a-Box or product-specific session.

---

## Foundation Products

### Lab-in-a-Box: Local AI
- **Status:** Launched
- **Claude Project:** Lab-in-a-Box
- **Gumroad:** gregorydcollins.gumroad.com/l/local-ai
- **Description:** Ollama + Open WebUI bundle for ZimaOS and Linux home labs
- **What's next:** Align with updated Lab-in-a-Box strategy; consider YouTube launch video

### Home Lab Binder Kit (HLBK)
- **Status:** In redesign
- **Claude Project:** HLBK
- **Gumroad:** gregorydcollins.gumroad.com/l/hlbk
- **Description:** Printable/fillable PDFs for home lab documentation (3 styles)
- **What's next:** Clarify product positioning — what do people actually need? Finish redesign with Claude.

---

## Signet Product Line

### Lab-in-a-Box: Signet (Free)
- **Status:** In active development — V1 nearly complete
- **Claude Project:** Lab-in-a-Box (Brainstorming & Agents project)
- **Gumroad:** (not yet listed)
- **Description:** A structured AI-powered interview that generates a personal signet.md file — a portable operating document that stamps your standards, voice, and judgment onto any AI agent session. Free tier covers 6 core sections. Output: signet.md.
- **Tagline:** Stamp your standards onto any AI, once.
- **Method:** Interview → Distill → Encode
- **Price point:** Free (lead product) / $14 launch one-time
- **Thumbnail keywords:** ALIGN / STAMP / DEPLOY
- **What's next:** Complete design rebuild using Industrial Archive palette; update Gumroad listing under Signet name; build usage guide

### Lab-in-a-Box: Signet Pro
- **Status:** Planned — V2
- **Claude Project:** (TBD)
- **Gumroad:** (not yet listed)
- **Description:** Full Signet interview plus Role Hats — specialized behavioral configurations for researcher, writer, operator, coder, and other roles. Subscription model with monthly hat presets, compatibility updates, and unlimited regenerations.
- **Price point:** $9-29/mo (TBD)
- **What's next:** Design and build after Signet Free launches; subscription infrastructure needed

---

## Team Builder Product Line
*(formerly AI Team — renamed 2026-03-19)*

### Lab-in-a-Box: Team Foundation
- **Status:** In active development
- **Claude Project:** AI Team Foundation
- **Gumroad:** (not yet listed)
- **Description:** Core Claude + ChatGPT collaborative workflow using GitHub as shared memory. Base system for all Team Playbooks.
- **Price point:** $40-50
- **What's next:** Complete core product, prepare for launch

### Lab-in-a-Box: Team Builder (V2 — future)
- **Status:** Future product idea — logged 2026-03-19
- **Claude Project:** (none yet)
- **Description:** Case study module documenting the creation of Lab-in-a-Box: Signet as a live demonstration of the five-model collaborative workflow (Claude, ChatGPT, Grok, Gemini, Gregory). Shows buyers exactly how to assign tasks to different models, run synthesis rounds, and coordinate a human-led AI team. The Signet build is the flagship worked example.
- **What's next:** Build after Team Foundation ships; full asset inventory already exists from Signet session

### Team Playbooks (Add-ons)
Planned playbooks to layer on top of Foundation:
- **Social Media Playbook** — status: planned
- **Product Development Playbook** — status: planned
- **Content Creator Playbook** — status: planned
- **Brand Management Playbook** — status: planned

---

## CrossCheck Product Line

### CrossCheck (Brand & Strategy)
- **Status:** Strategy locked, ready to build
- **Claude Project:** CrossCheck
- **Description:** "The second opinion system for AI" — peer review and verification kits for different audiences
- **What's next:** Build first product (Content Creator kit)

### CrossCheck for Content Creators
- **Status:** In development
- **Claude Project:** CrossCheck
- **Gumroad:** (not yet listed)
- **Description:** AI verification and peer review system for content creators ($27)
- **What's next:** Complete product, prepare for launch

### CrossCheck: Notion Product Idea
- **Status:** Idea / on radar
- **Claude Project:** (none yet)
- **Description:** Notion-based template or system (flagged as potential top seller from multi-model synthesis)
- **What's next:** Evaluate feasibility, decide if worth developing

---

## Standalone Products

### Smart Papa
- **Status:** Mature / not actively developed
- **Claude Project:** (none, or shared with Lab-in-a-Box)
- **Description:** iPhone app that hooks into ChatGPT for on-device Q&A
- **Gumroad:** (check if listed)
- **What's next:** Determine if this is active or archived

### Meet Dogs Daily
- **Status:** Active brand / exploration phase
- **Claude Project:** Meet Dogs Daily
- **Description:** Photography + social media brand; testing autonomous content creation and scheduling
- **What's next:** Implement agent-driven caption writing and scheduling via Meta Business Suite API

---

## Infrastructure & Meta-Tasks

### Lab Hardware Inventory
- **Status:** In progress
- **Claude Project:** Home Lab
- **Description:** Comprehensive spreadsheet of all home lab equipment, roles, specs
- **What's next:** Complete inventory spreadsheet, deliver to Claude for documentation

### Local File Structure Cleanup
- **Status:** Needed
- **Claude Project:** (none yet, or Lab-in-a-Box)
- **Description:** Projects scattered across different locations; need consolidation and organization
- **What's next:** Audit current structure, plan reorganization strategy

### ChatGPT Web Scraper
- **Status:** Planned
- **Claude Project:** Brainstorming
- **Description:** ChatGPT scrapes web for product ideas relevant to Lab-in-a-Box, sends findings to Claude for analysis
- **What's next:** Design scraper logic, set up automation workflow

---

## Coordination Notes

- **Load these files at session start:** `Products_status.md`, `Soul.md` (WolfNinja32 repo)
- **Use raw GitHub URLs:** https://raw.githubusercontent.com/WolfNinja32/WolfNinja32/main/Products_status.md
- **Update frequency:** After each major product milestone or when status changes
- **Product launch readiness:** Signet Free, HLBK, Team Foundation, CrossCheck for Content Creators are next in queue
- **Naming note:** AI Team Foundation and AI Team Playbooks renamed to Team Foundation and Team Playbooks on 2026-03-19

---

## Quick Reference: Projects & Products

| Product | Claude Project | Status | Priority |
|---------|---|---|---|
| Local AI | Lab-in-a-Box | Launched | Align strategy |
| Signet Free | Lab-in-a-Box | Nearly complete | Ship next |
| Signet Pro | TBD | Planned | After Signet Free |
| HLBK | HLBK | In redesign | Ship soon |
| Team Foundation | AI Team Foundation | In dev | Ship soon |
| Team Builder V2 | TBD | Future idea | After Foundation |
| CrossCheck for Content Creators | CrossCheck | In dev | Ship soon |
| Meet Dogs Daily | Meet Dogs Daily | Active | Explore automation |
| Smart Papa | TBD | Mature | Clarify status |
| CrossCheck: Notion | none | Idea | Evaluate |
| Lab Hardware Inventory | Home Lab | In progress | Complete |
| File Structure | TBD | Needed | Plan soon |
| ChatGPT Scraper | Brainstorming | Planned | Design phase |