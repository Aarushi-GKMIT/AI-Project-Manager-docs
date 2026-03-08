# AI Project Manager

## Overview

The AI Project Manager is an intelligent system designed to assist software development teams by analyzing communication and extracting meaningful project insights.

The system analyzes conversations from Slack workspaces and automatically identifies:

- Tasks
- Blockers
- Updates
- Urgent issues

These insights are stored in a knowledge base and can be queried using an AI chatbot.

---

## System Overview Diagram

```mermaid
flowchart LR

A[Team Communication]
--> B[AI Project Manager]

B --> C[Task Detection]

B --> D[Blocker Detection]

B --> E[Urgent Issue Detection]

B --> F[Knowledge Base]

F --> G[AI Chatbot]
```