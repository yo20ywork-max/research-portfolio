# Development Context & Handoff

[Portfolio](../README.md) · [Project map](../PROJECT_MAP.md)

Source repository identifier: `yo20ywork-max/dev-context`.

## Problem

Work spread across repositories and computers can lose context: which repository owns a feature, what changed, and what another session should read first.

## My implementation work

Establishing a versioned handoff and project-index workflow for ongoing software development.

## Technical scope

- A small Git-backed context repository.
- Durable decisions separated from disposable local caches.
- Project ownership and repository/deployment relationship records.
- A review process for public documentation and private operational material.

## Evidence and current scope

This public case describes the engineering method. The operational memory file remains private because it contains internal configuration and development history.

## Relationship to other work

Supporting engineering infrastructure used alongside the application projects. It is represented as process work, rather than a separately shipped customer product.

## Engineering perspective

Documenting sources of truth and handoff rules helps make iterative, AI-assisted development inspectable and repeatable across sessions.

For the public/private boundary, see [Public Disclosure Scope](../DISCLOSURE.md).

## Public material

[Browse the public presentation](https://github.com/yo20ywork-max/dev-context-showcase). It contains the reviewed material for this contribution, with the publication scope identified. The operational source and private history remain separate.
