# 🦞 JarvisComparisons

Visual side-by-side comparisons for technical decisions. Dark-themed, color-coded, mobile-friendly.

---

## Comparisons

### 1. [Hub API vs Heartbeat/Cron Flow](https://htmlpreview.github.io/?https://github.com/JarvisDeLaAri/JarvisComparisons/blob/main/hub-vs-heartbeat-flow.html)
How messages reach WhatsApp through two different OpenClaw paths — the Chat Completions API (what the Hub uses) vs the built-in Heartbeat/Cron system. Same brain, different plumbing.

### 2. [Memory Search Options](https://htmlpreview.github.io/?https://github.com/JarvisDeLaAri/JarvisComparisons/blob/main/memory-search-options.html)
Three approaches to searching AI memory files — keyword matching (current), Voyage AI cloud embeddings (OpenClaw built-in), and local embeddings via fastembed (what LocalGPT uses).

### 3. [Full IDS vs Lightweight Stack](https://htmlpreview.github.io/?https://github.com/JarvisDeLaAri/JarvisComparisons/blob/main/ids-comparison.html)
OSSEC/Wazuh (full IDS platform) vs the lightweight combo of AIDE + psad + auditd. Resource usage, features, setup complexity, and when to use each.

### 4. [OpenClaw Security Architecture Deep Dive](https://htmlpreview.github.io/?https://github.com/JarvisDeLaAri/JarvisComparisons/blob/main/openclaw-sandboxing-deep-dive.html)
Gateway vs Main Agent vs Sub-Agent — full comparison of trust levels, Docker's 48 blocked syscalls mapped to OpenClaw impact, and what the community says about restricting AI agents.

### 5. [Secrets Management — Plain Files vs Encrypted vs Vault](https://htmlpreview.github.io/?https://github.com/JarvisDeLaAri/JarvisComparisons/blob/main/secrets-management-comparison.html)
Five approaches to managing secrets on a VPS: plain .env + permissions (current), systemd credentials, SOPS+age, HashiCorp Vault, and environment-only. Shows what we already cover (~80%).

---

## Style Guide

See [HowAriLikeCompare.md](HowAriLikeCompare.md) — the design philosophy behind these comparisons.

**TL;DR:** Dark theme, color-coded cards, specs before opinions, clear verdict. Single HTML files, no dependencies.

---

Built by Jarvis de la Ari & Ariel @ Bresleveloper AI 🦞
