<h1 align="center">Mario Arturo Jiménez Terrón</h1>

<p align="center">
  <em>CTO @ Buzzword · COO @ Inovitz · GrupoCSI</em><br>
  <sub>Author of <a href="https://termdoc.app">termdoc</a> and <a href="https://dapctl.com">dapctl</a> · Linux · Free software · Photography</sub>
</p>

<p align="center">
  <a href="https://linkedin.com/in/marturojt"><img src="https://img.shields.io/badge/LinkedIn-0d1117?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="https://instagram.com/_systemctl"><img src="https://img.shields.io/badge/@__systemctl-0d1117?style=flat-square&logo=instagram&logoColor=white"></a>
  <a href="https://freejolitos.com"><img src="https://img.shields.io/badge/Freejolitos-0d1117?style=flat-square&logo=gnu&logoColor=white"></a>
  <a href="https://termdoc.app"><img src="https://img.shields.io/badge/termdoc.app-0d1117?style=flat-square&logo=rust&logoColor=white"></a>
  <a href="https://dapctl.com"><img src="https://img.shields.io/badge/dapctl.com-0d1117?style=flat-square&logo=rust&logoColor=white"></a>
</p>

---

## `$ whoami`

Mexican engineer. Two contexts, one standard.

By day I run technology at **Buzzword** (CTO) and operations at **Inovitz** (COO), both part of **GrupoCSI**. Since 2014 I've worked on **ART** (*Approval in Real Time*), a proprietary real-time decisioning platform for credit and insurance, running in production for tier-one financial clients under **CMMI Level 5** (DEV, SVC, SEC, DATA), **ISO 27001** and **PCI-DSS**.

After hours I write terminal tools in Rust, self-host what I can, and help keep **Freejolitos** alive — a hacker-culture community with people in Estonia, Russia, the Middle East and Mexico. Not a personal brand: a community that happens to run on infrastructure I maintain.

I also shoot architecture and street photography in Mexico City, on a Canon EOS R6 Mark II.

> *Reversibility first. Elegance after, if there's time left.*

---

## `$ ls ~/now`

