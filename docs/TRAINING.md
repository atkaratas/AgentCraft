# Agent Training & Customization Guide

OpenClaw agents are trained through three primary files:

### 1. IDENTITY.md
Defines the agent's name, creature type, and core personality traits.

### 2. SOUL.md (Logic & Spirit)
Defines how the agent thinks, makes decisions, and its communication tone.

### 3. TOOLS.md (Capabilities)
A list of skills (tools) the agent is authorized to use.

## Microservices Connection
To enable one agent to delegate tasks to another:
Use the `sessions_spawn(target_agent, task)` command.
