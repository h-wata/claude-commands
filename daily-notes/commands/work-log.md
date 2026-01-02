---
description: Log work notes based on the current conversation
allowed-tools: Bash
---

Based on the conversation in this thread, create a work log entry.

## Output
Append to ~/Documents/my-obsidian/Daily/$(date +%Y-%m-%d).md

## Steps
1. Create file if it doesn't exist
2. Add timestamp heading (HH:MM format)
3. Append to end of file

## Content to include
- What was worked on in this thread
- What changes were made
- Key decisions or important points

Write the memo content in Japanese.

If $ARGUMENTS is provided, incorporate it as additional context.

Additional instructions: $ARGUMENTS
