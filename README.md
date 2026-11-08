<div align="center">

# Tenerit

### DevOps engineer · I build self-hosted ops tools with local AI

<br/>

Your logs are sensitive. Your jobs are critical. Your AI should run **on your servers**.<br/>
I build monitoring tools for ops teams in **regulated and air-gapped** environments —<br/>
where nothing is allowed to leave the infra.

</div>

---

## 🛡️ CronGuard — cron monitoring that tells you *why* it broke

Your nightly backup fails. Here is what each tool tells you:

> **A classic monitor:**
> 🔴 `backup is DOWN`

> **CronGuard:**
> 🔴 `backup failed (exit 1) — severity: critical`
> **Cause:** disk full
> **Lead to verify:** grow the disk or move the backup target to a larger volume

One alert is a notification. The other is a head start on the diagnosis.

- ⏰ **Cron-aware detection** — missed, late, hung, failed, and *duration drift*
- 🧠 **Local-LLM root cause** — reads the logs, gives cause, fix and prevention · runs on Ollama, **no log egress**
- 🔁 **Incident memory** — recognises a failure it has already seen and what fixed it last time
- 🔌 **Air-gap ready** — offline bundle with checksums, one container, no network needed
- 📈 **Ops-native** — Prometheus metrics + ready alert rules, dead-letter queue, automatic backups
- 🧪 **Measured, not claimed** — eval harness with repeated runs and published error bars

**For:** ops / SRE / data teams whose critical crons (backups, ETL, billing sync) can't ship
logs to a third-party SaaS.

> 🤝 **Looking for design partners** — if you run critical cron jobs in a regulated or
> air-gapped environment, I'd love to hear how you monitor them today.
> **→ [Tell me about your setup](https://github.com/Tenerit/Tenerit/issues/new?title=CronGuard%20design%20partner&body=Team%20%2F%20sector%3A%0AHow%20many%20cron%20jobs%3A%0AHow%20you%20monitor%20them%20today%3A%0AAir-gapped%20or%20regulated%3F%3A)**

---

## 🧰 Also from me

### 🪑 [boardroom](https://github.com/Tenerit/boardroom)
A whole-project **review board** for Claude Code. Expert hats (architect, security,
SRE, product, investor, skeptic…) review your project in parallel and hand you a
**GO/NO-GO decision** plus the trade-offs only you can settle. Built to review CronGuard
before shipping it.

```
/plugin marketplace add Tenerit/boardroom
```

![last commit](https://img.shields.io/github/last-commit/Tenerit/boardroom?style=flat&color=8B5CF6&labelColor=161b22)

---

## 🧭 How I build

- **Local first** — the model goes to the data, not the other way round
- **Fail loud** — a missing ping is not "no problem"; silent degradation is the real enemy
- **Measured, not claimed** — honest numbers, repeated runs, error bars
- **Token-frugal** — cache recurring inputs, bound every prompt, one call where others make five

---

## 🛠️ Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
