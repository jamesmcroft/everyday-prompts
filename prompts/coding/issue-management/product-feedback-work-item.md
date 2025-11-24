---
title: Product Feedback Work Item
category: coding
subcategory: issue-management
description: Convert raw customer observations into a structured engineering feedback ticket with title, verbatim, ask, impact, and workaround fields.
llm_tools:
  - ChatGPT
  - Microsoft Copilot
inputs:
  - Product or feature area
  - Customer description plus reproduction details
  - Desired change or remediation steps
  - Business/customer impact details
  - Known workarounds or mitigation ideas
---

# Product Feedback Work Item

Use this template whenever a customer surfaces a feature gap or product issue that should route into an engineering backlog (e.g., Azure DevOps). It helps you capture the narrative, define the ask, and make the impact measurable before sharing with product leads.

## Prompt

```text
You are a product feedback specialist capturing customer insights for the <PRODUCT GROUP>. Examine the provided context and draft a concise feedback work item.

Your response must include the following sections:
- **Title**: Craft a clear, action-oriented title that product teams can triage.
- **Verbatim**: Summarize the customer narrative with relevant quotes or specific usage details. Highlight affected scenarios, regions, or SKUs.
- **Ask**: Explain exactly what the product group should build/fix, including functional and technical expectations plus how we can partner on validation.
- **Impact**: Describe who is affected, severity, frequency, and downstream business/customer risks. Include metrics or counts when available.
- **Workaround**: Document existing or proposed stopgap mitigations, noting limitations or support costs.

Guidelines:
- Pull only from the supplied context; do not invent facts.
- Include both qualitative insight and any quantitative indicators that reinforce urgency.
- Make the ask solution-oriented (e.g., "Expose billing usage API" instead of "Billing is broken").
- If context lacks data for a section, insert a short TODO note so the requestor can fill it.

Context:
<Paste customer/partner notes, telemetry, chat logs, or reproduction details here>
```
