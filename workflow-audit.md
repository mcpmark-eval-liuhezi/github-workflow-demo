# Workflow Audit

This page documents how branch, pull request, issue, and close-out fit together in a tidy GitHub workflow.

## Overview

A healthy repo pairs **issues** (what to do), **branches** (where to do it), **pull requests** (how to propose it), and **sub-issues** (how to break big tasks into trackable pieces). Everything converges in a **close-out** step: the PR is left open for review, tracked issues are commented on and closed as completed, and follow-ups are attached as sub-issues so nothing is lost.

## 1. Branch

Before any work lands on `main`, create a dedicated branch such as `feature/audit-notes`. Branches isolate experimental or incremental work so the default branch stays stable and reviewable at all times.

## 2. Pull Request

Open a pull request from the feature branch into the default branch (e.g. `main`). The PR is where review happens: reviewers read the diff, leave comments on specific lines, and either approve, request changes, or comment. Keeping the PR open (unmerged) during review demonstrates the real back-and-forth of协作.

## 3. Issue

Use issues for task tracking and discussion. A checklist issue can reference the PR, and smaller follow-up items can be attached as **sub-issues** so they stay linked to the parent task.

## 4. Close-Out

Close-out means: post a summary comment on the issue (e.g. “Checklist complete, closing this out”), mark the parent issue as **completed**, and keep any follow-up sub-issues open until they are separately resolved. This leaves an audit trail of what was done and what remains.

## Owner

- **Login:** HeziLiu
- **Display name:** Hezi Liu
- **Bio:** treat me like a tree
- **Location:** Beijing/Guiyang
- **Company:** BUPT/GZU
- **Email:** tackic@icloud.com
- **Profile:** https://github.com/HeziLiu
- **User ID:** 28861483
- **Account created:** 2017-05-22
- **Public repos:** 4 | **Followers:** 6 | **Following:** 5
