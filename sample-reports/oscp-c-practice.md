# OSCP-C — Practice Reflection

**Type:** OSCP-style training exercises  
**Scope documented:** Three standalone lab machines and one Active Directory set  
**Source:** Private OSCP-C practice report  
**Publication:** High-level reflection only; no walkthrough or challenge answer material

## What I practiced

- Identified remote services and examined the security implications of configuration and access-control behavior.
- Used controlled validation to distinguish reachability of a service from the ability to act with elevated privileges.
- Reviewed Linux and Windows local security controls, including service execution context and file access permissions.
- Investigated how inadvertently exposed authentication material can affect a multi-host Windows lab.
- Kept the assessment narrative focused on scope, observable evidence, and confirmed outcomes.

## Reporting approach

The source report records three independently scoped systems and an Active Directory exercise. My notes separate initial discovery, validation, local privilege review, and domain-level observations rather than treating the whole lab as a single unexplained result.

## Lessons learned

**Privilege depends on execution context.** File or service access is only meaningful when paired with an understanding of what account and permissions are involved.

**Simple exposures can have larger consequences.** Minor-looking security hygiene weaknesses need to be assessed in the context of other reachable systems and identities.

**Good documentation is reproducible reasoning.** Recording observations and their limitations is as important as documenting a positive result.

## Skills demonstrated

`TCP/UDP enumeration` · `Configuration review` · `Windows service analysis` · `Linux privilege assessment` · `AD access-path reasoning` · `Structured reporting`

> This reflection intentionally avoids linking any technique to a particular host or challenge and does not publish the original report.

[All practice summaries](README.md) · [Portfolio](../README.md)
