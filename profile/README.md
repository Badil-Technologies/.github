<div align="center">

<img src="https://avatars.githubusercontent.com/u/254782626?s=200&v=4" alt="Black Belt Technologies" width="110" />

# Black Belt Technologies

**Fundamentals first. No shortcuts.**

Welcome, developer 👋 This page is a quick tour of who we are, what we're building, and how to find your way around our code.

</div>

---

## 🥋 TL;DR

- We're a small, hands-on engineering team
- Our current focus is **Ikimasho**, a travel planning app (details below)
- We care about clean code, written-down decisions, and automation
- New here? Read [Getting started](#-getting-started), then pick an issue labelled `good first issue`

---

## ⛩️ Now building: Ikimasho

> **行きましょう (Ikimasho)** means *"let's go!"* in Japanese.

Ikimasho is a **mobile travel planning app** with two goals:

1. **🧭 Turn the trip-planning nightmare into a few clicks.** No more juggling tabs, spreadsheets, booking emails and screenshots. Everything lives in **one centralized app** that's easy to use.
2. **📖 Make every trip part of your portfolio.** Each trip you plan and take is saved and can be **shared** with friends, family and fellow travellers.

### ✨ Features

| Feature | What it does |
|---|---|
| 🗺️ **Trip planning** | Build your itinerary and follow your route in one place |
| 📖 **Shareable trip portfolio** | Keep a collection of your trips and share it |
| 🏮 **Digital passport** | A travel passport that fills up as you explore |
| 🔴 **Verified-route stamps** | Completing a verified route earns a **hanko-style stamp** for your passport |

**Status:** 🚧 Under active development

<details>
<summary><b>🎨 Brand palette: Sumi · Washi · Shu</b> (use these tokens in the UI, don't hard-code new colors)</summary>

| Token | Name | Hex | Use |
|---|---|---|---|
| `sumi` | Sumi ink | `#16130F` | Text, dark surfaces |
| `washi` | Washi paper | `#F6F2E9` | Backgrounds |
| `shu` | Shu vermilion | `#D9482E` | Primary accent, CTAs |
| `ai` | Ai indigo | `#233B53` | Secondary |
| `kin` | Kin gold | `#C9A24B` | Highlights, stamps |
| `gray` | Warm gray | `#8A8275` | Muted text, borders |

</details>

---

## 🧰 Tech stack

### 📱 Frontend

<!-- TODO: replace with the actual Ikimasho frontend stack (framework, language, state management, styling, testing). -->

<p>
  <img src="https://img.shields.io/badge/Framework-TBD-D9482E?style=flat-square" alt="Framework: TBD" />
  <img src="https://img.shields.io/badge/Language-TBD-233B53?style=flat-square" alt="Language: TBD" />
  <img src="https://img.shields.io/badge/Styling-TBD-C9A24B?style=flat-square" alt="Styling: TBD" />
</p>

### ⚙️ Backend & infrastructure

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" alt="Terraform" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

---

## 🚀 Getting started

1. **Get access.** Ask a maintainer to add you to the org and the right team.
2. **Clone what you need.** Every repo has a `README.md` with local setup steps.
   ```bash
   gh repo clone Badil-Technologies/<repo>
   ```
3. **Run it locally.** Each repo should start with one command, for example `make dev` or `docker compose up`. If it doesn't, that's a bug. Please open an issue.
4. **Pick something to work on.** Look for `good first issue` or `help wanted` labels.

---

## 📐 How we work

| Area | Convention |
|---|---|
| **Branches** | `main` is always deployable. Use short-lived branches: `feat/…`, `fix/…`, `chore/…` |
| **Commits** | [Conventional Commits](https://www.conventionalcommits.org/), for example `feat(passport): add stamp animation` |
| **Pull requests** | Keep them small and focused, with at least one review, and CI must be green before merging |
| **Decisions** | Significant technical choices are written down as ADRs in `docs/adr/` |
| **Infrastructure** | Everything is code. Nothing gets changed by clicking around in a cloud console |
| **Secrets** | Never commit them. Use the secret manager and `.env.example` files |
| **Tests** | New behaviour comes with tests. Bug fixes come with a test that reproduces the bug |

### 🥋 Our principles

- **Simple over clever.** Code is read far more often than it is written.
- **Write it down.** If it's not documented, it doesn't exist.
- **Automate the boring parts.** Formatting, linting, testing and releases all run in CI.
- **Own it end to end.** You build it, you ship it, you watch it in production.

---

## 🤝 Contributing

- Read the `CONTRIBUTING.md` in the repo you're working on.
- Open an issue before you start a large change, so we can agree on the approach.
- Be kind and constructive. We follow a Code of Conduct.
- Found a security issue? Don't open a public issue. Contact the maintainers privately.

---

## 📬 Contact

Questions, ideas, or want to join? Reach out at **[contact@example.com](mailto:contact@example.com)** or start a GitHub Discussion.

<div align="center">

---

<sub>© 2026 Black Belt Technologies · 行きましょう!</sub>

</div>
