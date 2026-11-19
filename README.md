<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=venom&color=0:0d0221,45:4c1d95,100:a78bfa&height=250&section=header&text=shubham%20gupta&fontSize=70&fontColor=ffffff&fontAlignY=40&desc=builds%20things%20%E2%80%A2%20breaks%20things%20%E2%80%A2%20writes%20the%20report%20after&descAlignY=62&descSize=17&animation=fadeIn" />

<a href="https://shubh4m03.github.io/SG-Portfolio">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2800&pause=900&color=C4B5FD&center=true&vCenter=true&width=760&lines=full+stack+%2B+agentic+ai+engineer;offensive+security+%E2%80%A2+pentester+%E2%80%A2+ctf+grinder;founder+%40+RAVEN'34+%F0%9F%A6%85;eJPT+%E2%86%92+PNPT+%E2%86%92+OSCP+(in+progress%2C+not+in+denial)" alt="typing" />
</a>

<br/>

<img src="https://img.shields.io/badge/lpu-b.tech%20cse%20'25--'29-4C1D95?style=flat-square&labelColor=0d0221" />
<img src="https://img.shields.io/badge/based%20in-punjab%2C%20india-7C3AED?style=flat-square&labelColor=0d0221" />
<img src="https://img.shields.io/badge/os-kali%20(btw)-8B5CF6?style=flat-square&logo=kalilinux&logoColor=white&labelColor=0d0221" />
<img src="https://img.shields.io/badge/status-open%20to%20work-A78BFA?style=flat-square&labelColor=0d0221" />

<br/><br/>

<a href="https://shubh4m03.github.io/SG-Portfolio"><img src="https://img.shields.io/badge/PORTFOLIO-4C1D95?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/shubham-gupta3/"><img src="https://img.shields.io/badge/LINKEDIN-5B21B6?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:shubham.2056@lpu.in"><img src="https://img.shields.io/badge/EMAIL-6D28D9?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://hackerone.com/m4v3rick03"><img src="https://img.shields.io/badge/HACKERONE-7C3AED?style=for-the-badge&logo=hackerone&logoColor=white" /></a>
<a href="https://tryhackme.com/p/shubh4m03"><img src="https://img.shields.io/badge/TRYHACKME-8B5CF6?style=for-the-badge&logo=tryhackme&logoColor=white" /></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=shubh4m03&label=visitors&color=7c3aed&style=flat-square" />
<img src="https://img.shields.io/github/followers/shubh4m03?label=followers&style=flat-square&color=7c3aed&labelColor=0d0221" />

</div>

<br/>

## `~/whoami`

```bash
shubham@raven34:~$ neofetch

  ┌──────────────────────────────────────────────┐
  │  role      swe  ×  ai eng  ×  offensive sec  │
  │  uni       lovely professional university    │
  │  degree    b.tech cse  ·  2025 → 2029        │
  │  org       founder @ RAVEN'34                │
  │  also      campus ambassador @ ICSS          │
  │  shipping  live software for a real shop     │
  │  grinding  eJPT → PNPT → OSCP                │
  │  shell     zsh on kali                       │
  └──────────────────────────────────────────────┘
```

i build software that has to survive real users, real traffic, and real attackers. product engineering + applied ai + offensive security, in one head, occasionally sleeping.

