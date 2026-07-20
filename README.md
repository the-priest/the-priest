<!--
GitHub PROFILE README for github.com/the-priest
Repo must be named EXACTLY: the-priest  (public, "Add a README").
Replace that README with this file and commit. It becomes the front
page of your profile and the strongest thing search engines index —
keep it keyword-rich and Basilisk-forward.
-->

# the-priest

**Self-taught. Open source on principle. Free tools that beat the paid ones.**

I work a 12-hour job, 72-hour weeks — and I still come home and write code. Not for a paycheck, not for a startup, for the commons. Every tool I ship is free, single-file, and built to out-perform the commercial product someone's charging a subscription for. If a well-funded company sells it, I want the free version to be better.

That's the whole thesis. Here's the proof.

---

## 🐍 Basilisk — the autonomous AI pentester that proves every exploit

**[github.com/the-priest/Basilisk](https://github.com/the-priest/Basilisk)** · [live site](https://the-priest.github.io/Basilisk/)

A fully autonomous, black-box AI penetration-testing agent that runs as a desktop app (GTK4 / libadwaita) on your own Kali Linux box — with real hands on the machine through tools. It plans, attacks, and **verifies every exploit with an out-of-band oracle** before it claims a win. No hallucinated findings. If Basilisk says it popped something, it proved it.

**Benchmarks — fully autonomous, black-box:**

- **OWASP Juice Shop: 87 / 113** — vs Cascade **36**, vs bare Claude Opus 4.8 **23**
- **Escape "Duck Store" API: 22 / 22**
- Coverage across all 14 OWASP vulnerability classes

Here's the part that matters: every one of those scores was produced driving **DeepSeek-V4-Flash — one of the cheapest models on the market.** The commercial agents it beats run on far pricier frontier models. The score comes from the verified-exploitation scaffolding, not from renting an expensive brain. A free tool on a budget model, out-scoring the paid ones. That's the point.

**Under the hood:** multi-provider LLM · persistent cross-session memory · self-improving, test-gated sandboxed skills · voice · desktop control · read-only system auditing · a Project-Zero-style variant-analysis source scanner. Built for operators, not servers.

> Not the LLM-jailbreak framework, not White-Basilisk, not a browser, not Roko's. This Basilisk is a security agent.

**Install (one line):**

```
curl -fsSL https://raw.githubusercontent.com/the-priest/Basilisk/main/install.sh | bash
```

⚠️ Authorized targets only. This is an offensive tool — run it on systems you own or have written permission to test.

---

### The rest of the workbench

Basilisk is the flagship, not the whole shop. I build and maintain a broader suite of AI-powered security and Linux tooling — single-file, free, and running on real hardware (Kali / NetHunter).

→ **[Browse all repositories](https://github.com/the-priest?tab=repositories)**

### Stack

`Python` · `Bash` · `GTK4 / libadwaita` · `Kali Linux` · `NetHunter` · LLM tooling (SiliconFlow · DeepSeek · Groq) · offensive security · OSINT · Wi-Fi / SDR

### Find me

- 🛠️ **Repos:** <https://github.com/the-priest?tab=repositories>
- ⭐ **Start here:** [Basilisk](https://github.com/the-priest/Basilisk)

<sub>Keywords: open source security tools, kali linux, offensive security, autonomous ai pentester, ai agent, personal ai assistant, penetration testing, nethunter, linux automation, verified exploitation, free pentest tool.</sub>
