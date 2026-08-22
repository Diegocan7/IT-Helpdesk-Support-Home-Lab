# IT-Helpdesk-Support-Home-Lab
A self-hosted lab simulating the IT operations of a small company built as a hands-on portfolio project

## Why this exists

Job descriptions for IT support roles typically ask for experience with employee onboarding/offboarding, SaaS account provisioning, asset & MDM management, security compliance (SOC 2 / ISO 27001), internal documentation, and process automation. Rather than just listing these as skills, this lab **builds and operates** a small simulated company IT environment to demonstrate them directly.

## The scenario

A fictional 15–20 person company (`corp.me-lab.local`). I act as the sole IT person: standing up the infrastructure, then running it day to day — resolving tickets, provisioning/deprovisioning accounts, auditing device compliance, and documenting everything as I go.

## Tech stack

- **Hypervisor:** Hyper-V (Windows 11 Pro host)
- **Directory services:** Windows Server 2022 — Active Directory Domain Services, DNS, Group Policy
- **Ticketing:** osTicket / Zammad *(planned  (2) )*
- **Asset management:** Snipe-IT *(planned  (3) )*
- **MDM & compliance:** Fleet / Intune trial, CIS benchmarking *(planned (4) )*
- **Automation:** Python (Google Workspace Admin SDK) *(planned (5) )*
- **Documentation:** BookStack / this repo *(planned (6) )*

## Project phases

| Phase | Focus | Status |
|---|---|---|
| 1 | Active Directory domain controller + client, OU structure, baseline GPO | Complete — [write-up](docs/phase1-active-directory.md) |
| 2 | Helpdesk ticketing workflow | Planned |
| 3 | Asset & license management (Snipe-IT) | Planned |
| 4 | MDM & SOC 2 / ISO 27001 compliance mapping | Planned |
| 5 | Onboarding/offboarding automation | Planned |
| 6 | Internal documentation / knowledge base | Planned |

## Repo structure

```
docs/          Write-ups for each phase, in depth
screenshots/   Supporting screenshots, organized by phase
scripts/       Automation scripts (added from Phase 5 onward)
```

## About me

Built by Diego Canodemaj, BSc Informatics & Telecommunications student at the National and Kapodistrian University of Athens.
