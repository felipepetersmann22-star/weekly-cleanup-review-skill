---
name: weekly-cleanup-review
description: Review a multi-assistant setup for inactive work, duplicate workflows and avoidable recurring usage. Use for an on-demand review or a user-requested recurring review, with proposals and explicit action boundaries.
license: MIT
---

# Weekly cleanup review

Produce a useful, evidence-based review of the specified setup. Weekly is a possible cadence, not a default to create. Follow the user's scope, preferences and existing platform tools. An audit is read-only unless the requested work or prior authorization permits changes.

## 1. Establish the review

Identify the authorized assistants, sources, available usage report, relevant time period, retention expectations, output destination and intended cadence. Check for an existing workflow before proposing a new routine. For a requested recurring run, determine the time zone and timing from the user's actual needs; do not assume weekdays or mornings. Note inaccessible sources and never claim a complete inventory from partial access.

## 2. Inspect and classify

- Read the previous report and incremental changes where available. If no reliable baseline exists, review the available scope and mark the coverage limit.
- Use actual usage data to prioritize, if accessible. Avoid estimating token or cost savings from activity counts alone.
- For each assistant or chat, distinguish **active or awaiting input**, **idle**, and **unknown**. Skip active or uncertain work rather than interrupting it. For idle work, identify whether a handover, file organization or memory correction would help; do not carry those out merely because an item is idle.
- Identify similar skills and routines, but compare their audiences, permissions, timing, failure behavior and purpose before proposing a merge.

## 3. Prepare changes only within scope

For a proposed cleanup, record the exact target, intended result, trade-off and any authorized action. Preserve active work and useful history. Backup, memory edits, archive moves, deletion, new schedules, disabling routines and messaging are separate actions; perform them only when the user's request and the platform's rules authorize them. Do not send a report to other people without explicit authorization.

If an authorized backup is needed, confirm the destination and retention policy, avoid overwriting existing backups, and avoid exposing secrets or copying them to an inappropriate location. Record what was actually captured and whether consistency could be checked. Never label a proposal as a completed backup or change.

Optional companions: use `clean-and-compact`, `reuse-before-research`, `frugal-routines` or `usage-saving` when installed and applicable. Otherwise perform the bounded review above and report the missing capability; they are not required dependencies.

## 4. Report

Use [the report template](assets/cleanup-report.md) when helpful. Distinguish observations, actions actually completed, skipped or inaccessible work, and proposed changes with evidence and trade-offs. Give up to three highest-impact recommendations unless the user requests a different scope. Describe real activity counts and unverified estimates separately. Deliver in the requested location; say when a backup, schedule or external notification has not been performed.

## Example

One assistant is awaiting a deployment decision; another has been idle and has an outdated handover. A review lists the first as active and proposes updating the second's handover. It does not stop the deployment, edit memory, move files, schedule a review or message someone else unless separately authorized.
