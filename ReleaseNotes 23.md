# Release Notes 1.21.1

**Release Version:** 2026 version 1.21.1

This communication is for notifying users of NAV AI about the enhancements made to the application.

---

## Features Released

### AI Assistant

Phase one of the AI Assistant is launched with contextual prompt suggestions, guided entity creation, on-demand Q&A and 7 management domains. Users can Create or list entities leveraging the AI Assistant capabilities while chatting in natural language. More capabilities and knowledge planned to be included in the following releases.

**Capabilities included:**

- Workspace Management
- Agent Management
- Workflow Management
- Dataset Management
- System Prompts Management
- Tag Management
- Module Management – Read operations only

---

### Hybrid Workflows

You can now combine multiple handoff types within a single multi-agent workflow, giving you precise control over how agents pass execution to one another — and a live visual preview to validate your configuration before running anything.

Previously, workflows were limited to a single handoff pattern. This release introduces a unified configuration interface that lets you mix and match all three available handoff types across agent nodes in the same workflow.

Each agent node must have exactly one handoff type assigned:

- **Agentic handoffs** let the LLM reason about user intent and decide autonomously whether to proceed or ask for clarification. This is the right choice when the next step depends on understanding context rather than evaluating data.
- **Linear handoffs** enforce strict sequential execution, guaranteeing that critical steps always happen in order. Use these wherever predictability is non-negotiable.
- **Conditional handoffs** introduce deterministic, rule-based routing at a single decision point — one explicit branch plus a default fallback — so the workflow can make controlled branching decisions without involving the LLM.

Combining all three means you get intelligent interpretation where ambiguity exists, reliable sequencing where order is critical, and transparent, auditable branching where business rules apply.

As you configure your workflow, a real-time preview renders agents and their handoffs as a directed graph, giving you immediate visual feedback on the structure and flow before execution begins.

---

## Other Improvements

- **Structured datasets Input Validation**
    - Column inputs now enforce data types automatically. Number columns accept only numeric values, and string columns accept only text — invalid characters are silently blocked as you type. Boolean columns (supporting Yes/No, True/False, 1/0, and y/n) are now rendered as a dropdown with the appropriate values, and date columns display a date picker for easy selection.
- More descriptive error messages
- New Workspaces are now created with the global chat disabled by default
- Tooltip message on the 'Any handoff' purple icon for improved UX
- Resolved various bugs on Workflows
