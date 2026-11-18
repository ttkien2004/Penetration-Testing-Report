# OSCP-B — Practice Reflection

**Type:** OSCP-style training exercises  
**Scope documented:** Three standalone lab machines and one Active Directory set  
**Source:** Private OSCP-B practice report  
**Publication:** High-level reflection only; no walkthrough or challenge answer material

## What I practiced

- Combined TCP and UDP discovery with service review across Windows and Linux lab systems.
- Evaluated configuration exposure, service-level access, and application security observations within authorized exercises.
- Assessed local privilege context, differentiating low-privilege access from administrator or root-level capabilities.
- Investigated domain relationships, internal service access, and the impact of credentials and permissions on cross-host reachability.
- Documented successful and unsuccessful validation attempts in a consistent reporting format.

## Reporting approach

The source report used dedicated sections for the Active Directory set and standalone systems. I captured the relevant service context, validation evidence, and outcomes as separate steps so later review could distinguish established results from work in progress.

## Lessons learned

**A network assessment is not limited to web ports.** Systematic service enumeration exposed multiple forms of access and configuration behavior worth investigating.

**There can be more than one way to observe command execution.** In lab testing, I learned to distinguish actual service-side execution from whether an interactive shell was available.

**Validate privilege claims.** A useful report identifies which security context was reached, not just which test was attempted.

## Skills demonstrated

`Network reconnaissance` · `Service analysis` · `Cross-platform privilege assessment` · `Active Directory mapping` · `Lateral-access reasoning` · `Evidence-based reporting`

> No host identifiers, exploit paths, passwords, flags, or private lab evidence are included here.

[All practice summaries](README.md) · [Portfolio](../README.md)
