# Penetration Testing Portfolio

A curated portfolio of **hands-on penetration testing practice**, assessment methodologies, and security research. The goal is to demonstrate how I approach testing, validate technical observations, and document results in controlled lab environments.

> **Context:** The OSCP-A/B/C entries summarize practice lab work. They are **not** the OSCP certification, official exam submissions, customer engagements, or public challenge walkthroughs. Original lab reports are retained privately.

## Practice at a glance

| Area | Experience documented |
| --- | --- |
| OSCP-style technical reports | 3 privately maintained reports (OSCP-A, OSCP-B, OSCP-C) |
| Standalone practice targets | 9 lab machines across Linux and Windows |
| Active Directory practice | 3 multi-host lab sets |
| Assessment activities | Reconnaissance, service enumeration, vulnerability validation, access verification, local privilege assessment, and AD path analysis |
| Reporting workflow | Structured technical notes, reproducible evidence in private reports, and clear descriptions of observed outcomes |

These counts describe **lab exercises and written practice**, not production penetration testing experience.

## What this portfolio demonstrates

- **Web-facing services:** Discovered HTTP attack surfaces, evaluated exposed content and application behavior, and reviewed vulnerable service or dependency conditions in controlled labs.
- **Infrastructure:** Enumerated TCP/UDP services, assessed access boundaries and exposed credentials, and validated Linux/Windows privilege escalation behavior in practice environments.
- **Active Directory:** Reviewed domain topology and privilege relationships, investigated credential-related attack paths, and practiced controlled network pivoting and lateral movement.
- **Technical documentation:** Maintained three OSCP-style reports with testing narratives, validation evidence, and organized findings. The public summaries omit exercise solutions.

## Repository contents

| Path | Contents |
| --- | --- |
| [`methodologies/web-pentesting.md`](methodologies/web-pentesting.md) | Web-service assessment workflow drawn from practice |
| [`methodologies/infrastructure-pentesting.md`](methodologies/infrastructure-pentesting.md) | Network, Linux, and Windows assessment workflow |
| [`methodologies/active-directory-assessment.md`](methodologies/active-directory-assessment.md) | AD-oriented assessment framework |
| [`sample-reports/`](sample-reports/README.md) | Public-safe OSCP-A/B/C practice reflections and an independent-report template |
| [`research/vulnerability-research.md`](research/vulnerability-research.md) | Reserved index for future authorized research publications |

### Practice report reflections

- [OSCP-A — Practice Summary](sample-reports/oscp-a-practice.md)
- [OSCP-B — Practice Summary](sample-reports/oscp-b-practice.md)
- [OSCP-C — Practice Summary](sample-reports/oscp-c-practice.md)

Each reflection describes scope, skill areas, documentation habits, and learning outcomes **without associating a specific target with its solution**.

## Tools encountered in the lab work

| Task | Examples used in the source reports |
| --- | --- |
| Service and web discovery | Nmap, ffuf, SearchSploit |
| Linux and Windows local assessment | LinPEAS, WinPEAS, native system utilities |
| Internal network and AD review | BloodHound, SharpHound, NetExec, Impacket |
| Controlled connectivity and access validation | SSH, WinRM, Ligolo-ng, Chisel |
| Reproducible lab tooling | Docker, Python, C toolchain |
| Reporting | SysReptor |

Tool names indicate hands-on exposure in the associated work; they do not imply expert-level proficiency with every tool.

## Scope, provenance, and publication boundaries

The three original reports include challenge-specific data that is **not published here**. This repository intentionally excludes host addresses, usernames, passwords, hashes, flags, payloads, exact exploit commands, and step-by-step challenge solutions. The methodology files are generalized descriptions and are **not replacements for the original reports**.

The repository does not assert a client engagement, an earned OSCP certification, or a production security finding. Results from lab activities are labeled as such. There are no CVSS scores or remediation sections in the published practice summaries.

## Planned additions

The research index reserves space for future, separately reviewed publications about **SNOWYDRIVE** and **CVE-2026-97229**. The underlying reports are **not included yet** and are not represented as published work here.

---

**Portfolio focus:** practical assessment methodology, technical reasoning, and clear lab documentation.
