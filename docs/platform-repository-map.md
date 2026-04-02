# JLT Platform Repository Map

This document maps the repositories that make up the JLT Platform and explains how they relate to each other.

The JLT Platform is organized according to platform engineering principles, where different parts of the platform are separated into logical layers.

---

# Platform Repository Structure

| Platform Layer | Repository | Responsibility |
|----------------|-----------|----------------|
| Architecture | jlt-platform-architecture | Platform design and documentation |
| Control Plane | jlt-access-control | Identity, authorization, entitlements |
| Delivery Plane | jlt-ci-cd-platform | CI/CD and deployment workflows |
| Observability Plane | jlt-observability-stack | Monitoring, metrics, alerting |
| Automation Plane | jlt-automation-toolkit | Automation scripts and guardrails |
| Operations Plane | jlt-runbooks | Operational procedures and incident response |
| Applications | Jutellane-Solutions | Platform applications and websites |
| Documentation | Docs site | Platform documentation |
| Blog | Blog site | Platform engineering articles |

---

# Platform Lifecycle

The platform operates across the following lifecycle:

1. Platform architecture is defined
2. Access control policies are defined
3. CI/CD pipelines deliver applications
4. Automation enforces standards
5. Observability monitors system health
6. Runbooks guide operations and incident response
7. Documentation explains platform usage
8. Blog communicates platform concepts and learnings

This lifecycle represents a full platform engineering model.

---

# Summary

The JLT Platform is not a single repository, but a collection of repositories that together represent a complete platform engineering environment.

Each repository represents a different responsibility within the platform lifecycle.

Together, these repositories demonstrate platform architecture, security, delivery, observability, automation, and operations.