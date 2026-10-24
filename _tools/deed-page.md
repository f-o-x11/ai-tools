---
name: deed.page
slug: deed-page
website: https://deed.page
description: Static hosting built for coding agents. An agent publishes an HTML file or folder with one HTTP PUT or MCP call and gets a public HTTPS link.
categories:
  - agents
  - coding
use_cases:
  - development
  - automation
modalities:
  - code
pricing: freemium
api: true
self_hosted: false
features:
  - Publish a file or folder with one HTTP PUT or `curl -T`, no account needed to start
  - Hosted remote MCP server at https://deed.page/mcp
  - MIT-licensed agent skill for SKILL.md agents such as Claude Code, Codex and Cursor
  - OpenAPI spec and llms.txt for agents that read docs directly
---
deed.page gives coding agents a place to put the HTML they generate. A report, prototype, dashboard or landing page goes up with a single request, and the agent hands back a permanent `https://<slug>.deed.page/` link that anyone can open.

The same owner token returned on the first publish lets the agent update, version, password-protect or delete the site later. A free plan covers small sites; paid plans add more room. Docs are at https://deed.page/docs and the agent skill lives at https://github.com/f-o-x11/deed-page-skill.
