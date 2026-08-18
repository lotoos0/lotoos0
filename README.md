<p align="center">
  <img src="./assets/operator-systems-hero.png" width="100%" alt="GitOps delivery loop from Git through CI/CD, registry, Kubernetes, and observability" />
</p>

<h1 align="center">Tomasz <code>/lotoos0</code></h1>

<p align="center">
  <strong>DevOps · SRE · Automation</strong><br />
  I build practical systems for what happens after the happy path ends:<br />
  visible failures, repeatable delivery, and recovery paths people can actually follow.
</p>

<p align="center">
  <a href="https://www.linux.org/"><img alt="Linux" src="https://img.shields.io/badge/Linux-111827?style=flat-square&logo=linux&logoColor=white" /></a>
  <a href="https://www.docker.com/"><img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" /></a>
  <a href="https://kubernetes.io/"><img alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" /></a>
  <a href="https://www.python.org/"><img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" /></a>
  <a href="https://www.typescriptlang.org/"><img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" /></a>
</p>

---

## Featured systems

### [`resilience-lab`](https://github.com/lotoos0/resilience-lab)

**Reliability · SRE · failure engineering**

Most demo systems prove the happy path. I built this one for what happens after the timeout, 5xx, or pod kill. FastAPI services, Redis, and Envoy run on Kubernetes while Prometheus, Grafana, Loki, alerts, and runbooks make failures visible before troubleshooting turns into guesswork.

**Current state:** `v0.1.0 released` · end-to-end stack validated · resilience experiments documented

`Kubernetes` `Helm` `FastAPI` `Envoy` `Prometheus` `Grafana` `Loki` `GitHub Actions`

### [`gitops-cloud-lab`](https://github.com/lotoos0/gitops-cloud-lab)

**GitOps · delivery · promotion · rollback**

The application is deliberately simple; the delivery path is the project. One FastAPI service moves through GitHub Actions → GHCR → Git → Argo CD → Kubernetes. Dev updates automatically, while production promotion remains an explicit pull-request decision. No cloud bill and no hidden deploy button.

**Current state:** `scope complete` · two environments · promotion, rollback, and failure paths documented

`kind` `GitHub Actions` `GHCR` `Helm` `Argo CD` `Kubernetes`

---

## Other things I build

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/lotoos0/discord-bot">discord-bot</a></h3>
      <p>A multi-guild music bot where <code>/play</code> is the easy part. The useful engineering is isolated per-guild state, asynchronous playlist work, tested cleanup paths, and a Docker-ready runtime.</p>
      <p><code>Python</code> <code>discord.py</code> <code>asyncio</code> <code>unittest</code> <code>Docker</code></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/lotoos0/memex-sim">memex-sim</a></h3>
      <p>A DEX-style simulator that turns synthetic candles, market events, positions, and PnL into a stateful domain model — not just a chart with Buy and Sell buttons.</p>
      <p><code>React</code> <code>TypeScript</code> <code>Zustand</code> <code>Lightweight Charts</code></p>
    </td>
  </tr>
</table>

## Current focus

- Hardening `resilience-lab` after v0.1.0 and turning experiments into useful recovery documentation.
- Improving the boring but important parts: delivery paths, failure evidence, rollback, and runbooks.

## Toolbox

| Build | Operate | Observe | Deliver |
| --- | --- | --- | --- |
| Python, FastAPI | Linux, Docker | Prometheus, Grafana | Git, GitHub Actions |
| TypeScript, React | Kubernetes, Helm | Loki, Envoy | GitLab CI/CD |
| Bash, automation | Terraform, AWS | Chaos engineering | Tests, docs, runbooks |

## Operating principles

```text
01  Ship small slices with clear completion criteria.
02  Measure the system, not the intention.
03  Document decisions and recovery paths.
04  Prefer repeatable systems over heroic effort.
```

## Say hello

<p>
  <a href="mailto:lotoos1998@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-lotoos1998%40gmail.com-0B1220?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/lotoos0"><img alt="GitHub profile" src="https://img.shields.io/badge/GitHub-%40lotoos0-0B1220?style=flat-square&logo=github&logoColor=white" /></a>
</p>
