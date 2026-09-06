# FocusOYL — Local AI Translator & Agent

[Portfolio](../README.md) · [Project map](../PROJECT_MAP.md)

Source repository identifier: `2ykrrmyscg-del/FocusOYL`.

## Problem

Local language tools need usable desktop interaction, constrained execution, and honest evaluation of model behavior.

## My implementation work

Development of a Windows resident translator and a separate cross-platform agent track, including local model integration, native interfaces, packaging, and validation documentation.

## Technical scope

- Windows x64 translation using HY-MT2 Q8 and summarization/generation using Gemma 4 E2B Mobile.
- A separate Rust agent/tool core with native application bindings.
- Android, macOS, Windows-agent, and iOS integration work at different delivery stages.
- Published source, release assets, model provenance, and third-party attribution.

## Evidence and current scope

[Public repository](https://github.com/2ykrrmyscg-del/FocusOYL) and [releases](https://github.com/2ykrrmyscg-del/FocusOYL/releases). Windows Translator Beta 3 still has semantic limitations. The agent's recorded real-model fixed-fixture result is 3/6; packaging success does not supersede that result. Android physical-device acceptance and Mac notarization are separate outstanding items in the documented release state.

## Relationship to other work

The Windows translator and MiniCPM-based agent are distinct implementation tracks within FocusOYL. Their model configurations and validation results are kept separate.

## Engineering perspective

Local execution alone does not establish semantic correctness or zero data retention. This project records model errors, host approval boundaries, platform constraints, and reproducible evaluation scope.

For the public/private boundary, see [Public Disclosure Scope](../DISCLOSURE.md).
