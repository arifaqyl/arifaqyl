<h1 align="center">Arif Aqyl</h1>

<p align="center">
Backend &amp; automation developer in Kuala Lumpur building <strong>live products for Malaysia</strong>.<br />
Two apps running in production on my own Raspberry Pi homelab, served through Cloudflare Tunnel.<br />
Shipped URLs, clean APIs, real uptime.
</p>

<p align="center">
  <a href="https://arifaqyl.me"><img src="https://img.shields.io/badge/Portfolio-arifaqyl.me-F2A33C?style=flat-square&logo=googlechrome&logoColor=black" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/arifaqyl"><img src="https://img.shields.io/badge/LinkedIn-arifaqyl-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://x.com/mindofaqyl"><img src="https://img.shields.io/badge/X-@mindofaqyl-000000?style=flat-square&logo=x&logoColor=white" alt="X" /></a>
  <a href="mailto:hello@arifaqyl.me"><img src="https://img.shields.io/badge/Email-hello@arifaqyl.me-F4EEE1?style=flat-square&logo=gmail&logoColor=black" alt="Email" /></a>
</p>

<p align="center">
  <img src="./images/chibi-uniform-transparent.png" width="200" alt="Chibi character in uniform" />
  <img src="./images/chibi-basketball-transparent.png" width="200" alt="Chibi character with basketball" />
</p>

## Live in production

| App | What it does | Link |
|-----|--------------|------|
| **TrafficMY** | Malaysia public transport pulse: multi-source ingest, rider signals, line board, journey planner. 246 tests green, 15-min refresh | [arifaqyl.me/traffic](https://arifaqyl.me/traffic/) |
| **Sah.Bukti** | WhatsApp-first collections control plane for micro-sellers. Order to invoice to review-gated ledger entry | [arifaqyl.me/sahbukti](https://arifaqyl.me/sahbukti/) |

Both run FastAPI + SQLite on a Pi 4 behind Cloudflare Tunnel. The infra is the flex: no rented cloud, just a box in my room that stays up.

## Selected work

| Project | What it does | Stack |
|---------|--------------|-------|
| **[aduanmy](https://github.com/arifaqyl/aduanmy)** | Production transport intelligence with strict scraper gates and a PWA front end | Python, FastAPI, SQLite, MapLibre, Playwright |
| **[sah-bukti](https://github.com/arifaqyl/sah-bukti)** | WhatsApp-first collections and evidence ledger for Malaysian micro-sellers | FastAPI, SQLite, React, WAHA |
| **[threadterm](https://github.com/arifaqyl/threadterm)** | Threads in your terminal: Bubble Tea TUI + JSON CLI, browser-cookie login, cross-platform releases | Go, Bubble Tea, Cobra, goreleaser |
| **[whatsapp-assignment-dashboard](https://github.com/arifaqyl/whatsapp-assignment-dashboard)** | 24/7 academic assistant: VLE scraping, WhatsApp-to-Telegram bridge, grounded daily agenda | Python, Playwright, Telegram API, WAHA |
| **[video-editing-automation](https://github.com/arifaqyl/video-editing-automation)** | Long raw footage to watchable cut: Whisper transcription and dead-air removal on GPU | Python, faster-whisper, ffmpeg, CUDA |
| **[flight-fare-monitor](https://github.com/arifaqyl/flight-fare-monitor)** | Fare history, threshold alerts, Telegram pings for cheap flights out of KL | Python, SQLite |

## How I build

- **Python + FastAPI** as the default backend lane; SQLite schemas that survive real usage
- **Automation first**: Playwright scrapers, Telegram bots, WhatsApp via WAHA, scheduled jobs
- **Ship it**: Docker Compose, PM2, nginx, Cloudflare Tunnel, Raspberry Pi homelab
- **Go** for fast single-binary CLI tools (Threadterm)

## Now

Closing the gap into harder backend and database work. Open to software engineering internships, KL or remote.

## Contact

- Portfolio: [arifaqyl.me](https://arifaqyl.me)
- LinkedIn: [linkedin.com/in/arifaqyl](https://linkedin.com/in/arifaqyl)
- X: [@mindofaqyl](https://x.com/mindofaqyl)
- Email: [hello@arifaqyl.me](mailto:hello@arifaqyl.me)

<p align="center">
  <sub>Kuala Lumpur · MYT</sub>
</p>
