# Four Iteration Test Prompts

These prompts were used to test the Enterprise Change Readiness Advisor in Microsoft Copilot Studio.

## Iteration 1 — Foundation

**Setup:** Agent instructions only. No supporting documents or organizational policy.

**Test Prompt:**

A production infrastructure change has been proposed. Assess whether sufficient information is available for CAB decision readiness. Explain what evidence you need, what risks you can reasonably identify, and which decisions must remain with authorized human approvers.

## Iteration 2 — Evidence

**Setup:** Attach the five fictional change-specific PDF documents in a fresh test conversation.

**Test Prompt:**

Assess CR-2026-047 for CAB decision readiness using the five attached documents. Analyze the evidence across documents, identify material risks, contradictions, missing information, and questions requiring human judgment. Provide an evidence-based CAB briefing.

## Iteration 3 — Governance

**Setup:** Add ECM-001 as an organizational Knowledge source. Attach the same five change-specific PDFs in a fresh test conversation.

**Test Prompt:**

Assess CR-2026-047 and all attached supporting evidence for CAB readiness against the applicable organizational standards available in your Knowledge. Identify the specific organizational requirements relevant to each material finding. Determine whether the evidence is sufficient for an authorized human to make an informed decision. Do not make the approval or rejection decision.

## Iteration 4 — Hardening

**Setup:** Apply the refined agent instructions. Retain ECM-001 in Knowledge and attach the same five PDFs in a fresh test conversation.

**Test Prompt:**

Assess CR-2026-047 and all attached supporting evidence for CAB readiness against the applicable organizational standards available in your Knowledge. Identify the specific organizational requirements relevant to each material finding. Determine whether the evidence is sufficient for an authorized human to make an informed decision. Do not make the approval or rejection decision.

## Important Notes

- Use a fresh test conversation for each iteration.
- Iterations 3 and 4 deliberately use the same test prompt.
- The comparison between Iterations 3 and 4 focuses on the effect of refined agent instructions and reporting structure.
- The agent supports CAB decision readiness; it does not approve or reject changes.
- All change documents and policies in this exercise are fictional.
