---
title: Weekly Impact Journal
category: journaling
subcategory: reflection
description: Create a first-person weekly recap grounded in calendar, email, chat, and file data with explicit ties to your focus areas and citations.
llm_tools:
  - Microsoft 365 Copilot
inputs:
  - Week start and end dates
  - Data sources to inspect (calendar, email, chat, files)
  - Core focus areas or goals
  - Current initiatives or customers to spotlight
  - Required citation format or link structure
  - Important interactions that must be referenced
---

# Weekly Impact Journal

Use this prompt when you want Microsoft 365 Copilot to sweep your workplace artifacts and assemble a concise but citation-backed weekly journal. It helps you maintain an auditable trail of wins, risks, and insights that plug directly into business or career updates.

## Context

This journal is meant to serve multiple audiences: your future self, your manager, and downstream deliverables such as business reviews or performance plans. Feed the model the exact time range, the data sources it is allowed to mine, the focus areas you are measured on, and any meetings or threads that simply cannot be missed.

## Prompt

```text
Using my calendar, emails, Teams, and files from <WEEK DATE RANGE>, generate a weekly summary that captures the following details:

- What went well this week?
  - Describe my key achievements, project milestones, successful collaborations, and any positive feedback received.
- What didn't go well this week?
  - Highlight any of my specific challenges, setbacks, or areas where expectations were not met.
- What's my biggest challenge right now?
  - Identify the most significant obstacle or issue I am currently facing in my work.
- What can I learn from this week?
  - Reflect on lessons learned, insights gained, and areas for personal or professional growth.

Always cite relevant sources from my calendar, emails, Teams, and files to support each point made in the summary. Ensure each section is specific and relevant to my core focus areas, and avoid generic statements. Ensure the narrative is in the first person perspective from my point of view.

---

Here's an example:

<EXAMPLE>
**What went well this week?**

- In the Thursday weekly sync with the Team, I successfully demonstrated the new software capabilities of our agentic AI workflow, which received positive feedback from the management team and is on track for deployment next week. We also finalized the project plan for the upcoming agent enhancements, ensuring all stakeholders are aligned on timelines and deliverables.
- In my customer meeting on Tuesday, Matt acknowledged "we are really getting there thanks to your engineering efforts", highlighting the progress made in improving customer experience through our recent engagements. We are seeing tangible improvements in customer trust as a result of our focused efforts on improving communication.

**What didn't go well this week?**

- I was asked during a call for explicit criteria for our change management processes; while owners agreed to follow up, this remains an open clarity that is affecting our ability to continue. I need to ensure we have a clear and documented process in place to avoid similar issues in the future.
- A code issue blocked me from re-running my tests locally during demos this week; I used screenshots to keep the demo moving and committed to a recorded walkthrough later. This highlighted the need for better pre-demo preparation and testing to avoid technical hiccups.
</EXAMPLE>

---

For additional context, the journal should align with my core focus areas:

- <FOCUS AREA 1>
  - <DESCRIPTION>
- <FOCUS AREA 2>
  - <DESCRIPTION>

---

Important interactions to consider as context for this week:
- <YYYY-MM-DD - Meeting or milestone + why it matters>
- <YYYY-MM-DD - Email thread or file + decision captured>
```

## Tips

- Run this prompt at the end of each week to maintain a consistent record of your impact and challenges.
- Pair this journal with the [Performance Review Impact Assessment](../../career/development/performance-review-impact-assessment.md) prompt to fast-track quarterly or annual submissions.
- If your business audience expects executive-ready bullets, keep each citation visible so they can drill into the source material without exporting additional notes.
- Maintain a running "Important interactions" list during the week; paste it into the prompt so Copilot knows which calls, escalations, or files cannot be missed.
- After Copilot generates the draft, stash it in Loop or OneNote so you can build longitudinal insights before your next career conversation.
