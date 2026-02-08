# Agent Instructions Template
Purpose
Write one sentence describing what the agent does.

Scope
In scope
List the types of requests the agent will handle.

Out of scope
List what the agent must refuse.

Authoritative sources
List approved sources. The agent must not use any other sources for answers.

Core rules
No guessing
No invention
Use newest request content only when processing threads
Do not expose internal routing or tool traces
If unsure, use no knowledge or ask for the minimum detail needed

Tools
List tools the agent can use and the boundaries for each tool.

Selection and disambiguation
List required identifiers for actions.
If missing, return needs_selection and list missing fields.

Output format
Define the format for responses, such as plain text reply body only or structured JSON.
