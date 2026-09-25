<p align="center">
  <img src="./logo.svg" width="140" height="140" alt="algorithco-cli logo" />
</p>

<h1 align="center">algorithco-cli</h1>

<p align="center">
  <strong>Algo — intelligent control layer for CLI coding agents, part of <a href="https://github.com/algorithco">Algorithco</a> — Builders of future technology</strong><br/>
  <em>Policies • Guardrails • Hardening • Reusable workflows</em>
</p>

<p align="center">
  <a href="https://github.com/algorithco-cli"><img src="https://img.shields.io/badge/org-algorithco--cli-0A0A14?logo=github&logoColor=white" alt="org" /></a>
  <a href="https://github.com/algorithco"><img src="https://img.shields.io/badge/main-algorithco-black?logo=github&logoColor=white" alt="main org" /></a>
  <a href="https://github.com/algorithco-cli/.github"><img src="https://img.shields.io/badge/profile-.github-1e81b0" alt="profile" /></a>
  <img src="https://img.shields.io/badge/security-guard-7A6CFF" alt="security" />
  <img src="https://img.shields.io/badge/location-Uzbekistan-lightgrey" alt="location" />
</p>

> **Official organization.** `@algorithco-cli` is the dedicated CLI / guard organization of [`@algorithco`](https://github.com/algorithco). All repositories and assets under this org are owned, reviewed, and maintained by the Algorithco core team.

---

## About

**algorithco-cli** exists to make every Algorithco project secure by default and reliable in production. Where `algorithco` ships products, `algorithco-cli` ships the control layer and constraints that keep them safe — policies, templates, reusable workflows, and hardening guides that are enforced across the entire ecosystem.

We sit between product and platform: we define the non-negotiables (secret scanning, least privilege, supply-chain provenance, reproducible builds) and provide the tooling to satisfy them without slowing teams down.

Main build: [`algorithco-cli/algo`](https://github.com/algorithco-cli/algo) — intelligent control layer for CLI coding agents (Phase 0 contracts + evidence).

## Mission

- **Secure by default** — every new repository inherits guardrails; security is not an afterthought.
- **Reliable in production** — health checks, observability, and failure-mode thinking baked into templates.
- **Consistent at scale** — one source of truth for community health files, workflows, and policies across all orgs.

## Scope

| Area | What we provide | Where it enforces |
|------|-----------------|-------------------|
| **Guardrails** | Branch protection, CODEOWNERS, secret scanning, push protections | All `algorithco` / `algorithco-cli` repos |
| **Policies & templates** | `SECURITY.md`, `CONTRIBUTING.md`, issue/PR templates, license headers | Org-wide community health (`.github`) |
| **Reusable workflows** | CodeQL, Gitleaks, Trivy, ESLint/Prettier, `tsc`, Docker provenance | GitHub Actions (central, versioned) |
| **Hardening guides** | W5 signer isolation, `x-api-key` + `initData` HMAC, rate limits, non-root containers | Referenced by `p2p`, `lms`, `algorithvoice` |
| **Research** | Public threat models, supply-chain notes, and post-mortems | Published here when ready |

> This org currently hosts the profile and health files. Guardrail repos and workflow catalog will appear here as they graduate from the main org.

## How we work

- **Least privilege & isolation** — signer secrets never leave `signer`, `x-api-key` between services, no env baked into images.
- **Provenance & reproducibility** — Docker builds with attestations, `checksums.txt` + cosign, Conventional Commits + release-please.
- **Detection before merge** — CodeQL, Gitleaks, Trivy, and `npm audit` are blocking checks on every PR (see `p2p` as reference implementation).
- **Small, senior, accountable** — guard changes are PR → green CI → review → squash-merge; no direct pushes to `main`.

## Trust & authenticity

To prevent impersonation, only two organizations are official:

- **Product org:** [`github.com/algorithco`](https://github.com/algorithco)
- **CLI / Guard org:** [`github.com/algorithco-cli`](https://github.com/algorithco-cli) (this org)

Any other account or organization claiming to be Algorithco is not affiliated.

**Verify you are in the right place:**
1. Check the URL is exactly `github.com/algorithco-cli`
2. Check the org avatar matches the purple `>:` logo on `#0A0A14` (see `profile/logo.svg`)
3. Cross-reference from the main org: [`algorithco` profile links here](https://github.com/algorithco)

## Community health

This repository ([`algorithco-cli/.github`](https://github.com/algorithco-cli/.github)) provides org-wide defaults:

- `profile/README.md` — this page (rendered on the org overview)
- `SECURITY.md` / `CONTRIBUTING.md` / `CODE_OF_CONDUCT.md` — applied to repos without their own file
- Issue and PR templates — (added as needed)

Repos with their own file override the default; the default is the fallback.

## Contact

- **Main org:** [@algorithco](https://github.com/algorithco) — product issues and partnerships
- **This org:** [Open an issue here](https://github.com/algorithco-cli/.github/issues) for guard/policy questions

For security disclosures, use the **Security** tab of the affected repository (private advisory) — never file a public issue for a vulnerability.

---

<p align="center">
  <sub>© 2026 Algorithco — Builders of future technology · algorithco-cli operated by Algorithco core team · Uzbekistan · Working worldwide</sub><br/>
  <sub><a href="https://github.com/algorithco">algorithco</a> · <a href="https://github.com/algorithco-cli">algorithco-cli</a> · <a href="https://github.com/algorithco-cli/.github/blob/main/profile/README.md">profile source</a></sub>
</p>
