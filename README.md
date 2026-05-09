daily-work-log
A Claude skill that turns your daily work summary into a structured log.

What it does
Tell Claude what you did today — or paste your chat history — and it will:

Classify each task by type (meeting, dev, docs, content, education, etc.)
Track status: done, in progress, blocked, or carry-over
Generate a clean log in the format you need (quick memo, report, or markdown)
Add a one-line insight when patterns are detected — too many meetings, unresolved blockers, more incomplete than complete


Example
Input:
Had a planning meeting in the morning. Reviewed some documents and sent a few emails in the afternoon. Started working on a report but didn't finish. Need to follow up with the team tomorrow.
Output:
May 9, 2026 — Work Log
Done

Planning meeting [meeting]
Document review [review]
Email responses [communication]

In Progress

Report writing [docs]

Tomorrow

Follow up with the team

Summary: Meetings and communication heavy day — report carries into tomorrow.
Insight: More tasks incomplete than complete today. What's the one thing to finish first tomorrow?

How to use
Talk to Claude at the end of the day:
Make a work log for today. [Tell Claude what you did]
Or paste a conversation:
Here's my Claude conversation from today. Make a work log from this. [Paste conversation]
Output format options:
Say thisFormat(nothing)Quick memo"make it a report"Report style"for Notion"Markdown"weekly log"Weekly summary

Installation

Copy the contents of SKILL.md
Paste into your Claude project instructions
Start logging


File structure
daily-work-log/
├── SKILL.md
└── references/
└── how-to-use.md

Why I built this
I kept forgetting what I actually did each day. This skill lets me just talk to Claude at the end of the day and get a clean log — without thinking about format or structure.

Created in May 2026.Sonnet 4.6Claude
