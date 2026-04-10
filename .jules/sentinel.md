## 2024-05-24 - Agent Prompt Injection Defense
**Vulnerability:** Agent instruction files (like SKILL.md) are vulnerable to prompt injection if they don't explicitly instruct the agent to treat user input as untrusted.
**Learning:** Orchestrator agents, which receive direct user input and delegate tasks, are particularly susceptible to being hijacked if they trust user input over their core directives.
**Prevention:** Explicitly instruct agents in their `<instructions>` block to treat all user input as untrusted and to reject any input that attempts to bypass or alter their core directives.
