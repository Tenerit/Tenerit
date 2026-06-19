<div align="center">

# Tenerit

### DevOps engineer · I ship privacy-first developer tools

<br/>

Infra by day, side projects by night.<br/>
I build small, sharp, **local-first developer tools** — and the occasional SaaS.

</div>

---

## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/Tenerit/boardroom"><img src="https://raw.githubusercontent.com/Tenerit/boardroom/master/assets/social-preview.png" alt="boardroom" /></a>

### 🪑 [boardroom](https://github.com/Tenerit/boardroom)
A whole-project **review board** for Claude Code. A panel of expert hats reviews
your project in parallel and hands you a **GO/NO-GO decision** plus the
cross-discipline trade-offs only you can settle.

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

<details>
<summary>👀 <b>Peek at a real boardroom review</b> (click to expand)</summary>

<br/>

```
# Boardroom review — acme-billing

## Decision: NOT YET
Core billing logic is solid, but a money-touching race condition and an
unauthenticated webhook make this unsafe for paying customers. Two fixes gate it.

## Decisions for you  (no single right answer — you choose)
- Hit the announced EU launch date vs add idempotency first.
  Product wants the date; SRE + Security show the retry path can double-bill.
  → What resolves it: slip one week, or gate EU behind a flag until it lands?

## Scorecard
| Hat       | Score | Verdict                          |
| Security  | 4/10  | unauth webhook + a secret in repo|
| SRE       | 5/10  | charge retry can double-bill     |
| Architect | 7/10  | clean; slight over-abstraction   |
| Product   | 7/10  | sharp ICP, tight scope           |

## Top risks
1. 🔴 Unauthenticated webhook → forged payment events  (src/webhooks/stripe.ts:34)
2. 🔴 Charge retry double-bills on timeout            (src/billing/charge.ts:88)
```

</details>

---

## 🧪 Also building

**CronGuard** — self-hosted cron-job monitoring with **local-LLM root-cause
analysis**. Detects misses, duration drift, and failures, then explains *why* and
who to wake. No logs leave your server.

---

## 🧭 What I care about

- **Token-efficient LLM tooling** — cut cost without cutting quality
- **Local-first & privacy-respecting** — your data stays on your machine
- Tools that hand you a **decision**, not just data

---

## 🧰 Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
