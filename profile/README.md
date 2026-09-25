<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A0A14,50:2A1B5E,100:7A6CFF&height=250&section=header&text=algorithco-cli&fontSize=44&fontColor=F4F2FF&desc=Algo%20%E2%80%94%20intelligent%20control%20layer%20for%20CLI%20coding%20agents&descSize=15&descAlignY=80&animation=fadeIn" width="100%" alt="algorithco-cli header" />

<p align="center">
  <a href="https://github.com/algorithco-cli"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1400&color=7A6CFF&center=true&vCenter=true&width=760&lines=Secure+by+default;Reliable+in+production;Consistent+at+scale;Contracts+%2B+evidence%2C+always" alt="typing principles" /></a>
</p>

<p align="center">
  <img src="./logo.svg" width="110" height="110" alt="algorithco-cli logo" />
</p>

<p align="center">
  <strong>Policy-enforced guard between CLI agents and the shell.</strong><br />
  🏛️ An official organization of <a href="https://github.com/algorithco"><strong>Algorithco</strong></a> — builders of future technology.
</p>

<p align="center">
  <a href="https://github.com/algorithco-cli"><img src="https://img.shields.io/badge/org-algorithco--cli-0A0A14?style=for-the-badge&logo=github&logoColor=white" alt="org" /></a>
  <a href="https://github.com/algorithco-cli/algo"><img src="https://img.shields.io/badge/flagship-algo-7A6CFF?style=for-the-badge&logo=rust&logoColor=white" alt="flagship" /></a>
  <a href="https://github.com/algorithco"><img src="https://img.shields.io/badge/main-algorithco-000000?style=for-the-badge&logo=github&logoColor=white" alt="main org" /></a>
</p>

<p align="center">
  <a href="https://github.com/algorithco-cli/algo"><img src="https://img.shields.io/github/stars/algorithco-cli/algo?style=social" alt="stars" /></a>
  <a href="https://github.com/algorithco-cli/algo"><img src="https://img.shields.io/github/last-commit/algorithco-cli/algo?style=social" alt="last commit" /></a>
  <img src="https://img.shields.io/badge/location-Uzbekistan%20%C2%B7%20worldwide-lightgrey?style=social" alt="location" />
</p>

---

## 🚀 Flagship

<p align="center">
  <a href="https://github.com/algorithco-cli/algo">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=algorithco-cli&repo=algo&theme=transparent&hide_border=true&title_color=7A6CFF&text_color=E6E3FF&icon_color=7A6CFF&show_owner=true" alt="algo repo card" />
  </a>
</p>

> **Algo** puts contracts and evidence between the agent and the machine: every action is
> typed, policy-checked, and reversible — Phase 0 ships the proto contracts plus the eval
> harness that gates every threshold change.

<p align="center">
  <a href="https://github.com/algorithco-cli/algo"><img src="https://img.shields.io/badge/Explore_the_code-7A6CFF?style=for-the-badge&logo=github&logoColor=white" alt="explore" /></a>
  &nbsp;
  <a href="https://github.com/algorithco-cli/.github/issues"><img src="https://img.shields.io/badge/Ask_a_question-0A0A14?style=for-the-badge&logo=githubdiscussions&logoColor=white" alt="ask" /></a>
  &nbsp;
  <a href="../../security/advisories/new"><img src="https://img.shields.io/badge/Report_vulnerability-critical?style=for-the-badge&logo=dependabot&logoColor=white" alt="security" /></a>
</p>

## 🧭 How it works

```mermaid
flowchart LR
    A["🤖 CLI Agent"] -->|"proposes action"| B["🛡️ Algo Guard"]
    B -->|"policy check"| C{"allow / deny /\nredact?"}
    C -->|"allow"| D["💻 Shell & Tools"]
    C -->|"deny"| E["⛔ Blocked + evidence"]
    D -->|"receipt"| F["📦 Audit log"]
    E --> F
    style B fill:#7A6CFF,stroke:#0A0A14,color:#fff
    style C fill:#1B1533,stroke:#7A6CFF,color:#E6E3FF
    style F fill:#0A0A14,stroke:#7A6CFF,color:#E6E3FF
```

## 🛠️ Built with

<p align="center">
  <img src="https://skillicons.dev/icons?i=rust,ts,react,python,docker,kubernetes,githubactions,bash&theme=dark" alt="tech stack" />
</p>

## 📐 Principles

| Principle | What it means in practice |
|-----------|---------------------------|
| 🔐 **Secure by default** | Least privilege, secret scanning, reproducible builds — inherited, not bolted on |
| 📈 **Reliable in production** | Health checks, observability, and failure-mode thinking in every template |
| 🧩 **Consistent at scale** | One source of truth for policies, workflows, and community health files |

## 🛡️ Official organizations

| | Organization | Role |
|---|---|---|
| 🏢 | [**@algorithco**](https://github.com/algorithco) | Owner — products, platform, partnerships |
| 🛡️ | [**@algorithco-cli**](https://github.com/algorithco-cli) | This org — CLI guard, policies, tooling |

Only these two are official. Anything else claiming to be Algorithco is not affiliated.

<details>
<summary><strong>How to verify you're in the right place</strong></summary>
<br />

1. The URL is exactly `github.com/algorithco-cli`
2. The avatar matches the purple `>:` logo on `#0A0A14` (see [`profile/logo.svg`](./logo.svg))
3. It's cross-linked from the main [`algorithco`](https://github.com/algorithco) org

</details>

---

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7A6CFF,50:2A1B5E,100:0A0A14&height=130&section=footer&text=Secure%20by%20default&fontSize=22&fontColor=F4F2FF&animation=fadeIn" width="100%" alt="footer" />

<p align="center">
  <sub>© 2026 Algorithco · Uzbekistan · Working worldwide · <a href="https://github.com/algorithco">algorithco</a> · <a href="https://github.com/algorithco-cli">algorithco-cli</a></sub>
</p>
