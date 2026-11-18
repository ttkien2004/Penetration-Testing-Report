# Active Directory Assessment — Practice Methodology

> A high-level assessment framework based on the three Active Directory lab sets documented in OSCP-A/B/C. This is a methodology summary, not a lab route, attack recipe, or claim of a production domain compromise.

## Purpose

Understand how identity, privilege relationships, host configuration, and internal network reachability influence security across a Windows domain.

## Assessment stages

### 1. Determine access and network context

- Identify the authorized entry point and the permissions already available.
- Inventory domain membership, reachable hosts, service roles, and network interfaces.
- Document any difference between the entry machine's visible network and the broader internal lab network.

### 2. Map domain relationships

- Collect the minimum domain information needed to understand identities, groups, machine roles, and access relationships.
- Review potential privilege paths using a graph-oriented view and validate important relationships independently.
- Distinguish local administrator rights from domain-level roles and permissions.

### 3. Assess credential and authentication exposure

- Review how credentials appear in configuration, application output, or administrative artifacts.
- Evaluate whether existing permissions or credential material create unintended cross-host access in the lab.
- Consider Kerberos-related risks and the difference between service access and user-level or administrative access.

### 4. Evaluate cross-host reachability

- Map the relationship between authentication rights and network connectivity.
- In segmented labs, document the presence and scope of an authorized test tunnel or route.
- Describe any lateral-movement observation in terms of identities, permissions, and verification results rather than copying exploit commands.

### 5. Verify outcomes and preserve evidence

| Question | Evidence to retain privately |
| --- | --- |
| What access was provided initially? | Identity and group context |
| Which internal assets were in scope? | Redacted topology / service inventory |
| Which relationship was examined? | Access path or privilege relationship |
| What changed after a test? | Before/after authorization context |
| Was the objective confirmed? | Explicit lab verification record |

## Tools practiced

**BloodHound / SharpHound, NetExec, Impacket, Evil-WinRM, Ligolo-ng, Chisel, and native Windows utilities** appear in the training reports. The original data and lab-specific commands are not reproduced here.

## Key takeaways

- A single host's local privileges and a domain's broader trust relationships must be assessed separately.
- Credential handling and unexpected reuse can materially change accessible resources.
- Network pivoting and identity-based access are distinct elements; both must be understood to describe a multi-host observation accurately.
- Structured evidence is necessary to explain why a proposed domain path is plausible and which stages were actually confirmed.

[Back to portfolio](../README.md)
