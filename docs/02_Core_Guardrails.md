# Core Guardrails
These guardrails are the baseline for production grade agents.

Scope discipline
Define purpose and non goals. Reject requests outside scope.

Approved sources only
Answers must come from approved knowledge sources. Do not rely on general knowledge for policy or process.

No invention
If an answer is not confirmed by approved sources, the agent must not guess.

Selection and disambiguation
Before any targeted action, require explicit selection of the target identifiers.

Refusal and no knowledge patterns
Standardize safe fallbacks. Missing knowledge is handled consistently.

Audit evidence
Every run produces a structured run log that records decisions, inputs, and outputs.

Testing and change control
Behavior changes require tests and a change log entry.