- 🛠️ **ship** full stack products with typed schemas, row-level auth, and CI that actually blocks bad merges
- 🧠 **build** agentic ai systems where the llm is treated like an unreliable dependency, not a magic wand
- 🔓 **break** things (legally) through bug bounty, ctfs, and my own recon tooling
- 🦅 **run** [RAVEN'34](https://github.com/shubh4m03), a student pentest division doing real engagements

<br/>

## `./stack`

<div align="center">

<img src="https://skillicons.dev/icons?i=python,cpp,c,js,ts,java,bash&theme=dark" /><br/>
<img src="https://skillicons.dev/icons?i=react,nextjs,astro,tailwind,vite,redux,figma&theme=dark" /><br/>
<img src="https://skillicons.dev/icons?i=fastapi,nodejs,supabase,postgres,mysql,mongodb&theme=dark" /><br/>
<img src="https://skillicons.dev/icons?i=aws,docker,git,githubactions,linux,kali,nginx,vercel,postman&theme=dark" />

</div>

<br/>

## `./main-quests`

<table>
<tr>
<td width="50%" valign="top">

### 🧞 PrepGenie
**agentic ai career coach**

parses your resume + target role, builds a competency map, runs multi-turn mock interviews, returns evidence-backed feedback. not a prompt wrapper.

`FastAPI` `Next.js 14` `TypeScript` `Supabase` `Gemini`

- schema-validated model output, retry on contract violation
- streamed responses, cached prompt/embedding layers
- RLS on every tenant table
- built for **HACK AI** hackathon

[**→ repo**](https://github.com/shubh4m03)

</td>
<td width="50%" valign="top">

### 📍 ShiftPin
**attendance pwa, live in production**

built for a real business: low-end androids, bad networks, people who will absolutely try proxy punch-ins.

`React` `TypeScript` `Supabase` `Service Workers` `PWA`

- device-binding to kill shared-credential fraud
- offline queue that reconciles on reconnect
- admin-only provisioning + audit trail
- replaced a paper register. yes, paper.

[**→ repo**](https://github.com/shubh4m03)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛰️ RAVEN-Recon
**terminal-native recon aggregator**

no browser, no gui, just a TUI that orchestrates your whole recon chain and normalizes it into one queryable dataset.

`Python` `Textual` `asyncio` `subfinder` `httpx` `naabu` `nuclei` `SQLite`

- bounded async workers, live streaming results
- scope guardrails reject out-of-scope targets *before* a packet leaves
- local-only storage, zero telemetry

[**→ repo**](https://github.com/shubh4m03)

</td>
<td width="50%" valign="top">

### ⚡ SG-Portfolio
**zero-js static portfolio**

every dependency had to justify its bytes.

`Astro` `TypeScript` `Tailwind` `GitHub Actions`

- island hydration, zero client js by default
- typed content collections: bad data fails the build
- fully automated deploy pipeline

[**→ repo**](https://github.com/shubh4m03/SG-Portfolio) · [**→ live**](https://shubh4m03.github.io/SG-Portfolio)

</td>
</tr>
</table>

<details>
<summary><b>🍔 side quest: Kitchenette</b> (campus food ordering spa)</summary>

<br/>

three-role (customer / vendor / admin) ordering app with an explicit order state machine, versioned persistence so schema changes don't brick returning users, and no backend at all. constraint-driven design, basically.

`JavaScript` `HTML5` `CSS3` `LocalStorage`

</details>

<br/>

## `./receipts`

| 🏆 | what happened |
| :-: | :-- |
| 🔓 | **responsible disclosure**: secure exam environment os-allowlist bypass, full repro + remediation |
| 🔓 | **responsible disclosure**: firebase access-control issue on a messaging platform, full repro + remediation |
| 📱 | **paypal android sdk**: independent security review as part of bug bounty research |
| 🚩 | **RootBreach CTF (NITJ)**: top 5 nationally |
| 🚩 | **Trivarna 2.0 CTF**: stego, BLE traffic analysis, zero-width char challenges |
| 🕵️ | **OSINT scavenger hunt**: multi-stage osint + digital forensics |
| 🧨 | **pwn / rev**: heap use-after-free, android apk reversing, pcap forensics |
| 🤖 | **HACK AI**: shipped a full agentic platform inside the hackathon window |
| 🌍 | **GSSoC 2026**: selected contributor |
| 🦅 | **founded RAVEN'34**: student pentest division with real clients and in-house tooling |

<br/>

## `./experience`

```diff
+ Founder & Lead Security Engineer  @ RAVEN'34                      [2025 → now]
  web / mobile / infra assessments, apk-level review, scoping → RoE → testing → client reporting.
  built the methodology, reporting standard, and tooling from zero.

+ Software Engineer (Part-Time)     @ Raj Laxmi Enterprises         [2025 → now]
  digitalised a retail operation: attendance pwa, inventory workflows, supabase data model with RLS.
  requirements straight from non-technical stakeholders. live users. no "works on my machine".

+ Campus Ambassador                 @ Indian Cyber Security Solutions [2025 → now]
  awareness sessions, outreach campaigns, student → certification pipeline.
```

<br/>

## `./ai-lab`

```yaml
agentic_systems:     tool-using agents · planner/executor loops · typed output contracts · deterministic fallbacks
llm_engineering:     gemini + claude apis · prompt architecture · streaming · token/cost budgeting
rag:                 chunking · embeddings · pgvector search · grounding
applied_ml / nlp:    scikit-learn · pandas · classification · semantic similarity · resume/jd parsing
evals:               regression suites for non-deterministic outputs · latency vs quality tradeoffs
ai_security:         prompt injection · insecure output handling · authz review
```

<br/>

## `./currently`

```yaml
learning:
  - advanced dsa in c++
  - distributed systems + scalable backend design
  - offensive sec: eJPT → PNPT → OSCP
  - applied ml + model evaluation

building:
  - RAVEN-Recon
  - ShiftPin at production scale
  - agentic ai with verifiable output contracts

exploring:
  - rag over postgres / pgvector
  - prompt injection + insecure output handling
  - aws + infrastructure as code
  - binary exploitation + reverse engineering

open_to:
  - swe internships
  - ai / ml engineering
  - appsec / security engineering
  - open source collabs
  - freelance product builds
```

<details>
<summary><b>📜 certs</b></summary>

<br/>

<div align="center">

<img src="https://img.shields.io/badge/EC--Council-Android%20Bug%20Bounty-6D28D9?style=flat-square&labelColor=0d0221" />
<img src="https://img.shields.io/badge/ISC2-Certified%20in%20Cybersecurity-9333EA?style=flat-square&labelColor=0d0221" />
<img src="https://img.shields.io/badge/Cisco-Ethical%20Hacker-7C3AED?style=flat-square&labelColor=0d0221" />
<img src="https://img.shields.io/badge/Cisco-Intro%20to%20Cybersecurity-7C3AED?style=flat-square&labelColor=0d0221" />
<img src="https://img.shields.io/badge/Cisco-Networking%20Basics-7C3AED?style=flat-square&labelColor=0d0221" />
<img src="https://img.shields.io/badge/Infosys-Springboard%20Cybersecurity-8B5CF6?style=flat-square&labelColor=0d0221" />
<img src="https://img.shields.io/badge/NPTEL-C%2B%2B-6D28D9?style=flat-square&labelColor=0d0221" />
<img src="https://img.shields.io/badge/NPTEL-DSA-6D28D9?style=flat-square&labelColor=0d0221" />
<img src="https://img.shields.io/badge/NPTEL-DBMS-6D28D9?style=flat-square&labelColor=0d0221" />

<br/>

**loading...** &nbsp;
<img src="https://img.shields.io/badge/eJPT-INE-A78BFA?style=flat-square&labelColor=0d0221" />
<img src="https://img.shields.io/badge/PNPT-TCM-A78BFA?style=flat-square&labelColor=0d0221" />
<img src="https://img.shields.io/badge/OSCP-OffSec-A78BFA?style=flat-square&labelColor=0d0221" />

</div>

</details>

<br/>

## `./stats`

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=shubh4m03&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&title_color=A78BFA&icon_color=7C3AED&text_color=C4B5FD&bg_color=0D1117" />
<img height="180em" src="https://streak-stats.demolab.com?user=shubh4m03&hide_border=true&background=0D1117&stroke=7C3AED&ring=A78BFA&fire=8B5CF6&currStreakLabel=A78BFA&sideLabels=C4B5FD&dates=6D28D9&sideNums=C4B5FD&currStreakNum=A78BFA" />

<br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=shubh4m03&layout=compact&hide_border=true&title_color=A78BFA&text_color=C4B5FD&bg_color=0D1117" height="150em" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=shubh4m03&bg_color=0d1117&color=c4b5fd&line=7c3aed&point=ffffff&area=true&area_color=7c3aed&hide_border=true" width="100%" />

<br/>

<img width="100%" src="https://raw.githubusercontent.com/shubh4m03/shubh4m03/output/snake.svg" />

</div>

<br/>

## `./coding-profiles`

<div align="center">

<a href="https://leetcode.com/u/shubhamgupta03/"><img src="https://img.shields.io/badge/LeetCode-4C1D95?style=for-the-badge&logo=leetcode&logoColor=A78BFA" /></a>
<a href="https://www.geeksforgeeks.org/profile/shubhamhyw7"><img src="https://img.shields.io/badge/GeeksforGeeks-5B21B6?style=for-the-badge&logo=geeksforgeeks&logoColor=white" /></a>
<a href="https://www.hackerrank.com/profile/shubhamg0116"><img src="https://img.shields.io/badge/HackerRank-6D28D9?style=for-the-badge&logo=hackerrank&logoColor=white" /></a>
<a href="https://www.codechef.com/users/shubh4m03"><img src="https://img.shields.io/badge/CodeChef-7C3AED?style=for-the-badge&logo=codechef&logoColor=white" /></a>

</div>

<br/>

<div align="center">

```
"engineering is turning constraints into systems that hold."
```

<a href="mailto:shubham.2056@lpu.in"><img src="https://img.shields.io/badge/slide%20into%20my%20inbox-4C1D95?style=for-the-badge&logo=gmail&logoColor=white" /></a>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:a78bfa,50:4c1d95,100:0d0221&height=140&section=footer" />

</div>
