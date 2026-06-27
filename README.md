# Clueso MCP

> Make on-brand videos with your AI agent.

Clueso's MCP connects AI agents like **Claude, ChatGPT, and Gemini** to a complete video-creation engine. Describe what you need in plain language and get polished, fully editable explainer videos and documentation — turn PRDs, support tickets, recordings, or slide decks into finished, on-brand video.

This is a **remote (hosted) MCP server**. There's nothing to install or run — connect to the hosted endpoint and authorize with your Clueso account.

- **Server URL:** `https://connect.clueso.io/mcp`
- **Transport:** Streamable HTTP
- **Auth:** OAuth 2.0 (sign in to Clueso, authorize)
- **Registry name:** `io.clueso/video`

## Connect

### Claude / Claude Code
Settings → Connectors → **Add custom connector** → paste `https://connect.clueso.io/mcp` → authorize with your Clueso account.

### ChatGPT
Settings → Connectors → add a custom connector pointing at `https://connect.clueso.io/mcp`.

### Cursor / VS Code / Gemini CLI
Add a remote MCP server with URL `https://connect.clueso.io/mcp` (Streamable HTTP). Your client walks you through the OAuth sign-in on first use.

Setup takes about two minutes — no code, no API keys.

## What your agent can do

Your agent works through ~40 tools spanning the full video workflow:

- **Find & browse** — locate workspaces, projects, clips, and reusable templates (clueprints)
- **Projects & clips** — create projects, add and edit clips, split, duplicate, reorder
- **Elements** — place text, images, shapes, and AI-generated media on the canvas
- **Voiceover & audio** — generate AI voiceovers, add and sync audio, batch-narrate
- **Auto-sync** — automatically pace narration against screen recordings
- **Articles** — write companion help-center articles alongside a video
- **Recording** — capture screen recordings
- **Files & assets** — upload and manage media
- **Clueprints** — build from and author reusable on-brand templates
- **Export** — render and export finished videos

Everything stays **on-brand** using your brand guidelines, personas, and tone of voice — and every output remains fully editable in the Clueso editor or by simply telling your agent what to change.

## Example workflows

- **Product marketing** — read a Linear ticket → produce a release video → post to Slack
- **Customer support** — turn the top support tickets into explainer videos, auto-published to your help center
- **Localization at scale** — "localize my entire video library into French and Spanish" across hundreds of videos in one instruction
- **Sales** — turn a meeting recording into a polished recap in minutes

## Links

- **Homepage:** https://www.clueso.io/mcp
- **Setup docs:** https://help.clueso.io/mcp-setup
- **Privacy policy:** https://www.clueso.io/legal/privacy
- **Terms:** https://www.clueso.io/legal/terms

## For maintainers

This repo is the public anchor for Clueso's MCP listing across registries. The canonical metadata lives in [`server.json`](./server.json), published to the [official MCP Registry](https://registry.modelcontextprotocol.io) under the name `io.clueso/video` via DNS-authenticated publishing from the `clueso.io` domain.
