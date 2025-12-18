---
# Safety Principles and Failure Modes

Healthcare systems must fail safely.

This project adopts a **fail-silent** philosophy:
- If the system crashes, it disappears
- If confidence drops, it stays silent
- If context is unclear, it refuses to assist

### What the system must never do:
- Block clinical work
- Suggest diagnoses or treatments
- Modify EMR data automatically
- Operate without clinician awareness

### Known failure modes:
- UI changes breaking observation
- Misattributed screen context
- Increased cognitive load if poorly designed

These risks are documented openly to encourage critique and improvement.
---