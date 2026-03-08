# Components of AI Project Manager

The AI Project Manager consists of several intelligent modules.

---

## Core Modules

1. Communication Intelligence
2. Task Extraction Engine
3. Blocker Detection System
4. Urgent Issue Detection
5. Knowledge Base
6. AI Chatbot

---

## Component Architecture

```mermaid
flowchart TD

A[Slack Communication]

A --> B[Communication Intelligence]

B --> C[Task Extraction]

B --> D[Blocker Detection]

B --> E[Urgent Detection]

C --> F[Knowledge Base]

D --> F

E --> F

F --> G[Vector Database]

G --> H[AI Chatbot]
```