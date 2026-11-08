<div align="center">

# Tenerit

### I build local-first AI products · your data stays on your machine

<br/>

DevOps engineer turned product builder, based in France.<br/>
Small LLMs, **bounded and measured**, running where the data already lives —<br/>
for trades, regulated teams and developers who can't ship their data to a cloud.

</div>

---

## 🔨 Building now

**HVAC-Flow** — the assistant for heating & cooling technicians. Dictate the job on
site, get the report, the quote and the invoice. Voice-first, phone-first, installed on
the company's own machine. Issues **Factur-X / EN 16931** e-invoices (ready for the
2027 French mandate), chases unpaid invoices, reminds clients of their yearly
maintenance. Local Whisper dictation + local TTS, one LLM call per job, cached.
*Private — looking for pilot companies.*

**CronGuard** — self-hosted cron-job monitoring with **local-LLM root-cause analysis**.
Detects misses, duration drift and failures, then explains *why* and who to wake.
No logs leave your server. *Private beta.*

**Recevable** — pre-fills the security questionnaires (NIS2 · ISO 27001 · DORA) that
big clients send to small IT suppliers. Answers grounded in your real practices,
never "in place" without proof, human sign-off before export. *In development.*

---

## 🧰 Open source

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/Tenerit/boardroom"><img src="https://raw.githubusercontent.com/Tenerit/boardroom/master/assets/social-preview.png" alt="boardroom" /></a>

### 🪑 [boardroom](https://github.com/Tenerit/boardroom)
A whole-project **review board** for Claude Code. Expert hats (architect, security,
SRE, product, investor, skeptic…) review your project in parallel and hand you a
**GO/NO-GO decision** plus the trade-offs only you can settle.

```
/plugin marketplace add Tenerit/boardroom
```

![last commit](https://img.shields.io/github/last-commit/Tenerit/boardroom?style=flat&color=8B5CF6&labelColor=161b22)

</td>
<td width="50%" valign="top">

<a href="https://github.com/Tenerit/ccx"><img src="https://raw.githubusercontent.com/Tenerit/ccx/master/assets/social-preview.png" alt="ccx" /></a>

### 🩻 [ccx](https://github.com/Tenerit/ccx)
**Claude Code X-Ray** — cross-session cost & token-waste analytics from the logs
Claude Code already writes. See what your sessions cost and what quietly burned
tokens. Zero network, zero deps.

```
npx @tenerit/ccx cost
```

![last commit](https://img.shields.io/github/last-commit/Tenerit/ccx?style=flat&color=34d399&labelColor=161b22)

</td>
</tr>
</table>

---

## 🧭 How I build

- **Local first** — the model goes to the data, not the other way round
- **Measured, not claimed** — eval harnesses, repeated runs, honest error bars
- **Token-frugal** — cache recurring inputs, bound every prompt, one call where others make five
- **Useful before complete** — tools that hand you a **decision**, not just data

---

## 🛠️ Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
