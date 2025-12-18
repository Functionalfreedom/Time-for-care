# Documentation Index — Time for Care

This documentation explains *why* this project exists, *what problem it addresses in Canada’s healthcare system*, *how the proposed system works at a high level*, and *where its limits are*.

The documents are designed to be read top-to-bottom, but each file stands on its own.

---

## 1. The Problem

**01_problem.md**  
Explains the core issue: how documentation friction and administrative load reduce patient care capacity in Canadian hospitals.

---

## 2. System Overview

**02_system_overview.md**  
A plain-language explanation of the proposed system, what it does, and — critically — what it does *not* do.

---

## 3. Hospital Bottlenecks

**03_hospital_bottlenecks.md**  
Describes the specific workflow and administrative bottlenecks observed in Canadian hospital settings.

---

## 4. Solution Architecture

**04_solution_architecture.md**  
Outlines the conceptual architecture of the system without deep technical jargon, focusing on safety, reversibility, and clinician control.

---

## 5. Safety & Failure Modes

**05_safety_and_failures.md**  
Details the system’s safety philosophy, fail-silent behavior, and known failure scenarios.

---

## 6. Simulation & Validation Model

**06_simulation_model.md**  
Explains the simulation approach used to estimate potential throughput improvements and validate assumptions.

---

## 7. Known Limitations

**07_known_limitations.md**  
An honest accounting of what this project does not solve and where uncertainty remains.

---

## 8. Roadmap

**08_roadmap.md**  
Describes potential future directions, collaboration paths, and research next steps.

---

## 9. Glossary

**glossary.md**  
Defines key terms used throughout the documentation for non-technical readers.

---

## Supporting Architecture Documents

These documents define non-negotiable system rules and failure behaviors.

- **../architecture/safety_invariants.md**  
  The core principles that must always hold for the system to be considered safe.

- **../architecture/failure_modes.md**  
  A taxonomy of how the system can fail and how it responds safely.

---

## Simulations

- **../simulations/README.md**  
  Overview of simulation assumptions, scope, and limitations.

---

## Source Code

- **../src/README.md**  
  Explains the purpose and boundaries of the reference codebase.

---

## Legal & Governance

- **../LICENSE** — MIT License  
- **../DISCLAIMER.md** — Non-clinical, research-only disclaimer  
- **../CONTRIBUTING.md** — Contribution guidelines  
- **../CODE_OF_CONDUCT.md** — Community standards

---

### How to Read This Repository

If you are:  
- **A clinician** → Start with `01_problem.md`  
- **A policymaker or researcher** → Start with `06_simulation_model.md`  
- **A developer** → Start with `src/README.md`  
- **A reviewer or auditor** → Start with `05_safety_and_failures.md`