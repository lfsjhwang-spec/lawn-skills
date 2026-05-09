아래 전체 복사해서 붙여넣으세요!

---

# daily-work-log

A Claude skill that turns your daily work summary into a structured log.

---

## What it does

Tell Claude what you did today — or paste your chat history — and it will:

- Classify each task by type (meeting, dev, docs, content, education, etc.)
- Track status: done, in progress, blocked, or carry-over
- Generate a clean log in the format you need (quick memo, report, or markdown)
- Add a one-line insight when patterns are detected — too many meetings, unresolved blockers, more incomplete than complete

---

## Example

**Input:**

Had a KPI meeting this morning and got feedback on the survey. Edited a video for the sales team. Had an automation meeting in the afternoon, still organizing interview notes. Need to wrap up the company-wide interview data tomorrow.

**Output:**

May 9, 2026 — Work Log

Done
- KPI meeting [meeting]
- Survey feedback review [review]
- Video editing (Sales Team) [content]
- Automation meeting [meeting]

In Progress
- Organizing interview notes [research]

Tomorrow
- Compile company-wide interview data

Summary: Heavy on meetings today — interview data wrap-up carries into tomorrow.

Insight: Meeting load was over 50% today. Consider blocking focus time tomorrow.

---

## How to use

Talk to Claude at the end of the day:

Make a work log for today. [Tell Claude what you did]

Or paste a conversation:

Here's my Claude conversation from today. Make a work log from this. [Paste conversation]

Output format options:

| Say this | Format |
|----------|--------|
| (nothing) | Quick memo |
| "make it a report" | Report style |
| "for Notion" | Markdown |
| "weekly log" | Weekly summary |

---

## Installation

1. Copy the contents of SKILL.md
2. Paste into your Claude project instructions
3. Start logging

---

## File structure

daily-work-log/
├── SKILL.md
└── references/
    └── how-to-use.md

---

## Why I built this

I kept forgetting what I actually did each day. This skill lets me just talk to Claude at the end of the day and get a clean log — without thinking about format or structure.

---

Built with Claude by Anthropic. Developed as part of an AI education course project, May 2026.