**[`termdoc`](https://github.com/marturojt/termdoc)** — A fast, terminal-native document viewer in Rust. One command for whatever document is in front of you, instead of a different tool per file type. Markdown, plain text and logs render today; many more formats are recognised and getting dedicated readers milestone by milestone. Not an editor, not a converter, not an IDE. `cargo install termdoc`. → [termdoc.app](https://termdoc.app)

**[`dapctl`](https://github.com/marturojt/dapctl)** — Terminal-first toolkit to sync, audit and manage music libraries on HiFi Digital Audio Players, with a safe preview of every change before a single file is copied. **v1.0.1**, prebuilt binaries for Linux/macOS/Windows, `brew tap marturojt/tap`. Validated on a real sync of 2,108 FLAC files (75 GB) to a HiBy R4. → [dapctl.com](https://dapctl.com)

**Own infrastructure** — Debian, Apache as reverse proxy, federated Matrix Synapse, Pi-hole, Cloudflare DNS, certificates by DNS validation. Arch Linux with Hyprland on the desk; LUKS2 + LVM + Btrfs underneath, with a tested rescue path before the old one is retired.

---

## `$ cat principles.txt`

```text
Reduce the problem before adding tools.
A well-divided monolith beats twelve badly-drawn services.
Official sources or nothing.
Documentation ships with the code, not after it.
Tools get named the way the system already taught: systemctl, journalctl, dapctl.
Security belongs in the design, not in the audit.
Never remove the escape route before testing the new one.
Code that ages well.
```

---

## `$ cat stack.txt`

```text
Languages      Rust · Python · TypeScript · Shell · SQL
Backend        FastAPI · Node.js · .NET · Next.js · Astro
Data           PostgreSQL · pgvector · SQLite · MySQL · MongoDB
Systems        Arch Linux · Hyprland · Debian · systemd · macOS
Infra          Apache · Cloudflare · Docker · GitHub Actions · Azure
Self-hosted    Matrix Synapse · Pi-hole · certbot (dns-cloudflare)
Security       PCI-DSS · ISO 27001 · LFPDPPP · OWASP · nmap · impacket
Environment    tmux · zsh · Obsidian · rsync
Camera         Canon EOS R6 Mark II · RF 24-70
```

---

## `$ ls projects/`

### Terminal tools · Rust

| Project | What it is |
|---|---|
| **[termdoc](https://github.com/marturojt/termdoc)** | Universal document viewer for the terminal. Multi-crate workspace, dual MIT/Apache-2.0, on crates.io. |
| **[dapctl](https://github.com/marturojt/dapctl)** | DAP-aware music library sync and audit. GPLv3, v1.0.1, `cargo install dapctl`. |
| **[homebrew-tap](https://github.com/marturojt/homebrew-tap)** | `brew tap marturojt/tap` — distribution channel for my own tools. |

### Security engineering

| Project | What it is |
|---|---|
| **[Harden.Tools](https://github.com/marturojt/harden-tools-website)** | Security engineering for real infrastructure. Bilingual Astro site. |
| **Fortaleza** · *private* | Micro-SaaS that scans domains passively and non-destructively — 7 parallel scanners, findings mapped to LFPDPPP, PCI-DSS, ISO 27001 and OWASP Top 10, reported in business language. |
| **fortaleza-pentest** · *private* | Internal LAN penetration testing TUI. 12 assessment modules over nmap, hydra and impacket; every finding mapped to PCI-DSS v4.0 and ISO 27001:2022 controls, with Markdown, HTML and PDF reports. |

### Platforms & APIs

| Project | What it is |
|---|---|
| **[id-manager-api](https://github.com/marturojt/id-manager-api)** | ID document extraction, face matching and proof of life. Python. |
| **DocAI** · *private* | Electronic dossier platform: upload, OCR, structured extraction with AI and natural-language queries over case files. Configurable by industry preset. FastAPI + Postgres/pgvector + S3. |
| **[snr-red](https://github.com/marturojt/snr-red)** | URL shortener and QR manager with per-link analytics — geolocation, device, browser, time series. Next.js + Node.js, running at [snr.red](https://snr.red). |
| **[croni.co](https://github.com/marturojt/croni.co)** | The Python URL shortener that came before snr-red. |
| **[poc-contact-center](https://github.com/marturojt/poc-contact-center)** | AI agents for contact centre: five use cases, three verticals, WebRTC voice and SSE text, live metrics panel. |

### Sites

| Project | What it is |
|---|---|
| **[masada](https://github.com/marturojt/masada)** | Astro + MDX, static output, zero JS frameworks. Self-hosted at [masada324.org](https://masada324.org). |
| **[insidious-space-landing](https://github.com/marturojt/insidious-space-landing)** | Minimalist cyberpunk landing for a free-software systems integrator. |

### Hardware & systems

| Project | What it is |
|---|---|
| **[zmk-config](https://github.com/marturojt/zmk-config)** | Keyboard firmware config. ZMK, plus QMK and PCB work on the side. |
| **[datacenter-monitor](https://github.com/marturojt/datacenter-monitor)** | Temperature and humidity monitoring for a datacenter, on a Raspberry Pi with a DHT11. |
| **[SFTPFolderAnalyzer](https://github.com/marturojt/SFTPFolderAnalyzer)** | Detects new files on an SFTP server and notifies over Telegram. |
| **myConfigs** · *private* | Migrates terminal and prompt config between Macs, AES-256-CBC encrypted with PBKDF2, using only the `openssl` already present on macOS. |

### Experiments

| Project | What it is |
|---|---|
| **[WaifuBOT](https://github.com/marturojt/WaifuBOT)** | AI companion inside a Telegram bot. Python. |
| **ART** · *proprietary* | Real-time approval platform for financial products. In production since 2014. |

Most of what's here started as something I needed, and only later became software worth reusing.

---

<p align="center"><sub><i>Free software as practice, not as a flag.</i></sub></p>
