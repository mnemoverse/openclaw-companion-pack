---
title: OpenClaw Essentials
---

# OpenClaw Essentials

**Two books. One clean path.**
Get from **zero** to a **private-by-default OpenClaw gateway** — then continue with the flagship security-first operator manual.

---

## What this is

OpenClaw Essentials is a small, practical series for people who want a self-hosted agent platform they can actually run.

- **Vol. 1** gets you from **nothing** to **gateway alive** (official Ansible path).
- **Vol. 2** (*OpenClaw Made Safe*) teaches the real operator discipline: safe workflows, boundaries, recipes, and emergency procedures.

This page is the simplest place to start.

---

## Who this is for

You are in the right place if you are:

- setting up OpenClaw for the first time
- comfortable using a terminal (or willing to learn basic SSH)
- looking for a **repeatable** setup you can verify with checklists

You are *not* the target audience if you want a "no-terminal" experience.

---

## The two books (and how they fit)

### Vol. 1 — *Your First OpenClaw*

**From Zero to Gateway Alive (An Operator Setup Guide)**

This short runbook covers only the gap the flagship intentionally does not:

- pick a small VPS with SSH
- bootstrap the host safely (user, SSH lockdown, updates, UFW)
- install OpenClaw via the **official Ansible** path
- verify the gateway is alive, private-by-default, and stable across reboots
- stop and hand off to the flagship (Made Safe, Part 0)

**Scope rules (by design):**

- no threat models, hardening standards, recipes, or operational patterns
- no panic procedures (use the flagship Panic Card)

### Vol. 2 — *OpenClaw Made Safe* (Flagship)

Starts when your gateway already exists:

- `openclaw` is on your PATH
- the gateway is running and reachable privately

Then it takes you from "running" to "operating safely."

---

## Download the Companion Pack (free)

The Companion Pack is a small set of reusable pages:

- Safety Snapshot
- Health Ladder
- Remote Access cheat sheet (SSH + Tailscale Serve)
- Tiny troubleshooting fork
- Gateway Alive Card (print-friendly)
- Pointer to the flagship Panic Card

**Downloads (latest release):**
<{{ site.github.repository_url }}/releases/latest>

**Errata / updates:**
[Known issues and corrections](errata/)

---

## What to do next (recommended path)

1) **Start with Vol. 1** and get your gateway alive.
2) **Print the Panic Card** from *OpenClaw Made Safe* before your first real session.
3) Continue in **Vol. 2, Part 0: Quick Start Without Regret**.

---

## Buy on Amazon

- **Vol. 1:** Search Amazon for: "Your First OpenClaw Edward Izgorodin"
- **Vol. 2:** Search Amazon for: "OpenClaw Made Safe Edward Izgorodin"

---

## Versioning and freshness

OpenClaw moves fast. This project uses a simple rule:

- Companion Pack releases are tagged to an OpenClaw release (example: `v1.0-for-openclaw-2026.2`)
- the book is a stable snapshot
- updates go to the Companion Pack first

---

## Disclaimer

This project is **not affiliated with OpenClaw, its contributors, any OpenClaw Foundation, or OpenAI**.
OpenClaw is a trademark of its respective owners.
