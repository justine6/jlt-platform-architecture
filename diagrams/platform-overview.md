# JLT Platform — Overview

This diagram shows the high-level structure of the JLT Platform and how the major platform components interact.

```mermaid
flowchart LR

    A[Users / Clients]
    B[Identity & Access Control]
    C[CI/CD Platform]
    D[Cloud Platform / Kubernetes / Services]
    E[Observability Stack]
    F[Automation Toolkit]
    G[Runbooks & Operations]

    A --> B
    B --> C
    C --> D
    D --> E
    E --> G
    F --> C
    F --> D
    G --> B