<h1 align="center">Arif Aqyl</h1>

<p align="center">
Backend &amp; automation developer in Kuala Lumpur building <strong>software for Malaysia</strong>.<br />
Two apps in production on a Raspberry Pi in my room, and a set of open-source libraries<br />
that get Malaysian rules right and cite where they come from.
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

## Libraries for Malaysian developers

Small, dependency-free Python packages. Each one takes a rule that every
Malaysian codebase reimplements badly, does it from the primary source,
and tests it against published figures. CLI, type hints, CI.

| Package | What it gets right | Verified against |
|---|---|---|
| **[gaji](https://github.com/arifaqyl/gaji)** | Take-home pay: EPF, SOCSO, EIS and monthly PCB, including the s6A rebate most calculators forget. Reverse mode: gross for a target net. | KWSP Third Schedule, PERKESO band tables, LHDN YA2025. 209 tests |
| **[cuti](https://github.com/arifaqyl/cuti)** | Public holidays for all sixteen states, Friday–Saturday weekends, opt-in replacement days. A subscribable `.ics` feed per state. | The JPM gazette, row by row. 40 tests |
| **[sahih](https://github.com/arifaqyl/sahih)** | MyKad, phone numbers, postcodes and plates, validated against the published rules, honest about what a number does not tell you. | JPN, MCMC numbering plan, Pos Malaysia. 80 tests |
| **[tnb](https://github.com/arifaqyl/tnb)** | Your electricity bill line by line on the July 2025 tariff, including which lines SST and KWTBB actually apply to. | Six published bill totals reproduced to the sen. 15 tests |
| **[kwsp](https://github.com/arifaqyl/kwsp)** | EPF dividend history and a retirement projection on EPF's aggregate-balance method, stating the rate it assumed. | KWSP declared rates, three sources cross-checked. 20 tests |
| **[ringgit](https://github.com/arifaqyl/ringgit)** | Money as `Decimal`: BNM 5-sen cash rounding, SST by category, amounts in Malay words for cheques. Floats refused. | BNM rounding mechanism, RMCD MySST. 47 tests |
| **[duitnow](https://github.com/arifaqyl/duitnow)** | Parse and validate DuitNow / EMVCo QR payloads: TLV, CRC-16, merchant fields. Builds valid payloads. | EMVCo MPM spec and its CRC check value. 10 tests |

```
pip install gaji cuti sahih tnb kwsp ringgit duitnow
```

## Live in production

| App | What it does | Link |
|-----|--------------|------|
| **TrafficMY** | Malaysia public transport pulse: multi-source ingest, deviation detection, line board, journey planner. Refreshes every 15 minutes. | [arifaqyl.me/traffic](https://arifaqyl.me/traffic/) |
| **Sah.Bukti** | WhatsApp-first collections control plane for micro-sellers. Order to invoice to review-gated ledger entry. | [arifaqyl.me/sahbukti](https://arifaqyl.me/sahbukti/) |

Both run FastAPI + SQLite on a Pi 4 behind Cloudflare Tunnel with no open
ports. **[pi-lab](https://github.com/arifaqyl/pi-lab)** is the runbook:
the real configs with secrets stripped, and what broke along the way.

## Earlier work

| Project | What it does | Stack |
|---------|--------------|-------|
| **[aduanmy](https://github.com/arifaqyl/aduanmy)** | TrafficMY's source: scraper gates, headway deviation engine, PWA front end | Python, FastAPI, SQLite, MapLibre, Playwright |
| **[sah-bukti](https://github.com/arifaqyl/sah-bukti)** | Sah.Bukti's source | FastAPI, SQLite, React, WAHA |
| **[threadterm](https://github.com/arifaqyl/threadterm)** | Threads in your terminal: Bubble Tea TUI + JSON CLI, cross-platform releases | Go, Bubble Tea, Cobra, goreleaser |
| **[whatsapp-assignment-dashboard](https://github.com/arifaqyl/whatsapp-assignment-dashboard)** | 24/7 academic assistant: VLE scraping, WhatsApp-to-Telegram bridge, daily agenda | Python, Playwright, Telegram API, WAHA |
| **[video-editing-automation](https://github.com/arifaqyl/video-editing-automation)** | Long raw footage to watchable cut: Whisper transcription and dead-air removal on GPU | Python, faster-whisper, ffmpeg, CUDA |
| **[flight-fare-monitor](https://github.com/arifaqyl/flight-fare-monitor)** | Fare history, threshold alerts, Telegram pings for cheap flights out of KL | Python, SQLite |

## How I build

- **Primary sources first.** A gazette, a statute schedule, a published tariff. Then tests that pin the arithmetic to published figures.
- **Python + FastAPI** for services, **SQLite** for state, `Decimal` for money.
- **Automation**: Playwright scrapers, Telegram bots, WhatsApp via WAHA, scheduled jobs that page on transitions, not on every run.
- **Ship it**: PM2, nginx, Cloudflare Tunnel, a Raspberry Pi that stays up.
- **Go** for single-binary CLI tools.

## Now

Software engineering student at UniKL MIIT. Open to software engineering internships, KL or remote.

## Contact

- Portfolio: [arifaqyl.me](https://arifaqyl.me)
- LinkedIn: [linkedin.com/in/arifaqyl](https://linkedin.com/in/arifaqyl)
- X: [@mindofaqyl](https://x.com/mindofaqyl)
- Email: [hello@arifaqyl.me](mailto:hello@arifaqyl.me)

<p align="center">
  <sub>Kuala Lumpur · MYT</sub>
</p>
