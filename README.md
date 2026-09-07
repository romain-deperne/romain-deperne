# Romain Deperne

Pentester and vulnerability researcher. OSCP · OSWA.

I work on web and API pentesting, bug bounty, and vulnerability research. I also build automation and LLM workflows around that work. Every finding listed below has a reproduced proof of concept.

Here is some of my work:

- Found and reported vulnerabilities in DbGate, Dagster, JupyterHub, KubeAI, Graphiti, Chamilo, Plunk, mcp-atlassian, and adx-mcp-server.
- The public write-ups cover code execution, SQL/KQL/Cypher injection, command injection, SSRF, arbitrary file read, email header injection, and CSRF.
- Built [Bounty Target Radar](https://github.com/romain-deperne/bounty-target-radar), a Python CLI for collecting and ranking public `security.txt` and disclosure-policy signals.
- Published two articles in MISC magazine.
- Represented France in cybersecurity at [WorldSkills Lyon 2024](https://worldskills.org/what/competitions/worldskills-lyon-2024/events/competitors/5624), after winning a silver medal at the [2023 French national competition](https://www.worldskills-france.org/actualites/47e-competition-nationale-des-metiers-les-resultats).
- Cyber reserve officer with the French Gendarmerie.

## Selected vulnerabilities

| Finding | Project | Impact |
|---|---|---|
| [CVE-2026-48017](https://github.com/romain-deperne/CVE-2026-48017) | DbGate | Remote code execution |
| [CVE-2026-41490](https://github.com/romain-deperne/CVE-2026-41490) | Dagster | SQL injection |
| [CVE-2026-77262](https://github.com/romain-deperne/CVE-2026-77262) | mcp-atlassian | Arbitrary file read |
| [CVE-2026-34940](https://github.com/romain-deperne/CVE-2026-34940) | KubeAI | OS command injection |
| [CVE-2026-32247](https://github.com/romain-deperne/CVE-2026-32247) | Graphiti | Cypher injection |
| [CVE-2026-40864](https://github.com/romain-deperne/CVE-2026-40864) | JupyterHub | CSRF |

[More advisories crediting my work](https://github.com/advisories?query=credit%3Aromain-deperne)

## Publications

- [React2Shell: CVE-2025-55182, autopsy of a zero-click RCE and detection/mitigation strategies](https://connect.ed-diamond.com/misc/misc-144/react2shell-cve-2025-55182-autopsie-d-une-rce-zero-click-et-strategies-de-detection-et-de-mitigation), MISC no. 144
- [Understanding four CUPS vulnerabilities](https://connect.ed-diamond.com/misc/misc-138), MISC no. 138, with Nicolas Vieux

## Links

- [Vulnerability research workflow](https://github.com/romain-deperne/vulnerability-research-workflow)
- [LinkedIn](https://fr.linkedin.com/in/romain-deperne%F0%9F%9B%A1%EF%B8%8F-580920221)
- [Email](mailto:romaindep@protonmail.com)
