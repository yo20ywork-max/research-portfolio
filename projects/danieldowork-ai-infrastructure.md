# DanielDoWork — AI Infrastructure

[Portfolio](../README.md) · [Project map](../PROJECT_MAP.md)

Source repository identifier: `yo20ywork-max/danieldowork-ai`.

## Problem

An AI feature needs more than a chat interface: model access, routing, service health, memory integration, and a reliable way to deliver work to an execution environment.

## My implementation work

Development and integration of the AI service stack supporting DanielDoWork, including the bridge, local model routing, worker execution, and development tooling.

## Technical scope

- Python/FastAPI bridge services and model-routing integration.
- LiteLLM, Ollama, OpenClaw, and a browser-based WebLLM frontend in the development stack.
- Local worker modes for deterministic tests and separately configured live integrations.
- Container-based development and operational setup documentation.

## Evidence and current scope

The implementation includes local development instructions and integration documentation. Provider availability, hardware requirements, and end-to-end behavior depend on the selected configuration; the project is not presented as cost-free or continuously available.

## Relationship to other work

Companion infrastructure for DanielDoWork — AI Workspace, with a distinct service lifecycle. The two repositories represent different technical layers of the same product.

## Engineering perspective

Routing and fallback logic need observable states and realistic failure handling. A successful isolated worker test should be distinguished from a successful full application workflow.

For the public/private boundary, see [Public Disclosure Scope](../DISCLOSURE.md).

## Public material

[Browse the public presentation](https://github.com/yo20ywork-max/danieldowork-ai-showcase). It contains the reviewed material for this contribution, with the publication scope identified. The operational source and private history remain separate.

## Browser-conversation planning and execution

DanielDoWork's core concept describes executable capabilities in natural language, uses GPT/Claude/Gemini web conversations to interpret a user's goal, and turns structured responses into trackable tasks for a configured execution runtime. OpenClaw and browser/DOM components provide execution paths, with results returned to the conversation and task state.

The [expanded README](https://github.com/yo20ywork-max/danieldowork-ai-showcase) explains the intended loop, the actual response protocol, queue and event handling, deployment boundaries, and which integration claims still require full-system validation. The task-list vision and existing one-action response protocol are identified separately.
