# Solution Architecture (Conceptual)

The proposed system explores a “sidecar” model — a lightweight companion that runs alongside existing hospital systems.

Key Characteristics:
- No direct EMR integration
- No database write access
- No clinical inference

Instead, the system:
- Observes screen context
- Captures clinician-entered fragments
- Helps assemble compliant documentation faster

Importantly:
- Clinicians remain fully responsible for content
- Notes are reviewed and signed exactly as they are today
- If removed, the hospital returns to baseline behavior

This design deliberately favors safety and reversibility over power.