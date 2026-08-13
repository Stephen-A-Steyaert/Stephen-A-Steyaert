# 👋 Hey, I'm Stephen Steyaert

I'm a CS student at Old Dominion and developer who learns by doing - currently working on my own interpreted scripting language in C++.

---

## 🧠 About Me

- :mortar_board: Senior studying Computer Science  
- 🧱 Partially self-taught - I dive deep into backend systems and APIs outside class  
- 🛡️ Part of the team building [CyberCup.AI](https://cybercup.ai), a cybersecurity & AI competition platform
- 🕸️ Focused on backend development: APIs, databases, containerized deployments  
- :snake: Python was my intro to programming; I taught myself C++  

---

## :test_tube: What I'm Working On

### :shield: [CyberCup.AI](https://cybercup.ai)

Cyber AI Competition Unified Platform (CUP) — a unified hub for cybersecurity & AI competitions, built at the School of Cybersecurity, Old Dominion University.

**Inaugural competitions hosted:**
- :robot: **LLM CTF** — An AI red-teaming competition where participants extracted hidden flags from a protected LLM using only natural language prompts. No coding or hacking tools required — success depended on creativity, logical reasoning, and understanding how LLMs respond under constraints.
- :gear: **AI-Assisted CTF** — Combined traditional CTF challenges with LLMs, where participants used a dedicated LLM agent to analyze challenges, reason through solutions, and capture flags.
- :closed_lock_with_key: **Backdoor LLM Challenge** — Explored supply-chain-style attacks where hidden behavior is implanted into a model during training, causing it to behave normally except when a specific trigger is present.
- :performing_arts: **Autonomous AI CTF (AAA-CTF)** — Applied AI agent reasoning, planning, and tool use to real cybersecurity problems: vulnerability discovery, reverse engineering, exploit development, and forensic investigation.

### :robot: Agentic AI Security CTF *(in progress)*

Exploit autonomous AI agents using prompt injection, memory poisoning, and goal manipulation to capture flags across multiple difficulty tiers.

**"Agent Breaker" challenge ladders — 9 scenarios, each easy through expert:**
- :airplane: **Atlas Air** — Extract an airline rebooking agent's confidential internal policy (fare-waiver matrix, reason codes, override codes) through prompt extraction, against defenses that get harder to social-engineer around at each tier.
- :speech_balloon: **CalmMind** — Jailbreak a mental-health support bot's output-safety filters into producing profanity, defeating increasingly strict content and instruction-protection layers.
- :calendar: **City Event Guide** — Indirectly inject a malicious URL into an AI-generated Barcelona itinerary by hiding instructions inside the event data it reads, bypassing layered filtering rules.
- :email: **ClearComm** — Trick a corporate email assistant into spoofing its `send_email` sender field to impersonate the CEO.
- :house: **HomeHive** — Get a smart-home concierge to disclose the names of private functions it's wired to but never supposed to reveal.
- :electric_plug: **MCP Mischief** — Compromise an MCP (Model Context Protocol) server's tool descriptions to make a database assistant exfiltrate sensitive data through a tool parameter.
- :brain: **Preference Poisoning** — Inject a poisoned memory entry into a personal assistant's persistent memory so it hijacks future unrelated responses.
- :headphones: **ResolveAI** — Poison a customer-support knowledge base so the AI leaks another customer's private data during an unrelated support interaction.
- :money_with_wings: **RugLESS Protocol Intelligence** — Manipulate an AI-powered DeFi due-diligence platform's risk assessments via poisoned protocol documentation.

**FinBot — business AI agent challenges, also part of this track:**
- :speech_balloon: **Chat Jailbreak (Threshold Extraction)** — Social-engineer a vendor-support chatbot into revealing confidential approval thresholds it's told never to share directly.
- :balance_scale: **Contract Review Injection/Evasion/Manipulation** — Hijack a legal-review AI (CyberLaw) into approving contracts with dangerous clauses — from direct prompt injection, to semantically-disguised unlimited-liability language, to exploiting a fully autonomous tool-calling version.
- :satellite: **Data Exfiltration & MCP Tool Poisoning** — Trick FinAGENT into leaking sensitive company data through its HTTP/webhook tool or a poisoned MCP tool description.
- :bug: **DevBot PR/CI Challenges** — Get a code-review agent (DevBot) to approve a vulnerable PR, dismiss a CRITICAL scanner finding, leak a CI deploy token through a webhook, get it to recommend a malicious dependency via a poisoned rules file, or compose several individually-safe suggested fixes into a malicious combined patch.
- :envelope: **Email Exfiltration** — Redirect an invoice agent's notification email to an attacker-controlled address despite an "unoverridable" send-only-to-vendor rule.
- :calendar: **Interview Slot Poisoning** — Override a scheduling agent's strict no-double-booking rule.
- :receipt: **Invoice Approval** — Manipulate an AI invoice processor (FinAGENT) into approving invoices above its auto-approve threshold, against increasing fraud-detection and scrutiny.
- :page_facing_up: **Resume Injection** — Get an unqualified candidate approved by CyberHire's AI resume screener, including bypassing a dual-agent security/evaluator architecture.

### :mortar_board: [CyberCup.AI — Training](https://cybercup.ai/learn)

A growing library of hands-on AI security training paths.

**Paths include:**
- :brain: **AI and LLM Fundamentals** — Learn how large language models work, how they are trained, and how safety guardrails are built.
- :shield: **AI Security Fundamentals** — Master the core concepts of AI and cybersecurity, from cryptography to prompt injection, through hands-on challenges.
- :closed_lock_with_key: **AI Security Fundamentals v2 (PRO)** — Advanced AI security: threat modelling, red teaming, privacy, supply chain security, and compliance.
- :dart: **Prompt Injection (PRO)** — How prompt injection works, from direct and indirect attacks to real-world defenses.
- :mag: **Prompt Leaking (PRO)** — How attackers extract hidden system prompts and how to protect against it.
- :unlock: **Jailbreaking (PRO)** — How jailbreaking bypasses AI safety training, from single-turn to multi-turn attacks.

> Each path is broken into modules and hands-on rooms, built to teach AI security by doing.

### :link: [LTI Integration](https://instructor.cybercup.ai/lti-setup)

Building LTI 1.3 (Learning Tools Interoperability) support so CyberCup.AI training plugs directly into Learning Management Systems.

- :books: Native support for **Moodle** and **Canvas LMS**, plus any LMS supporting LTI 1.3 Advantage
- :arrows_counterclockwise: OIDC login, tool launch, deep linking, and JWKS endpoints for secure LMS integration
- :bar_chart: Automatic grade passback and roster synchronization, so instructors can assign CyberCup.AI training directly through their LMS

> Building the platform where cybersecurity and AI security research meet.

---

## 🛠 Tech Stack

**Languages:**  
 <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a>  <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/> </a>

**Backend & Frameworks:**  
<a href="https://www.djangoproject.com/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/django.svg" alt="django" width="40" height="40"/> </a> <a href="https://fastapi.tiangolo.com/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/fastapi.svg" alt="django" width="40" height="40"/> </a>

**Tools & Infrastructure:**  
<a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/docker.svg" alt="docker" width="40" height="40"/> </a> <a href="https://github.com/features/actions" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/githubactions/githubactions-original.svg" alt="github actions" width="40" height="40"/></a>, <a href="https://doc.traefik.io/traefik/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/1/1e/Traefik_Logo.svg" alt="traefik" width="40" height="40"/></a> <a href="https://nginx.org/" target="_blank" rel="noreferrer"><img src="https://cdn.worldvectorlogo.com/logos/nginx-1.svg" alt="nginx" width="40" height="40"/></a> <a href="https://github.com/astral-sh/uv" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/astral-sh/uv/main/docs/assets/logo-letter.svg" alt="uv" width="40" height="40"/></a>

**Testing:**  
Pytest, Factory Boy, Catch2

<!-- ---

## :file_folder: Featured Projects -->

<!-- ### :construction: [Personal Site and Blog](https://github.com/Stephen-A-Steyaert/personal-site) 
A clean Django-based resume website and blog, containerized and deployed using Docker Swarm + Traefik. -->  
<!-- 📎 Live at: [resume.helloworld.xyz](https://resume.helloworld.xyz) -->

---

## :bar_chart: My Stats

<p><img src="https://github-readme-streak-stats.herokuapp.com/?user=stephen-a-steyaert" alt="stephen-a-steyaert" /></p>

---

## :globe_with_meridians: Connect With Me

<!-- - 🧠 [Website](https://resume.helloworld.xyz) -->
<!-- - 💼 [LinkedIn](https://linkedin.com/in/stevesteyaert) -->
- :mailbox: Email: stephen@steyaert.xyz
