---
title: Monthly Impact Journal
category: journaling
subcategory: reflection
description: Roll up multiple Weekly Impact Journals into a single, citation-backed monthly summary aligned to your priorities.
llm_tools:
  - Microsoft 365 Copilot
  - Loop or OneNote
  - SharePoint or OneDrive
  - Teams
inputs:
  - Month timeframe (start and end dates)
  - Weekly journal documents or links
  - Core priorities or focus areas
  - Key initiatives or accounts to spotlight
  - Citation format or reference style
  - Instructions for summarizing impact vs. effort
---

# Monthly Impact Journal

Use this prompt to stitch together your [Weekly Impact Journals](./weekly-impact-journal.md) into a single narrative that shows compounding impact, persistent risk, and lessons learned through the month.

## Context

Feed the model the month you want to summarize, attach or paste each weekly journal, and restate the core priorities you are measured against. This ensures the model cites only the supplied journals and keeps the narrative tethered to the same focus areas you share with business or career audiences.

## Prompt

```text
Using the following weekly journals, generate a monthly summary that captures the following details:

- What went well this month?
- What didn't go well this month?
- What were my biggest challenges this month, and how did I address them?
- What did I learn this month?

Only cite relevant sources from the weekly journals to support each point made in the summary. Ensure each section is specific and relevant to my core priorities, and avoid generic statements.

---

For additional context, the journal should align with my core focus areas:

- <FOCUS AREA 1>
  - <DESCRIPTION>
- <FOCUS AREA 2>
  - <DESCRIPTION>

---

Important interactions to consider as context for this month:
- <Initiative or highlight + why it matters>

---

Here are the weekly journals to reference:

- <WEEKLY JOURNAL 1 OR LINK>
```

> [!TIP]
> If using M365 Copilot, attach or add the files from your business OneDrive, SharePoint, or Loop workspace so it can reference them directly.

## Tips

- Run the [Weekly Impact Journal](weekly-impact-journal.md) prompt every Friday so you always have clean inputs for the month-end rollup.
- Store weekly journals in a Loop workspace or OneNote section named after the quarter—Copilot can reference them quickly when the links share friendly titles.
- When highlighting challenges, reference both the week the issue appeared and the week you mitigated it so reviewers can trace closure.
- Pair this monthly summary with the [Performance Review Impact Assessment](../../career/development/performance-review-impact-assessment.md) to accelerate quarterly or annual narratives.
