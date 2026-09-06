# ChatGPT–Codex Bridge

[Portfolio](../README.md) · [Project map](../PROJECT_MAP.md)

Source repository identifier: `yo20ywork-max/chatgpt-codex-bridge`.

## Problem

A coding task can span multiple execution loops and interruptions. The bridge provides a way to track a mission, record validation, and resume after a pause.

## My implementation work

Development of a local integration tool connecting a ChatGPT-facing MCP interface to Codex CLI execution and mission state.

## Technical scope

- TypeScript/Node.js implementation of an MCP-facing bridge.
- Mission state, event records, reports, and checkpoint/resume behavior.
- Mock scenarios and separately documented real CLI checks.
- Explicit boundaries for repository changes and validation reporting.

## Evidence and current scope

[Public source](https://github.com/yo20ywork-max/chatgpt-codex-bridge), including its verification matrix and transcripts. The repository records mock and real CLI verification, while the full ChatGPT Web-to-real-Codex end-to-end mission remains unverified in that matrix.

## Relationship to other work

A standalone integration tool. It is distinct from the DanielDoWork AI infrastructure bridge.

## Engineering perspective

Reliable orchestration needs explicit paused, blocked, failed, and completed states. A changed-file check is not an operating-system sandbox, and mock success is not live end-to-end evidence.

For the public/private boundary, see [Public Disclosure Scope](../DISCLOSURE.md).
