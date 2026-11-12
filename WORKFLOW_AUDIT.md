# Workflow Audit

This page documents how branches, pull requests, issues, and close-out fit together in a tidy GitHub workflow.

## Overview

A healthy repository lifecycle looks like this:

1. **Branch** — Start work on a dedicated branch (e.g. `feature/audit-notes`) instead of the default branch.
2. **Commit** — Make small, focused commits with clear messages (e.g. "Add audit documentation").
3. **Pull Request** — Open a PR from your feature branch into the default branch (e.g. `main`) to propose and discuss the changes.
4. **Issue** — Track larger tasks and Follow-ups as issues; attach follow-ups as sub-issues of the main checklist issue.
5. **Review** — Request a review, discuss comments on the diff, and resolve outstanding feedback.
6. **Close-out** — Once the PR is approved and tests pass, merge it. Then mark the parent issue as completed while keeping any open follow-up issues open.

## Branch, Pull Request, Issue, and Close-out Fit Together

- **Branches** isolate work so the default branch stays stable.
- **Pull Requests** are the conversation layer: they link the branch to the default branch, show a file-by-file diff, and bundle review comments in one place.
- **Issues** track tasks, epics, and follow-ups. A checklist issue can have sub-issues so progress is granular and traceable.
- **Close-out** happens when the PR is merged and the checklist issue is closed as completed, leaving follow-up issues open for later work.

## Owner

| Field | Value |
| --- | --- |
| Login | HeziLiu |
| Display name | Hezi Liu |
| Bio | treat me like a tree |
| Location | Beijing/Guiyang |
| Company | BUPT/GZU |
| Profile URL | https://github.com/HeziLiu |
| Email | tackic@icloud.com |
| Account created | 2017-05-22 |
| Public repos | 4 |
| Followers / Following | 6 / 5 |

## Demo Repository

- Repository: https://github.com/mcpmark-eval-liuhezi/github-workflow-demo (public)
- Working branch: `feature/audit-notes`
- Pull request title: "Add workflow audit notes" (open, not merged)
- Checklist issue: "Demo: workflow checklist" (closed as completed)
- Follow-up issue: attached as a sub-issue under the checklist
