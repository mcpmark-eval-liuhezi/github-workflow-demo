# Workflow Audit

This page explains how the four core pieces of a tidy GitHub workflow —
**branch**, **pull request**, **issue**, and **close-out** — fit together.

## 1. Branch

Work starts on a short-lived, purpose-named branch (for example
`feature/audit-notes`) cut from the default branch. Keeping each branch focused
on one idea keeps the eventual diff small, reviewable, and easy to reason about.
Nobody commits directly to the default branch.

## 2. Pull Request

The pull request is the review gate. It opens a conversation around the diff,
runs checks, and lets reviewers request changes or approve. The PR references
the issue it resolves (e.g. `Closes #1`) so the two stay linked and searchable.

## 3. Issue

The issue is the unit of intent: *what* needs to happen and *why*. A small
follow-up can be attached as a sub-issue so related work stays tracked without
derailing the main task. Discussion and decisions live on the issue thread.

## 4. Close-out

Close-out is the wrap-up: post a final comment summarizing the outcome, close
the completed issue (and only that one), and leave follow-ups open so nothing
falls off the radar. Merging the PR and closing the referenced issue complete
the loop.

## Owner

- **Login:** HeziLiu
- **Display name:** Hezi Liu
- **Bio:** treat me like a tree
- **Location:** Beijing/Guiyang
- **Company:** BUPT/GZU
