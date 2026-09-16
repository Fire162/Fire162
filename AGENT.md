# Agent Guide — Fire162 Profile Repository

This document serves as the persistent guide and reference for AI coding agents (`agy`) working on the `Fire162/Fire162` repository.

---

## 📌 Repository Overview

* **Repository**: `Fire162/Fire162`
* **Purpose**: Special GitHub profile repository rendered on the public GitHub profile page ([github.com/Fire162](https://github.com/Fire162)).
* **Primary Language**: Markdown (`README.md`), HTML.
* **Owner**: Abhinav Maurya ([@Fire162](https://github.com/Fire162)).

---

## 🏗️ Architecture & Conventions

1. **Profile Layout Structure (`README.md`)**:
   * **Hero Header**: Capsule Render wave banner, profile title, bio, and social badge links (Instagram, Email).
   * **About Me**: Core background, development philosophy, and areas of expertise.
   * **Key Scale & Milestones**: Table of reach metrics (3M+ users, 100K+ community, Fire PM, VPS infrastructure).
   * **Featured Open-Source Projects**: Responsive multi-column HTML grid (`<table><tr><td width="50%">...</td></tr></table>`) featuring flagship tools with live GitHub star badges and MIT license indicators.
   * **What I Build & Capabilities**: Detailed domain breakdown (AI & Intelligent Systems, Developer Infrastructure, Browser Extensions, Telegram Microservices, Full-Stack Apps).
   * **Tech Stack**: Skillicons dark theme icon set.
   * **Open to Collaborations**: Collaboration scope and value proposition.
   * **Crypto Support**: Multi-chain cryptocurrency donation table.
   * **GitHub Stats**: Streak stats and activity graph widgets.
   * **Footer**: Capsule Render footer with sign-off quote.

2. **Design & Styling Rules**:
   * **Badge Theme**: Shields.io flat-square style (`style=flat-square`) with `#32B88D` accent color.
   * **Grid System**: Use GitHub-native HTML `<table>` blocks with `valign="top"` and percentages (`colspan="2"`, `width="50%"`) rather than external image generators for cards, ensuring 100% uptime and resilience against 3rd-party rendering service outages.
   * **Badges**: Use Shields.io badges for dynamic GitHub stars, licenses, and platforms.

3. **Infrastructure Privacy & IP Leak Prevention**:
   * **Absolute Confidentiality**: Never write, expose, or commit server IP addresses (VPS IPv4/IPv6, gateway, private subnets) or private tokens to ANY file in this repository.
   * **Placeholder Standard**: Always use `<your-vps-ip>` or documentation IP `192.0.2.1` (RFC 5737).

---

## ⚡ Development & Git Workflow

* **Working Branch**: `main`
* **Pre-Commit Audit**:
  * Run `git diff` to verify changes.
  * Proactively scan for any IPv4 address patterns or API keys before staging.
* **Push**:
  * Changes to `main` directly reflect on the GitHub profile page.
  * Use concise, conventional commit messages (`feat: ...`, `fix: ...`, `docs: ...`).
