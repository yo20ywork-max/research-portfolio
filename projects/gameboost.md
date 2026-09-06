# GameBoost — Network Route Evaluation & Tunnel Prototype

[Public source](https://github.com/yo20ywork-max/gameboost) · [Test evidence](https://github.com/yo20ywork-max/gameboost/blob/main/VALIDATION.md)

## Problem and approach

A nearby network node does not necessarily offer the best route to a game endpoint. GameBoost explores using available client-to-node and node-to-endpoint measurements to compare candidate routes and provide a desktop connection workflow.

## Implementation scope

The project contains three cooperating components: a FastAPI backend with SQLite, a PySide6 Windows client, and a Linux WireGuard node agent. Source includes profile-based route planning, weighted node ranking, probe caching, authentication, lease management, and native tunnel-service integration.

The implementation demonstrates service boundaries, network configuration, local application packaging, and backend tests. Full IPv4 tunneling and selected destination routes are separate modes within one project.

## Evidence and limits

The public tests cover route selection, packet-loss penalties, target construction, probe evaluation, and API behavior with synthetic data and mocked agent calls. The repository validation record reports the actual test outcome.

A route score is an estimate, not a measured gameplay improvement. No published benchmark in this snapshot establishes reduced game latency, anti-cheat certification, universal game compatibility, or IPv6 protection. Promotional store mockups contain sample values and are not benchmark evidence.

## Publication boundary

The source snapshot includes explicit demo accounts and placeholder deployment secrets for local development. The demo Compose port binds to loopback. Real node deployment changes host networking and needs dedicated configuration and review; those installation scripts are not part of the automated validation run. No original credentials, runtime databases, tunnel configurations, or private signing files are included.
