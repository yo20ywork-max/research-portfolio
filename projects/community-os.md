# Community OS — Collaboration Prototype

[Portfolio](../README.md) · [Project map](../PROJECT_MAP.md)

Source repository identifier: `yo20ywork-max/discord-2-0-app`.

## Problem

Communities need communication alongside governance, knowledge organization, and operational tools. This project explores those needs through an interactive prototype and an application starter.

## My implementation work

Product prototyping and application-architecture work spanning workspace interactions, community modules, and a backend-oriented starter.

## Technical scope

- A static TypeScript workspace prototype with browser-local state.
- A pnpm/Turborepo starter using Fastify, Prisma/PostgreSQL, Socket.IO, and Next.js.
- LiveKit integration scaffolding and a Tauri desktop shell.
- Product scope, roadmap, and local end-to-end test documentation.

## Evidence and current scope

The source README identifies the root application as a frontend prototype and the nested monorepo as an MVP starter. UI controls do not establish that the corresponding production services are complete. The project is independent and is not an official Discord product.

## Relationship to other work

The prototype and starter are two development surfaces within one repository and one product exploration.

## Engineering perspective

The main design challenge is turning a broad interface concept into a bounded implementation plan, with clear distinctions between simulated behavior, scaffolding, and integrated functionality.

For the public/private boundary, see [Public Disclosure Scope](../DISCLOSURE.md).
