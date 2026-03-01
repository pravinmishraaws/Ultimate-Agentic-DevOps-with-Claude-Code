---
name: commit
description: Commit code to GitHub with an AI-generated summary of changes
allowed-tools: Bash
disable-model-invocation: true
---

Commit the changes completed in this session to the GitHub repo.

Steps:
- [ ] Run `git diff --staged` and `git status` to understand what changed
- [ ] Add all changes: `git add .`
- [ ] Write a concise commit message in imperative tense summarizing the changes
- [ ] Commit: `git commit -m "<your message>"`
- [ ] Push: `git push origin main`

If any step fails, stop and report the error. Do not continue to the next step.