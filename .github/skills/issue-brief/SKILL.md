---
name: issue-brief
description: >-
  Write a three-part brief of a single GitHub issue. Use when asked to brief,
  summarize, or explain one issue in a GitHub repository.
disable-model-invocation: false
---

# Issue brief

Brief exactly one GitHub issue.

1. If the user did not give an owner, a repository, and an issue number, ask for them before calling any tool.
2. Read the issue through the configured GitHub MCP server. Do not invent the title, body, or labels.
3. Reply with these three headings and no others. Put one sentence under each heading.

## What is wrong

## Why it matters

## Next check

4. Do not create or edit files.