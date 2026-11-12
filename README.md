# Tim Patzelt

**Senior AI Engineer · Berlin**

I build ML and LLM systems and ship them as small, well-tested software that runs in
production. My background is in NLP research, especially medical language.

By day I'm a Senior AI Engineer at an IT consultancy, building AI applications for
clients whose data must stay on their own infrastructure. That means:

- **On-premise LLM applications**: structured extraction and description from documents
  and images, served behind FastAPI backends and React frontends, with open-weight models
  running locally rather than through external APIs.
- **Model evaluation before rollout**: task-specific evaluation sets and side-by-side
  comparisons of open-weight models, so model choices rest on measured accuracy rather
  than leaderboards.
- **Classic ML where it fits**: compact vision classifiers (e.g. EfficientNet on CPU)
  combined with LLM steps, when a small model is cheaper, faster and easier to audit.

In my own time I build agentic tooling and the infrastructure that keeps it reliable.

[![Website](https://img.shields.io/badge/web-tpatzelt.github.io-0A0A0A?style=flat-square)](https://tpatzelt.github.io)
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
