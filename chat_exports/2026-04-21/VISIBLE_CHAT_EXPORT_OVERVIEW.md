# Visible Chat Export Overview

This folder contains an export of the **visible and recoverable** content from the current ChatGPT conversation about the GDRF project.

## Important limitation
This is **not a guaranteed byte-perfect full transcript of the entire chat history**.

Why:
- The active session view includes many `Skipped` sections.
- Those skipped sections are not accessible verbatim from the current tool context.
- Only the content that remains visible/recoverable in the current session context can be exported faithfully.

## What is included here
- Visible user request trail for the GDRF parameter-wave buildout
- Raw exported assistant code blocks for:
  - Wave 22 — Parameter Reputation System
  - Wave 23 — Parameter Maintenance Planner
  - Wave 24 — Parameter Contamination Tracking
  - Wave 25 — Parameter Capability Packing
- Repo/import manifests and staging notes
- GitHub connector troubleshooting trail in summary form

## What is not guaranteed here
- Hidden chain-of-thought
- Elided `Skipped` message bodies
- Any earlier messages no longer present in the visible context window

## Export labeling doctrine
- `visible_request_trail.md` = user-visible request sequence reconstructed from visible context
- `wave-XX-*.md` = raw assistant-produced code export for a wave
- `repo-import-log.md` = notes on GitHub import attempts and connector state

## Repository target
- Repo: `PayneTrain69/Gdrf`
- Export date label: `2026-04-21`
