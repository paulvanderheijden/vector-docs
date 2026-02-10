# Vector Documentation — Project Instructions

## About this project

- This is the product documentation for **Vector**, a decision- and commitment-centric operating system for leadership teams
- Built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally

## Terminology

- Use **"circle"** not "forum" in user-facing docs (internal model uses "forum")
- Use **"session"** not "meeting" (sessions are records, meetings are events)
- Use **"decision"** and **"commitment"** as the two atomic units — always
- Use **"owner"** not "assignee" or "responsible"
- Use **"taken"** not "approved" or "decided" for decision closure
- Use **"rolled"** not "overdue" or "late" for missed commitments

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for field names: `ownerPersonId`
- No emojis unless explicitly requested

## Content boundaries

- Document the product as it is designed, not internal implementation details
- Don't document database schemas or API internals
- The domain model section is the conceptual schema, not a technical spec
