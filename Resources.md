# Resources.md — Gregory's Lab & Toolchain
*Last updated: 2026-03-20*

---

## Hardware

### Primary Workstation
**iMac 5K** (Late 2014) — Intel CPU, 32GB RAM, 1TB HDD, macOS Ventura 13.7.8
Primary product development machine. Local file storage. GitHub pushes via VS Code.

### Daily Driver
**MacBook Air M3** (2024) — Apple M3, 16GB RAM, 512GB internal + 2TB external SSD, macOS 14
Active daily-use system. UTM and Parallels installed. Strong candidate for local AI work.

### Local AI / Self-Hosting Server
**ZimaOS Server / HP 6300 SFF** (circa 2012–2013) — Intel Core i5-3550 3.3GHz 4c/4t, NVIDIA GeForce GT 710, 32GB RAM, 250GB boot SSD + 6TB HDD, ZimaOS+ 1.54
Active. Runs Ollama + Open WebUI (Lab-in-a-Box: Local AI reference implementation). Primary self-hosting and experimentation box.

### NAS / Services
**TrueNAS Server** — Intel Xeon E3-1220 v3 3.1GHz, 16GB RAM, mirrored SSD boot + 6TB data pool, TrueNAS Community 25.10.1
Active primary NAS. Runs Pi-hole and other services.

### Utility Server
**Mac mini** (Late 2014) — Intel Core i5 dual-core 2.6GHz, 8GB RAM, 500GB SSD, macOS Sequoia
Network-attached host for Drobo 5C. Always-on candidate for lightweight agent tasks.

### Workstation (Status Unclear)
**Mac Pro "trash can"** (2013) — Intel Xeon, 64GB RAM
Current active status unconfirmed. Verify before assigning a role.

### Edge Compute
**Raspberry Pi 4** — Broadcom ARM, 8GB RAM (maxed)
Active. Candidate for PicoClaw-style lightweight agent tasks and always-on monitoring.

**Raspberry Pi #2 and #3** (older models) — specs unconfirmed
Available. Suitable for low-demand edge tasks once specs verified.

### Linux Laptop
**MacBook Pro** (specs unconfirmed) — MX Linux from dedicated USB drive
Active for Linux experimentation.

### Virtual Machines
**Windows 10 VM** — Parallels on MacBook Air M3

### Creative & Photography
- **Topaz Photo AI 4.0.4** — AI-powered photo enhancement and noise reduction
- **PhotoPrism** — self-hosted photo management and library (running on TrueNAS)
- **Sony RX-10 Mark IV** — primary camera for product demo videos and photography
- **MXL USB.007 Microphone** — USB condenser mic for voiceover and talking head recordings

---

## Software & Toolchain

### Development
- **VS Code** — primary editor and GitHub source control
- **GitHub** — source of truth for all shared context files and product repos
- **Docker / Docker Compose** — active on ZimaOS server

### Local AI Stack
- **Ollama 0.5.7** — running on ZimaOS server (pinned; update to 0.18.0 planned)
- **Open WebUI 0.5.20** — running on ZimaOS server (pinned)
- **LM Studio** — installed, available for model testing

### Virtualization
- **UTM** — GUI Linux VMs on Apple Silicon
- **Parallels** — Windows 10 VM on MacBook Air M3

### Storage
- **PhotoPrism** — self-hosted photo management
- **TrueNAS** — primary NAS and services host
- **Drobo 5C** — attached to Mac mini

---

## AI Tools & Access

- **Claude.ai** — primary AI partner; Projects used for domain separation
- **ChatGPT** — web search, memory retrieval, cross-checking
- **Grok** — additional cross-checking in multi-model synthesis workflow
- **Gemini** - creative ideas and visual feedback
- **Ollama** — local model inference on ZimaOS server
- **Claude API** — available; reserved for high-reasoning orchestration tasks

---

## Notes
- ZimaOS Docker Compose requires: `sudo /usr/lib/docker/cli-plugins/docker-compose`
- ZimaOS writable data path: `/DATA/AppData/`
- Items marked ⚠️ in hardware sheet have unconfirmed specs — verify before documenting in product materials