# Romain Deperne

**Offensive Security · AppSec & Source-Code Review · AI-driven offensive tooling**
OSCP  ·  OSWA

---

### What I do

Penetration testing and **application-security source-code review**, scaled with an
**AI-driven offensive harness** I built and operate. The harness is an LLM-agent system that reads
source, hypothesizes vulnerabilities, **writes and runs PoCs to confirm them**, kills false positives,
and files coordinated-disclosure reports — human-in-the-loop on every aggressive action. I steer it,
validate its output against professional standards, and benchmark where automation beats (or misses)
a human pentester.

It has driven **300+ projects audited**, **200+ reports filed**, and **40+ CVE IDs assigned** across
the AI/LLM ecosystem — the official **MCP SDKs** (Python, TypeScript, Rust), LangChain, LlamaIndex,
mem0, RAGFlow, KubeAI, Dagster, JupyterHub and more — with multiple high-CVSS RCE chains. Findings
span **Python, Go, TypeScript/JS, C# and C/C++**. Every report ships with a standalone, reproduced PoC.

### 🛠 Flagship — how I work at scale

**[`vulnhunter-harness`](https://github.com/romain-deperne/vulnhunter-harness)** — architecture &
methodology of the AI-driven offensive-security harness: agent orchestration, non-bypassable scope
hooks, the find → prove → disclose loop, and the human-vs-automation benchmarking that makes it
trustworthy on real engagements.

### Featured CVEs — published & reproduced

Each link is a public repo with the full write-up, root-cause analysis and a working PoC.

| CVE | Target | Class | CVSS | Ecosystem |
|-----|--------|-------|:----:|-----------|
| [CVE-2026-27825](https://github.com/romain-deperne/CVE-2026-27825) | `mcp-atlassian` | Path Traversal (arbitrary file read) | **9.3** | 🤖 MCP server |
| [CVE-2026-33980](https://github.com/romain-deperne/CVE-2026-33980) | `adx-mcp-server` | KQL Injection | **8.8** | 🤖 MCP server |
| [CVE-2026-48017](https://github.com/romain-deperne/CVE-2026-48017) | `DbGate` | Remote Code Execution | **8.8** | Database tooling |
| [CVE-2026-34940](https://github.com/romain-deperne/CVE-2026-34940) | `KubeAI` | OS Command Injection | **8.7** | 🤖 AI serving infra |
| [CVE-2026-34975](https://github.com/romain-deperne/CVE-2026-34975) | `Plunk` | CRLF Email Header Injection | **8.5** | Web |
| [CVE-2026-32247](https://github.com/romain-deperne/CVE-2026-32247) | `graphiti-core` | Cypher Injection | **8.1** | 🤖 AI memory / RAG |
| [CVE-2026-41490](https://github.com/romain-deperne/CVE-2026-41490) | `Dagster` | SQL Injection (dynamic partitions) | High | 🤖 Data / AI orchestration |
| [CVE-2026-34160](https://github.com/romain-deperne/CVE-2026-34160) | `Chamilo LMS` | Unauthenticated SSRF | 7.5 | Web |
| [CVE-2026-33715](https://github.com/romain-deperne/CVE-2026-33715) | `Chamilo LMS` | Unauth SSRF + Open Email Relay | 7.5 | Web |
| [CVE-2026-40864](https://github.com/romain-deperne/CVE-2026-40864) | `JupyterHub` | XSRF bypass (CWE-352) | Moderate | 🤖 ML notebooks |

→ [All GitHub Security Advisories I'm credited on](https://github.com/advisories?query=credit%3Aromain-deperne)

### Recognition

- 🇫🇷 **WorldSkills 2024 France — Cybersecurity Champion**
- 🌍 **WorldSkills International — World Top 10**
- Reserve cyber officer @ Gendarmerie Nationale

### Selected publications & talks

- *React2Shell: CVE-2025-55182, Zero-Click RCE* — **MISC Magazine #144**
- *Understanding CUPS Vulnerabilities (CVE-2024-47xxx)* — **MISC Magazine #138**
- Live Hacking Demo — **Barbhack Conference**, Palais des Congrès

### Contact

- 💼 [LinkedIn](https://fr.linkedin.com/in/romain-deperne%F0%9F%9B%A1%EF%B8%8F-580920221)
- ✉️  [romaindep@protonmail.com](mailto:romaindep@protonmail.com)

---

*Pentest delivery · AppSec & source-code review · AI-assisted vulnerability research · coordinated disclosure. Open to offensive-security roles.*
