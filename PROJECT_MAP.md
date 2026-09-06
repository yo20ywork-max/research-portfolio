# Repository and Product Relationships

This map preserves every source repository in the portfolio while explaining shared product history.

| Source repository identifier | Display name | Relationship |
|---|---|---|
| `yo20ywork-max/overpower` | DanielDoWork — AI Workspace | Main product application |
| `yo20ywork-max/danieldowork-ai` | DanielDoWork — AI Infrastructure | AI services integrated with the workspace application |
| `millenniume/millennium-social-os` | CrossGen — Social & Workflow Platform | Company-maintained CrossGen product line |
| `yo20ywork-max/millennium-social-os-stage00-ci` | CrossGen — Architecture & CI | Related engineering branch of the CrossGen codebase |
| `yo20ywork-max/discord-2-0-app` | Community OS — Collaboration Prototype | Static prototype plus a separate application starter |
| `yo20ywork-max/tqcpb-official-site` | Tianqing — Professional Services Website | Client website |
| `millenniume/millennium-cms-line-ai-v4` | Millennium — CMS & Customer Service | Company-maintained CMS repository |
| `yo20ywork-max/millennium-cms-line-ai-v4` | Millennium — CMS Development Line | Related earlier development repository |
| `yo20ywork-max/gpt-codex-web-bridge` | ChatGPT–Codex Bridge | Standalone public integration tool |
| `yo20ywork-max/shared-context` | Development Context & Handoff | Shared engineering context |
| `2ykrrmyscg-del/FocusOYL` | FocusOYL — Local AI Translator & Agent | Windows translator and a distinct cross-platform agent track |

## Product relationships

- DanielDoWork's web application and AI infrastructure run as distinct components. Updating the infrastructure repository alone does not update the web application's deployed frontend.
- The two CrossGen repositories share history and contain different engineering work. Architecture and CI work is presented as a contribution to CrossGen.
- The two Millennium CMS repositories belong to the same product lineage. Their separate case studies show implementation and maintenance context.
- FocusOYL's Windows translator and MiniCPM-based agent use different model/runtime paths. Their validation results are not interchangeable.

Display names improve navigation without changing repository URLs or deployment bindings.
