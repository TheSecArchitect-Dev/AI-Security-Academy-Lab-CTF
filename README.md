# 🚨 AI Security Academy Lab CTF

Hands-on AI Security CTF writeups focused on breaking LLM-based systems, multi-agent architectures, and modern AI workflows.

---

## 🧠 About This Repository

This repository documents my practical journey through labs from:

👉 https://ctf.aisecurityacademy.ai/labs

It focuses on **real-world AI security vulnerabilities**, explored through hands-on CTF challenges.

---

## 🎯 Goals

- Build strong fundamentals in **AI Security & LLM exploitation**
- Understand how **modern AI systems break**
- Practice **AI Red Teaming techniques**
- Map vulnerabilities to **industry standards (OWASP Top 10 for LLMs)**

---

## 🧩 AI Security – What & Why?

AI Security focuses on protecting systems powered by Large Language Models (LLMs) and AI agents.

### Key Risk Areas:
- Prompt Injection
- Data Leakage
- Unauthorized Tool Execution
- Multi-Agent Trust Exploitation
- Output Manipulation

Unlike traditional systems, AI applications are controlled by **natural language**, making them more dynamic — and more vulnerable.

---

## ⚔️ Core Attack Techniques Covered

Across these labs, the following attack patterns are explored:

- 🔹 Prompt Injection (Direct & Indirect)
- 🔹 Multi-Agent Exploitation
- 🔹 Confused Deputy Attacks
- 🔹 Tool / Function Abuse (MCP, APIs)
- 🔹 Output Manipulation & Data Exfiltration
- 🔹 Role Confusion & Trust Bypass

---

## 🧠 OWASP Top 10 for LLM Applications

This repo aligns with:

👉 OWASP Top 10 for LLMs

| Risk | Description |
|------|------------|
| LLM01 | Prompt Injection |
| LLM02 | Insecure Output Handling |
| LLM05 | Improper Agent Design |
| LLM07 | System Prompt Leakage |

---

## 🧪 Labs Index

| Lab Name | Focus Area | Status |
|---------|-----------|--------|
| Digital Doppelgänger | Multi-Agent Exploitation | ✅ Completed |
| Ghost Protocol | MCP Tool Abuse | ⏳ Pending |
| Behind the Curtain | Output Manipulation | ⏳ Pending |
| Shadow Commands | Prompt Injection | ⏳ Pending |
| Toxic Toolkit | Tool Chain Exploitation | ⏳ Pending |
| Broken Signals | Output Encoding Attacks | ⏳ Pending |

---

## 🧠 Standard Attack Methodology

```text
1. Recon (Identify agents / tools)
2. Map trust relationships
3. Identify privilege gaps
4. Test direct access
5. Attempt indirect exploitation
6. Abuse trusted components
7. Extract via output channels
