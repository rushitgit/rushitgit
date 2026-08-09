<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="dark_mode.svg" />
    <source media="(prefers-color-scheme: light)" srcset="light_mode.svg" />
    <img alt="Rushit Palesha neofetch profile" src="dark_mode.svg" />
  </picture>
</p>

# Rushit Palesha

```text
> NAME        security-tilted builder · chess on the clock · flag chaser
> LOC         Dubai
> ROLE        Senior AI Engineer · Security @ Deriv
> DEGREE      CS — BITS Pilani, Dubai Campus (’21–’25)
> SIDE QUESTS CVEs · HackerOne · agent / MCP hardening · CTFs
```

If you’re human: I like **systems that misbehave in interesting ways**, **agent boundaries**, and **competitions where the clock is honest**.

Longer form (selected work, research writeups, receipts): **[rushit-portfolio-theta.vercel.app](https://rushit-portfolio-theta.vercel.app/)**

---

## Where to click

| Go | You’ll find |
| :--- | :--- |
| [Published CVEs](#published-cves) | Electron · OpenImageIO — coordinated disclosure |
| [Scoreboard exports](#scoreboard-exports) | CTF numbers, vendor finals, no slideshow |
| [What I actually do](#what-i-actually-do) | Work, OSS, bounty — one breath each |
| [Upstream merges](#upstream-merges) | VulnHunter · DefenseClaw |
| [Stack + shields](#stack-and-badges) | Boring but honest |
| [Say hi](#say-hi) | Mail · LinkedIn · portfolio |

---

## Published CVEs

| ID | Target | Signal |
| :--- | :--- | :--- |
| [**CVE-2026-70606**](https://www.cve.org/CVERecord?id=CVE-2026-70606) | [Electron](https://github.com/electron/electron/security/advisories/GHSA-r4w5-6pfg-jxp5) | Session-isolation / cache reuse via `ProtocolResponse.url` · Medium · CVSS 5.9 · CWE-668 |
| [**CVE-2026-59956**](https://github.com/AcademySoftwareFoundation/OpenImageIO/security/advisories/GHSA-hjfv-gvxc-qgvh) | OpenImageIO | Heap-buffer-overread in IFF decoder when Z-buffer is set · CWE-125 |

---

## Scoreboard exports

<details open>
<summary><code>[+] cat ./ctf/ledger.tsv</code> — merged results</summary>

| When | What | Signal |
| :--- | :--- | :--- |
| 2026 | [HTB](https://www.hackthebox.com/) Project Nightfall · Global Cyber Skills Benchmark | **Global 23rd** · **UAE 3rd** · 122 / 126 chals · 75,200 pts |
| 2026 | HTB Cyber Apocalypse | **294 / 6,744** teams · 83 / 136 chals · 3-person team |
| 2026-02 | [Snyk](https://snyk.io/ctf/) Fetch the Flag | **56 / 1539** · **2100** pts · **6 / 22** chals |
| 2025-10 | GITEX — UAE CSC CTF ([CTF.ae](https://gitex.ctf.ae/) world) | **3rd** · finals · tracks: web, pwn, DFIR, RE, coding, AI/ML-adjacent |
| 2025-08 | Kaspersky CTF · 24h (UAE CSC adjacency) | **12 / 415** (MEA, TR, Africa) · **2nd UAE** · **660** pts · web · RE · crypto · forensics · pwn · AI |
| — | Dubai Police CTF · academic track | **1st UAE** |
| — | Internal **AI / agent** build-off | **2nd** · **$5k** · NL → agents + tools · OpenAI Agents SDK |

</details>

<details open>
<summary><code>[+] ls ./ctf/archive/</code> — older loot</summary>

- NASA Space Apps **2023** — UAE winner · global nominee  
- IEEE Xtreme **17.0** — UAE section lead  
- GDG on Campus BITS Dubai — tech lead  
- Chess — **FIDE** rated · NYU inter-college **3rd** · [Lichess @rush21](https://lichess.org/@/rush21)  
- Paper — [*ChatGPT and the Social Media Echo: A Sentiment Analysis*](https://ieeexplore.ieee.org/document/10458761) (MoSICom 2023)  
- Past gigs — JetSynthesys · Cybage · Force Motors  

</details>

---

## What I actually do

| Bucket | Contents |
| :--- | :--- |
| **9–5-shaped** | Senior AI Engineer in Security @ Deriv — agent-security controls, supply-chain defenses, SOC / AI-assisted testing, DLP, anomaly detection. |
| **Vuln research** | Coordinated disclosure into upstream (Electron, OpenImageIO). Niche over noise. |
| **Public goods** | **LobsterLock** — host-level policy layer for autonomous agents (OpenClaw runtime boundary: cmd / net / fs). **[DefenseClaw](https://github.com/cisco-ai-defense/defenseclaw)** — scan and govern agent surfaces: skills, MCP, tool calls. |
| **Solo queue** | **[HackerOne](https://www.hackerone.com/)** — real bounties, real scopes, real consequences. |

---

## Upstream merges

| Repo | What landed |
| :--- | :--- |
| [Capital One / VulnHunter#21](https://github.com/capitalone/VulnHunter/pull/21) | Fixed repository-basename collisions in batch scans — preserve owner/repo identity across checkout, logs, results, resume state. |
| [Cisco AI Defense / DefenseClaw](https://github.com/cisco-ai-defense/defenseclaw) | Structured network-egress telemetry: query filters, blocked-call counts, OTel counters, optional Splunk forwarding ([#58](https://github.com/cisco-ai-defense/defenseclaw/pull/58), [#86](https://github.com/cisco-ai-defense/defenseclaw/pull/86)). |

---

## Stack and badges

**Languages:** Python · Java · C / C++ · Go · TypeScript · SQL  
**AI / agents:** RAG · evaluation · OpenAI / Anthropic · LangChain · agent guardrails  
**Security:** SOC · DLP · LLM/agent abuse cases · vuln research · automation without theater  
**Backend & data:** FastAPI · Flask · Spring · Postgres · MySQL · SQL Server · Neo4j · vector stores · Kafka · RabbitMQ · Pub/Sub  
**Platform:** Docker · Linux · Git  

<p align="left">
  <a href="https://rushit-portfolio-theta.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-rushit--portfolio-111?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/rushit-palesha/"><img src="https://img.shields.io/badge/LinkedIn-Rushit_Palesha-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:palesharushit@gmail.com"><img src="https://img.shields.io/badge/Email-palesharushit%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/electron/electron/security/advisories/GHSA-r4w5-6pfg-jxp5"><img src="https://img.shields.io/badge/CVE--2026--70606-Electron-red?style=for-the-badge&logo=electron&logoColor=white" alt="CVE-2026-70606"></a>
  <a href="https://github.com/cisco-ai-defense/defenseclaw"><img src="https://img.shields.io/badge/Open%20Source-DefenseClaw-111?style=for-the-badge&logo=github&logoColor=white" alt="DefenseClaw"></a>
  <a href="https://www.hackerone.com/"><img src="https://img.shields.io/badge/HackerOne-bug%20bounty-111111?style=for-the-badge&logo=hackerone&logoColor=white" alt="HackerOne"></a>
</p>

<details>
<summary><code>[+] make shields-expand</code> — full gadget rack</summary>

[![Java](https://img.shields.io/badge/-Java-007396?style=for-the-badge&logo=java&logoColor=white)](https://www.oracle.com/java/)
[![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org)
[![Go](https://img.shields.io/badge/-Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)](https://go.dev/)
[![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![C++](https://img.shields.io/badge/-C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)](https://isocpp.org/)
[![C Language](https://img.shields.io/badge/-C%20Language-A8B9CC?style=for-the-badge&logo=c&logoColor=white)](https://en.wikipedia.org/wiki/C_(programming_language))
[![Spring](https://img.shields.io/badge/-Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)](https://spring.io/)
[![Spring Batch](https://img.shields.io/badge/-Spring%20Batch-00A98F?style=for-the-badge&logo=spring&logoColor=white)](https://spring.io/projects/spring-batch)
[![Flask](https://img.shields.io/badge/-Flask-000000?style=for-the-badge&logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![Maven](https://img.shields.io/badge/-Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white)](https://maven.apache.org/)
[![Gradle](https://img.shields.io/badge/-Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)](https://gradle.org/)
[![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Firebase](https://img.shields.io/badge/-Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=white)](https://firebase.google.com/)
[![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![Microsoft SQL Server](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)](https://www.microsoft.com/sql-server)
[![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)](https://openai.com/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://www.linux.org/)
[![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)](https://www.rabbitmq.com/)
[![Google Pub/Sub](https://img.shields.io/badge/Google%20Pub%2FSub-4285F4?style=for-the-badge&logo=googlepubsub&logoColor=white)](https://cloud.google.com/pubsub)
[![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)](https://kafka.apache.org/)

</details>

---

## Say hi

**palesharushit@gmail.com** · **f20210010@dubai.bits-pilani.ac.in** · [LinkedIn](https://www.linkedin.com/in/rushit-palesha/) · [Portfolio](https://rushit-portfolio-theta.vercel.app/)

Good DMs: odd agentic trust bugs, **CVE** / disclosure edge cases, **CTF** war stories, **bounty** weirdness, **chess** panic moments.

---

<sub>This README’s threat model: markdown injection (you), recruiter copy-paste (them), and my future self forgetting to update the TSV.</sub>
