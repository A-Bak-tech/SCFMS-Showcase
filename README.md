# SCFMS — Facility Management & Security System

**Collaborative computer science capstone | Troy University, CS4498 Team 1**  
**Java · Java Swing · Object-oriented design · Software testing**

> **Portfolio showcase only.** The original team source code is maintained privately to respect academic integrity and collaborative contributions. This repository contains no implementation code, compiled programs, credentials, or completed course test artifacts.

## Project overview

SCFMS is a **desktop application prototype** that demonstrates how a facility-management and security system can organize access requests, credentials, monitoring events, and administrative workflows in a single application. It was developed collaboratively for a university capstone course.

The system uses a Java Swing interface and modular Java components. It models facility access and related security operations for demonstration and testing, rather than controlling real physical security infrastructure.

## Features demonstrated in the team project

- **Authentication and sessions:** Login workflow, hashed password verification, account lockout logic, and a simulated second authentication step.
- **Role-based access control:** Evaluates permissions associated with users and facilities.
- **Credential and access workflows:** Models credential validation, access requests, visitor access, and revocation-related operations.
- **Monitoring and alerts:** Organizes simulated monitoring data, alarm events, and security-administration workflows.
- **Reports and audit records:** Provides reporting components and integrity checks for in-memory audit/event logs.
- **Desktop interface:** Java Swing windows, login prompts, and administrative panels.

These are **team-project capabilities** and are **not** a claim that one contributor implemented every feature.

## Architecture at a glance

| Layer | Responsibilities |
| --- | --- |
| Desktop presentation | Swing login and application windows, panels, dialogs |
| Application workflows | Access management, monitoring, credential handling, security administration |
| Shared services | Authentication, session handling, validation, role checks |
| Data model | Users, facilities, permissions, credentials, access/audit events |

See [Architecture](docs/architecture.md) for a high-level view.

## Testing and engineering practices

The academic project includes documented use-case test scenarios and screenshot evidence maintained in the private course repository. This showcase describes the testing approach without publishing test answers or course submission files. See [Testing overview](docs/testing-overview.md).

## My contributions

This was a **team project**. My individually attributable work is being documented against Git history before detailed ownership claims are published. See [My contributions](docs/my-contributions.md).

## Screenshots and demo

Screenshots will be added only after reviewing them for personal information, sensitive details, and permission to share. See [screenshots/README.md](screenshots/README.md).

## Project boundaries

This is an **academic prototype**, not a certified or production-ready security system. Some hardware interactions, authentication steps, and monitored events are simulated; the demo data store is held in memory. There are no claims of production deployment, real hardware integration, or compliance certification.

## Source access and reuse

The source code is intentionally not provided publicly. No software license is granted by this documentation-only repository for the original collaborative implementation. Contact the project contributors through approved channels regarding reuse or access.
