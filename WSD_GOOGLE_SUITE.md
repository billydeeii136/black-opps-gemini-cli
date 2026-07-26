# WSD Google Suite Operating Profile

**Control marker:** `WSD_GOOGLE_SUITE_NODE_PROFILE_2026-07-26`

This file extends `GEMINI.md` across the full Google AI suite while preserving the WSD single-owner Gatekeeper doctrine.

## Covered products and surfaces

- Gemini Android and web applications, Gemini Live, Deep Research, Canvas, Gems, notebooks, file and code analysis, connected applications, schedules, tasks, and skills where available.
- Google Workspace with Gemini across Gmail, Calendar, Chat, Docs, Drive, Sheets, Slides, Meet, Vids, Forms, Keep, Tasks, Workspace Studio, Gemini Notebook, and NotebookLM.
- Google AI Studio, Gemini Developer API, Gemini API, Interactions API v1, Google Gen AI SDK, realtime and multimodal endpoints, ADK, Genkit, and owner-authorized API clients.
- Vertex AI Studio, Vertex AI Agent Builder, Agent Engine, Agent Garden, and Vertex AI SDK as adapter or API lanes only. Cloudflare remains the default infrastructure target.
- Gemini Code Assist Standard and Enterprise, Gemini Code Assist agent mode, Gemini CLI where supported, Google Antigravity, Antigravity CLI, VS Code, JetBrains, Android Studio, Cloud Shell, and Cloud Workstations.

## Lifecycle controls

- Consumer Gemini Code Assist and Gemini CLI access through individual Google AI plans ended June 18, 2026; migrate those workflows to Antigravity or Antigravity CLI. Standard and Enterprise access remains separate.
- Firebase Studio is migration-only: new workspaces and signup were disabled June 22, 2026 and final sunset is scheduled for March 22, 2027. Use Google AI Studio or Google Antigravity for new long-term work.

## Node deployment

Apply this profile to A15, A16, A17-1, A17-2, A17-3, A17-4, TCL-TRACFONE-FLIP through its supported bridge, and MACBOOK-1 through MACBOOK-3.

Every WSD-controlled Google GUI, CLI, IDE, API, SDK, Workspace connector, notebook, agent, export, and automation must load the Gatekeeper profile, accept all owner-authorized raw-data categories at protected Gatekeeper intake, preserve isolated lanes, prevent uncontrolled publication, and record provider, product, surface, node, agent, model, connector, API or command in provenance.
