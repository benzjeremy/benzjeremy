### Hey, I'm Jeremy. 👋

17 y/o systems developer from North Rhine-Westphalia, Germany. High-velocity **VibeCoding** paired with uncompromising engineering discipline in **Go** — verified cryptography, zero Electron bloat, 100% Local-First ownership, and free software.

[![Awesome Go](https://awesome.re/mentioned-badge.svg)](https://github.com/avelino/awesome-go)
![Go Version](https://img.shields.io/badge/Go-1.22+-00ADD8?logo=go&logoColor=white)
![License: GPL-3.0](https://img.shields.io/badge/License-GPL--3.0-blue.svg)
![Status: Pre-Release](https://img.shields.io/badge/Status-Pre--Release%20%2F%20WIP-orange.svg)
![Security](https://img.shields.io/badge/Security-Zero--Dummy--Standard-10b981)
![Architecture](https://img.shields.io/badge/Architecture-Zero--Electron-orange)

> [!IMPORTANT]
> ### 🚧 Pre-Release / Active Development Notice
> All software projects across this ecosystem are **not yet finished** and remain under active development. All current releases, tags, packages, and binaries are **Pre-Releases** (Work in Progress), even if not originally announced as such. Features, APIs, and tools are continually being refined.

---

### 🏪 Always Up-to-Date: BenzStore & App Catalog

Instead of tracking releases and version numbers manually across dozens of individual repositories, all current builds, changelogs, and release assets are centralized in **[BenzStore](https://benzjeremy.github.io/benzstore/)** — the unified, privacy-first open-source AppStore for Android and PC:

👉 **[Launch BenzStore Live Catalog & Downloads →](https://benzjeremy.github.io/benzstore/)**

* 📦 **Always Current:** Live JSON feed containing every software project, updated automatically with each build.
* 🔒 **Zero-Dummy Security:** Byte-level SHA-256 checksum verification before installation.
* 🎯 **True Version-Picker:** Download the latest build or select any historical release with full changelog.
* 💻 **Multi-Platform:** Native Android APKs, standalone Linux ELF binaries (WebKitGTK), and Windows executables (App-Mode).
* 📱 **F-Droid Integration:** Also available via the official [myfdroid](https://benzjeremy.github.io/myfdroid/) repository.

```bash
# Quick install the BenzStore CLI via Go:
go install github.com/benzjeremy/benzstore@latest
```

---

### 🚀 Flagship Projects (3x Featured in Awesome-Go)

While all apps and tools can be explored directly in the **[BenzStore Catalog](https://benzjeremy.github.io/benzstore/)**, these three Go projects are officially recognized and listed in [Awesome-Go](https://github.com/avelino/awesome-go):

| Project | Description | Showcase & Source |
| :--- | :--- | :--- |
| 🔭 **[untis-go](https://github.com/benzjeremy/untis-go)** | Native Go WebUntis desktop client. Zero Electron, WebKitGTK shell, SQLite cache-first, M365 sync, AES-256-GCM vault & 60 FPS timetable matrix. | [Awesome-Go](https://github.com/avelino/awesome-go#other-software) · [Website](https://benzjeremy.github.io/untis-go/) · [GitHub](https://github.com/benzjeremy/untis-go) |
| ⚡ **[docklite](https://github.com/benzjeremy/docklite)** | Radically ultra-lightweight Docker manager in Go & Astro (~12 MB RAM). Direct `/var/run/docker.sock` API, live SSE telemetry & single binary. | [Awesome-Go](https://github.com/avelino/awesome-go#devops-tools) · [Website](https://benzjeremy.github.io/docklite/) · [GitHub](https://github.com/benzjeremy/docklite) |
| 🌌 **[spotify-screensaver](https://github.com/benzjeremy/spotify-screensaver)** | Elegant desktop screensaver with crisp OLED clock, MPRIS D-Bus Spotify metadata, 60 FPS canvas visualizer, ad handling & AES-256-GCM vault. | [Awesome-Go](https://github.com/avelino/awesome-go#other-software) · [Website](https://benzjeremy.github.io/spotify-screensaver/) · [GitHub](https://github.com/benzjeremy/spotify-screensaver) |

---

### 🛡️ Engineering Philosophy & Non-Negotiable Standards

- **Zero-Dummy Security:** Production-grade cryptography by default: **AES-256-GCM** with fresh random nonces, key derivation via **PBKDF2 with ≥100,000 iterations**, anti-CSRF origin checks, anti-DNS-rebinding protection, and strict localhost (`127.0.0.1`) binding.
- **Radically Lean & Native (Zero-Electron):** No 300+ MB Electron wrappers. Built in pure **Go with WebKitGTK / Win32 API**, starting in milliseconds and consuming only 10–25 MB RAM.
- **100% Local-First & Privacy:** Zero untracked telemetry, zero cloud lock-in, and full GDPR/DSGVO compliance. Complete offline availability for desktop binaries and Android APKs.
- **Free Software & SemVer Integrity:** Licensed under the **GNU General Public License v3.0 (GPL-3.0)**. Clean SemVer tagging without trailing zeros (e.g. `v1.4`, `v2.3`), automated CI/CD multi-platform builds, and public documentation.

---

### 🛠️ Core Tech Stack & Tooling

```
Systems & Backend   : Go (Golang) 1.22+, CGO, Docker Engine API, SQLite, UNIX Domain Sockets, Win32 Named Pipes
Desktop Native      : WebKitGTK, GTK3 (Wayland/X11 with DMABUF fix), HTML5 Canvas Hardware Visualizers
Mobile Native       : Android SDK / Java 17, Material Components, App Widgets, F-Droid Repository Standard
Security & Crypto   : AES-256-GCM, PBKDF2 (100k+), OAuth2 PKCE, Anti-CSRF, DNS-Rebinding Protection
Web & Showcase      : Astro, go:embed Single-Binary Distribution, Semantic HTML5, CSS3 Custom Properties
```

---

🌐 **Central Portfolio & Hub:** [benzjeremy.github.io](https://benzjeremy.github.io/) · **AppStore:** [benzjeremy.github.io/benzstore/](https://benzjeremy.github.io/benzstore/) · **Status:** [benzjeremy.github.io/status/](https://benzjeremy.github.io/status/)

<sub>📬 Contact: `benzjeremy@pm.me` · Please open a GitHub Issue in the respective project before emailing · Subject format: <code>[GITHUB] [PROJECT] [#ID]</code></sub>
