---
name: ask-first
description: Use whenever a request is vague, ambiguous, or missing details. Ask all clarifying questions first, in one batch, and only start building after every ambiguity is resolved.
---

# Ask First, Build Later

## Core rule
Do not write code, create files, or run commands while any part of the request is unclear. Wasting context on wrong guesses is worse than asking.

## Step 1: Check for ambiguity
Before doing anything, silently check whether these are clear:
- The exact goal and what "done" looks like
- Platform, language, framework, and versions
- Target users and key features
- Inputs, outputs, and edge cases
- Design, style, and language of the UI
- Existing code or files that must be respected
- Limits: time, performance, security, budget

## Step 2: Ask everything in one batch
- If anything is unclear, ask ALL questions at once in a single numbered list.
- Keep questions short, specific, and easy to answer. Offer options (A / B / C) when possible.
- Do not ask about things that can be safely inferred from the project or earlier messages.
- Do not start building while waiting for answers.

## Step 3: Repeat until clear
- After the user answers, check again. If new ambiguity appears, ask one more short batch.
- Never assume silently. If you must assume something small, state it clearly and ask for confirmation.

## Step 4: Confirm, then build
- When no ambiguity is left, write a 3 to 5 line summary of what you will build.
- Wait for the user's approval, then start building.
- If the user says "just do it" or "no more questions", state your assumptions in one short list and proceed.

## Keep it cheap
- Do not scan the whole repository just to ask questions.
- Do not write long explanations while clarifying. Questions only.
