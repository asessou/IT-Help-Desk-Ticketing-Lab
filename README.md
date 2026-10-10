# IT Help Desk Ticketing Lab

## Project Overview

This project simulates entry-level IT Help Desk work using documented incident tickets, systematic troubleshooting, and clear follow-up actions.

The lab uses a fictional organization, Northstar Medical Group (NMG), to practice incident documentation and technical troubleshooting.

## Objectives

- Document user-reported incidents.
- Record troubleshooting steps and verified results.
- Distinguish confirmed evidence from assumptions.
- Identify incident impact and urgency before assigning priority.
- Document resolutions and follow-up actions.
- Practice version control with Git and GitHub.

## Tools and Environment

- Windows Server 2022
- PowerShell
- Active Directory Domain Services (AD DS)
- DNS Server
- Git
- GitHub
- Oracle VirtualBox

## Project Structure

```text
IT-Help-Desk-Ticketing-Lab/
├── tickets/
│   ├── INC-1001.txt
│   └── INC-1002.txt
├── docs/
├── reports/
└── README.md
```

## Incident Tickets

### INC-1001 — Account Access

Documents an account-access report for a fictional employee. The investigation includes account status and group-membership checks, with authorization verification required before restoring access.

### INC-1002 — Network Connectivity

Documents a reported workstation connectivity issue. Server-side tests checked gateway connectivity, external IP connectivity, DNS resolution, and the status of DNS and Active Directory services.

**Important limitation:** The network tests were performed on the Windows Server domain controller. A separate client workstation was not available, so the reported workstation issue remains unverified.

## Troubleshooting Approach

1. Gather the user's symptoms and determine business impact.
2. Inspect the relevant system configuration.
3. Perform targeted diagnostic tests.
4. Record each test and its result.
5. Avoid making changes without sufficient evidence and authorization.
6. Document the next action, resolution, or escalation.

## Learning Outcomes

This project provides hands-on practice with incident documentation, basic Windows network diagnostics, DNS, Active Directory service checks, and Git-based change tracking.

## Disclaimer

All employee names, departments, and incident scenarios are fictional and intended for educational purposes. No production systems or real employee accounts are represented by these tickets.