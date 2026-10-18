# Architecture overview

SCFMS is a modular Java desktop application built as a collaborative course project. The original source remains private.

```text
                  Java Swing desktop interface
                              |
       +----------------------+----------------------+
       |                      |                      |
 Access / credentials     Monitoring          Security administration
       |                      |                      |
       +----------------------+----------------------+
                              |
             Shared authentication / validation
                              |
               In-memory data and event models
```

## Areas represented in the codebase

- **Presentation:** Login window, main application window, administrative panels.
- **Access workflows:** Permission checking, access requests, credential handling, reporting.
- **Monitoring workflows:** Monitoring events, telemetry models, alerts, coordinator components.
- **Security administration:** Administrative operations, incident-related workflows, emergency-override models.
- **Shared infrastructure:** Authentication, input validation, session management, common entities and event logs.

## Scope and limits

The code is an educational demonstration. It uses an in-memory data store and simulated behavior in several security-related workflows. This document intentionally omits implementation details, credentials, exact validation logic, and course assessment materials.
