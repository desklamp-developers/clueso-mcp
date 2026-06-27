<p align="center">
  <img src="assets/clueso-logo.png" alt="Clueso" width="88" height="88" />
</p>

# Clueso MCP

> Make videos and docs with ChatGPT, Claude, and Gemini.

Clueso's MCP connects your favorite AI agents to a video creation engine.
Just describe what you need — and every output stays fully editable, by you or AI.

No scripting, no API keys to manage, no terminal commands. This is a remote
(hosted) MCP server: connect to the endpoint, authorize with your Clueso
account, and start creating in about two minutes.

- **Server URL:** `https://connect.clueso.io/mcp`
- **Transport:** Streamable HTTP
- **Auth:** OAuth 2.0 (sign in to Clueso)
- **Registry name:** `io.clueso/video`

## Connect your MCP

Works with **Claude, ChatGPT, Gemini, Cursor — or any MCP client.**

- **Claude / Claude Code:** Settings → Connectors → Add custom connector →
  `https://connect.clueso.io/mcp` → authorize.
- **ChatGPT / Cursor / any other MCP client:** add a custom connector pointing
  at the same URL; your client walks you through the OAuth sign-in.

Full setup guide: https://help.clueso.io/mcp-setup

## What you can make

Create videos through conversation — product walkthroughs, feature
announcements, tutorials, sales demos, training content, and customer
onboarding videos. Your agent applies your brand guidelines automatically,
so everything stays on-brand.

## Edit anything, just by asking

Edit existing videos the same way — swapping assets, updating text, changing
branding, trimming clips, adjusting transitions, and rearranging sections.
Manage your entire library, all through conversation.

## Example workflows

- Read a Linear ticket → produce a release video → post it to Slack
- Turn your top support tickets into explainer videos, auto-published to your help center
- "Localize my entire video library into French and Spanish" — in one instruction
- Turn a meeting recording into a polished recap in minutes

## Links

- Homepage: https://www.clueso.io/mcp
- Setup: https://help.clueso.io/mcp-setup
- Privacy: https://www.clueso.io/legal/privacy
- Terms: https://www.clueso.io/legal/terms

## For maintainers

Public anchor for Clueso's MCP listing across registries. Canonical metadata
lives in [`server.json`](./server.json), published to the
[official MCP Registry](https://registry.modelcontextprotocol.io) as
`io.clueso/video` via DNS-authenticated publishing from the `clueso.io` domain.
