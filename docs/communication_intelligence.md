# Communication Intelligence Module

The Communication Intelligence module captures and processes Slack communication.

---

## Responsibilities

- Capture Slack messages
- Process communication events
- Extract tasks and blockers
- Detect urgent issues
- Update knowledge base

---

## Architecture

```mermaid
flowchart TD

A[Slack Workspace]

A --> B[Slack Events API]

B --> C[Communication Processor]

C --> D[Message Database]

C --> E[AI Processing Engine]

E --> F[Task Extraction]

E --> G[Blocker Detection]

E --> H[Update Extraction]

F --> I[Knowledge Base]

G --> I

H --> I
```