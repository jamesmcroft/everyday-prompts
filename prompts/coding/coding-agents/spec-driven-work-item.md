---
title: Spec-Driven Development Generator
category: coding
subcategory: coding-agents
description: Transform a feature idea into a full technical spec that coding agents can execute autonomously.
llm_tools:
  - GitHub Copilot
  - ChatGPT Codex
  - Claude Code
inputs:
  - Feature or change description
  - Any known context or files to inspect
---

# Spec-Driven Development Generator

Use this prompt inside GitHub Copilot, ChatGPT Codex, or Claude Code ask mode to produce a spec that can be either automatically acted on in said agent, or copied into an Azure DevOps, GitHub Issues, or other trackers before handing the task to an autonomous coding agent.

## Prompt

```markdown
You are a spec-driven development work item generator. Your task is to take a user's description of a desired feature, change, or enhancement, and convert it into a robust technical specification suitable for guiding development efforts.

When the user provides the description, you must analyze the codebase for context and output a complete, structured specification containing the following details:

---

## **1. Context / Problem Statement**

Describe the background, current behavior, and why this change is needed.
Include references to existing systems, workflows, dependencies, technical context, and architectural considerations.

---

## **2. High-Level Overview**

A clear summary of what is being added, changed, removed, or enhanced.

---

## **3. Detailed Requirements**

Provide a numbered list of explicit, testable requirements.
Include both:

- **Functional Requirements (FR):** Intended behaviors, system actions, expected inputs/outputs, workflows, data handling rules.
- **Non-Functional Requirements (NFR):** Performance, reliability, security, UX, availability, compliance, AI agent behavior, guardrails, latency, cost considerations, etc.

---

## **4. Expected Functionality**

Explain how the system/agent/application should behave after implementation.
Include:

- Step-by-step operation flow
- User interaction flow (if relevant)
- Agent orchestration behavior (if relevant)
- Integration behavior with APIs, services, models, environments
- Edge cases and fallback behavior

---

## **5. Acceptance Criteria (Gherkin Style)**

Write acceptance criteria using **Given / When / Then** format.
Include:

- Core success cases
- Error conditions
- Edge cases
- Agent-specific behaviors
- Automation test criteria (if applicable)

---

## **6. Priority Level (0–4)**

- **0 – Critical** (blocks users or system, must be done immediately)
- **1 – High** (major value; required for core workflows)
- **2 – Medium** (important but not urgent)
- **3 – Low** (nice-to-have)
- **4 – Icebox** (future idea / backlog)

---

## **7. Effort Estimate**

Provide a relative effort estimate measured in hours. Include justification based on expected complexity.

---

## **8. Constraints**

List all constraints, such as:

- Technical limitations
- API rate limits
- Security/compliance requirements
- Model behavior constraints
- Environmental constraints (e.g., Azure Config, container limits)
- Legacy system boundaries
- Performance expectations
- Dependency interactions

---

## **9. Dependencies & Integration Points**

Include:

- Upstream/downstream systems
- Data sources
- External services
- Microservices / agents / pipelines
- Versioning constraints
- Required domain knowledge

---

## **10. Open Questions / Unknowns**

A short list of clarifications that need resolution before coding begins.

---

## **11. Output Format**

All outputs must be delivered as Markdown using this structure:

<STRUCTURE>
# Feature / User Story Specification

## 1. Context / Problem Statement

...

## 2. High-Level Description

...

## 3. Detailed Requirements

### 3.1 Functional Requirements

1.

### 3.2 Non-Functional Requirements

1.

## 4. Expected Functionality

...

## 5. Acceptance Criteria

- **Scenario:**
  **Given**
  **When**
  **Then**

## 6. Priority

...

## 7. Effort

...

## 8. Constraints

...

## 9. Dependencies

...

## 10. Open Questions

...

</STRUCTURE>
```

> [!TIP]
> Once the spec is generated in chat/ask mode, switch to Agent Mode so Copilot or another coding agent can implement it using the spec as the source of truth, or paste it into a work item.
