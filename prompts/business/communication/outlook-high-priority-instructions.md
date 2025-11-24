---
title: Outlook Copilot Priority Instructions
category: business
subcategory: communication
description: Teach Outlook Copilot which messages deserve top billing so high-priority mail is surfaced automatically.
llm_tools:
  - Microsoft Outlook Copilot
inputs:
  - Role or function
  - Examples of high-priority senders
  - Types of incidents, deadlines, or keywords that require fast action
  - Signals across Teams, monitoring, or attachments that indicate urgency
tags:
  - outlook
  - copilot
  - inbox-prioritization
  - urgency-signals
---

# Outlook Copilot Priority Instructions

Outlook now lets you define custom rules so Copilot highlights the messages that matter most. Adjust and drop each of the instructions below into **Settings → Copilot → Prioritize** and tailor the placeholders to reflect your role.

> [!IMPORTANT]
> Each instruction can be added as a separate row in the Prioritize settings. These will be combined into a single instruction set that Copilot uses to rank incoming emails.

## High Priority Instructions

```text
- Messages from my manager (<MANAGER NAME/EMAIL>) or leadership (<LEADER NAMES/EMAILS>)
- Messages from key stakeholders such as <PROGRAM/ACCOUNT/BUSINESS/CUSTOMER TEAMS>
- Messages flagged as urgent/important
- Messages or meeting invites that directly asks me for a quick RSVP or response
- Messages with a time-sensitive deadline, e.g. action required by end of day
- Messages related to security or compliance, such as vulnerability disclosures or urgent policy updates
- Messages containing keywords like <LIST OF KEYWORDS>
- Messages where I am @mentioned in a thread (i.e. directly in the To: line rather than CC:)
- Messages that tie into my active projects or initiatives where a delay could cascade downstream
- Draft messages requiring my review or feedback
- Messages from teams where someone says "I sent you an email"
```

Configure these instructions once and Outlook Copilot will consistently surface the right emails at the top of your inbox.

> [!TIP]
> Consider any of your specific role responsibilities to include as high-priority signals. For example, customer success managers might want to prioritize messages from customers reporting issues, while product managers could highlight emails about upcoming launch deadlines.
