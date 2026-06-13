# Romain Deperne

**Offensive Security Researcher  ·  LLM & Agentic-AI Security**
OSCP  ·  OSWA

---

### What I do

I research the security of agentic AI systems and LLM-based applications. I built a private
LLM-agent platform (tool-use architecture) that has uncovered **455+ vulnerabilities** across the
AI / LLM ecosystem — covering the official **MCP SDKs** (Python, TypeScript, Rust), LangChain,
LlamaIndex, mem0, RAGFlow, smolagents, LiteLLM and MetaGPT — with **20+ CVE IDs assigned** and
multiple high-CVSS RCE chains. Every finding ships with a standalone, reproduced PoC and a
coordinated-disclosure timeline.

### Featured CVEs — published & reproduced

Each link is a public repo with the full write-up, root-cause analysis and a working PoC.

| CVE | Target | Class | CVSS | Ecosystem |
|-----|--------|-------|:----:|-----------|
| [CVE-2026-27825](https://github.com/romain-deperne/CVE-2026-27825) | `mcp-atlassian` | Path Traversal (arbitrary file read) | **9.3** | 🤖 MCP server |
| [CVE-2026-33980](https://github.com/romain-deperne/CVE-2026-33980) | `adx-mcp-server` | KQL Injection | **8.8** | 🤖 MCP server |
| [CVE-2026-34940](https://github.com/romain-deperne/CVE-2026-34940) | `KubeAI` | OS Command Injection | **8.7** | 🤖 AI serving infra |
| [CVE-2026-34975](https://github.com/romain-deperne/CVE-2026-34975) | `Plunk` | CRLF Email Header Injection | **8.5** | Web |
| [CVE-2026-32247](https://github.com/romain-deperne/CVE-2026-32247) | `graphiti-core` | Cypher Injection | **8.1** | 🤖 AI memory / RAG |
| [CVE-2026-34160](https://github.com/romain-deperne/CVE-2026-34160) | `Chamilo LMS` | Unauthenticated SSRF | 7.5 | Web |
| [CVE-2026-33715](https://github.com/romain-deperne/CVE-2026-33715) | `Chamilo LMS` | Unauth SSRF + Open Email Relay | 7.5 | Web |

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

*Always down to talk offensive sec, AI red-teaming, bug bounty and coordinated vulnerability disclosure.*
