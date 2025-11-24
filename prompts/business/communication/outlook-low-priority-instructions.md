---
title: Outlook Copilot Low-Priority Instructions
category: business
subcategory: communication
description: Teach Outlook Copilot which messages can be safely deprioritized so high-signal mail stays in focus.
llm_tools:
  - Microsoft Outlook Copilot
inputs:
  - Role or function
  - Examples of mailing lists, notifications, or content that rarely need fast action
  - Phrases that signal FYI-only or no-deadline work
---

# Outlook Copilot Low-Priority Instructions

Pair this template with Outlook’s priority feature to push FYI-only or low-impact messages further down the view. Adjust and drop each of the instructions below into **Settings → Copilot → Prioritize** and tailor the placeholders to reflect your role.

> [!IMPORTANT]
> Each instruction can be added as a separate row in the Prioritize settings. These will be combined into a single instruction set that Copilot uses to rank incoming emails.

## Low Priority Instructions

```text
- Messages related to company-wide announcements (e.g., "All Hands" meetings)
- Newsletters or marketing blasts (internal "news you can use", updates, etc.)
- Automated digests (daily build summaries, reminders, etc.)
- Messages where I'm CC'd, only copied (not directly addressed), or part of FYI-only threads
- "Just keeping you in the loop" messages that don't require action from me
- Recurring status updates with no new deliverables or decisions required
- "For your reference" docs or whitepapers with no deadlines
- Invitations to optional webinars or training sessions outside of my immediate scope. My current scope: <SCOPE/PROJECT/INITIATIVE DETAILS>
- Social or community messages (e.g., Team's shoutouts, Team's threads, etc.)
- Low-impact or deadline-free communications
- Ping reminders without context or attachments
```

Combine this with the high-priority instruction to give Copilot the full picture of what should float to the top versus what can wait.

> [!TIP]
> Consider any out-of-scope responsibilities to include as low-priority signals. For example, a software engineer might deprioritize messages about marketing campaigns, while a sales manager could push down internal IT notifications.
