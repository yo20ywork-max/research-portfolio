# DanielDoWork — AI Workspace

[Portfolio](../README.md) · [Project map](../PROJECT_MAP.md)

Source repository identifier: `yo20ywork-max/danieldowork-web`.

## Personal investment

DanielDoWork is my first major software project and the project into which I have put the most personal effort and self-funded development. The web application and companion AI infrastructure are presented together as the core of that work.

## Problem

Marketing and project work can become fragmented across spreadsheets, conversations, and AI tools. DanielDoWork brings project records, workspace interactions, and AI-assisted tasks into a web application.

## My implementation work

Application development and integration across project workflows, workspace data, messaging, and AI execution. The work also includes device-connection and deployment configuration.

## Technical scope

- A Next.js and TypeScript application backed by Supabase.
- Workspace and project interfaces, structured records, imports, and messaging integrations.
- Personal-compute integration connecting the web product to user-owned execution services.
- Supporting browser-extension and desktop-connection work.

## Evidence and current scope

[Product website](https://www.danieldowork.com). The source repository contains implementation and release documentation. A release candidate in source control is not, by itself, evidence of the deployed website version.

## Relationship to other work

This is the main application repository. The separate DanielDoWork AI Infrastructure case covers companion services. Changes to those services and changes to the deployed web application have separate delivery paths.

## Engineering perspective

Web UI, application state, external services, and local compute need explicit boundaries. This project made deployment source tracking and integration diagnosis a practical part of product development.

For the public/private boundary, see [Public Disclosure Scope](../DISCLOSURE.md).

## Public material

[Browse the public presentation](https://github.com/yo20ywork-max/danieldowork-showcase). It contains the reviewed material for this contribution, with the publication scope identified. The operational source and private history remain separate.

## Product logic and architecture

DanielDoWork's core concept describes executable capabilities in natural language, uses GPT/Claude/Gemini web conversations to interpret a user's goal, and turns structured responses into trackable tasks for a configured execution runtime. OpenClaw and browser/DOM components provide execution paths, with results returned to the conversation and task state.

The [expanded README](https://github.com/yo20ywork-max/danieldowork-showcase) explains the intended loop, the actual response protocol, queue and event handling, deployment boundaries, and which integration claims still require full-system validation. The task-list vision and existing one-action response protocol are identified separately.
