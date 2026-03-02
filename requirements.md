# Requirements
This file is a guideline for creating requirements and is not needed for implementing this project.

### implementation.md
Requirements must be validated against implementation.md before something is implemented.
The requirements must be changed as long as there are contradictions between them and implementation.md.

### Versioning (mandatory)
When requirements change, the implementation flow must follow this sequence:

1. Create a new revision file: `project.v{N+1}.md` (delta from previous version).
2. Update `project.md` so it contains the consolidated latest requirements.
3. Ensure the version title in `project.md` matches the highest revision (e.g. `Project Requirements v3`).
4. Implement code changes according to the resulting `project.md`.

Do not skip step (1) when requirement scope/behavior changes.

### Human-in-the-loop (HITL)
If requirements are added/edited by a human, the agent should perform the consolidation into `project.md` and ensure the version title/state are consistent before implementation.

## Template
Can you please generate some example-requirements for an application?
The requirements should be kind of specific (not to generic).

### Base Requirements
 - Only web-applications for frontend. No native apps.
 - The system shall be usable on modern desktop and/or mobile browsers.

### Restrictions
 - not more than 10 functional requirements (base requirements excluded)
 - no non-functional requirements
