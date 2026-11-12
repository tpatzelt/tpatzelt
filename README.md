```console
tim@lindus:~$ whoami
tim patzelt · senior ai engineer · berlin

tim@lindus:~$ cat ~/.plan
- make models run where the data lives, not where the API is
- measure first: evals > vibes > leaderboards
- reach for the small model when it is enough
- give agents a charter, a sandbox and a reviewer, then go to sleep

tim@lindus:~$ ls ~/past
nlp-research/  medical-language/  saliency-maps/  eye-tracking/

tim@lindus:~$ uptime
up since 2016, load average: too many side projects
```

[![Website](https://img.shields.io/badge/web-tim--boo.com-0A0A0A?style=flat-square)](https://tim-boo.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Tim%20Patzelt-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tim-patzelt-3248a1168)
[![arXiv](https://img.shields.io/badge/arXiv-2409.14579-B31B1B?style=flat-square&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2409.14579)

---

### Live projects

| Project | What it does | Stack |
|---|---|---|
| **[Mein Pendel](https://github.com/tpatzelt/mein-pendel)** · [live](https://pendel.tim-boo.com/today) | Watches your Berlin commute and messages you, via Telegram or ntfy, only when it is actually disrupted. It also warns about planned works days ahead and suggests an alternative connection. | Python, FastAPI, SQLite, HAFAS |
| **[Wie Berlin radelt](https://github.com/tpatzelt/berlin-bike-data)** · [live](https://bikes.tim-boo.com) | A bilingual data article on where and when Berlin's shared bikes run out. It is built from its own GBFS snapshot history, with weather joins and an interactive station map. | Python, DuckDB, Parquet, SVG, Leaflet |

### Agents and developer tooling

- **[nightshift](https://github.com/tpatzelt/nightshift)**: an autonomous Claude Code runner that sticks to a plan. A planner, sandboxed workers and reviewers work from a charter under hard gates, and it has shipped several hundred merged changes to the projects above.
- **[job-application-agent](https://github.com/tpatzelt/job-application-agent)**: a plan → act → reflect agent that finds job listings and scores them against a CV, with an offline harness for evaluating result quality.
- **[pr-review-bot](https://github.com/tpatzelt/pr-review-bot)**: like Dependabot, but it reviews pull requests.
- **[djcc](https://github.com/tpatzelt/djcc)**: a live techno DJ that Claude Code can drive, with a beat-matched mixing engine, prompt steering and a Rekordbox-style web UI.

### Research

- **[Medical concept normalization in a low-resource setting](https://github.com/tpatzelt/medical-lay)** ([arXiv:2409.14579](https://arxiv.org/abs/2409.14579)): normalizing German medical forum posts to UMLS concepts with multilingual Transformers (SapBERT).
- **[Drowsiness detection](https://github.com/tpatzelt/drowsiness-detection)**: learned features (CNNs, LSTMs) compared with engineered features for detecting drowsiness from eye-tracking data.
- **[best-attributions](https://github.com/tpatzelt/best-attributions)**: saliency maps formulated as an optimization problem.

### Infrastructure and Linux

- **[homelab](https://github.com/tpatzelt/homelab)**: Docker Compose stacks behind Caddy and Cloudflare Tunnel, with Prometheus and Grafana monitoring, Renovate-pinned images and weekly verified restic backups.
- **Omarchy bar widgets** ([VPN](https://github.com/tpatzelt/omarchy-vpn-widget) · [systemd](https://github.com/tpatzelt/omarchy-systemd-widget) · [peripherals](https://github.com/tpatzelt/omarchy-peripherals) · [disk space](https://github.com/tpatzelt/omarchy-diskspace) · [sysmon](https://github.com/tpatzelt/omarchy-sysmon)): small QML/Quickshell status widgets with no extra dependencies.

### Toolbox

`Python` · `PyTorch` · `Hugging Face Transformers` · `FastAPI` · `React/TypeScript` · `PostgreSQL` · `DuckDB` · `SQLite` · `LLM agents` · `Claude Code` · `Docker` · `Caddy` · `Prometheus/Grafana` · `GitHub Actions` · `Linux`
