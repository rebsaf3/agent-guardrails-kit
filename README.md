```markdown
# Agent Guardrails Kit
A reusable kit for building business agents that are safe, predictable, and auditable.

This kit is platform agnostic.
Use it for Copilot Studio agents, Power Automate workflows, custom LLM apps, or any system where an agent might answer questions or trigger actions.

This kit focuses on practical guardrails.
No guessing
No invention
Approved sources only
Selection and disambiguation before targeted actions
Refusal and no knowledge patterns
Run logs as evidence
Test packs to prevent drift
Change control for safe iteration

## Who this kit is for
End users and stakeholders
People who need to trust what agents do and why

Builders and operators
People who implement agents and need repeatable standards

Leaders and risk partners
People who need auditability, consistency, and visible change control

## What you get in this repo
docs
Plain language explanations of the guardrails and why they matter

templates
Copy and paste templates for agent instructions, contracts, schemas, messages, and tests

governance
Change control and change log templates that keep behavior stable

redaction
Public repo checklist so you do not leak sensitive details

examples
Filled examples that show correct usage

## The core guardrails
1. Scope discipline
The agent must have an explicit purpose and explicit non goals.

2. Approved sources only
Answers must be grounded in approved knowledge sources only.

3. No invention
If the answer is not confirmed, the agent must not guess.

4. Selection and disambiguation
Before any targeted action, the agent must confirm the exact target identifiers.

5. Refusal and no knowledge patterns
Safe fallback responses are required and standardized.

6. Audit evidence
Every run should produce a structured run log.

7. Testing and change control
Behavior changes require tests and a change log entry.

## Quick start
1. Copy templates/instructions/Agent_Instructions_Template.md into your repo
2. Fill in the purpose, sources, tools, and refusal rules
3. Copy templates/tests/Test_Pack_Template.md and define passing behavior
4. Add selection and disambiguation rules from docs/03_Selection_And_Disambiguation_Standard.md
5. Use the schemas in templates/schemas to structure requests and run logs

## License
MIT
