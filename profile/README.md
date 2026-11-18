<p align="center">
  <a href="https://nextanalytica.app"><img src="https://nextanalytica.app/icon-512.png" width="96" alt="nextanalytica.app logo"></a>
</p>

<h1 align="center">nextanalytica.app</h1>

<p align="center"><b>Web analytics your AI agent reads over MCP.</b><br>
One tag on your site. Then ask Claude, Cursor or Codex what changed and what to fix.</p>

<p align="center">
  <a href="https://nextanalytica.app">Website</a> ·
  <a href="https://nextanalytica.app/docs">Docs</a> ·
  <a href="https://nextanalytica.app/mcp">MCP server</a> ·
  <a href="https://nextanalytica.app/llms.txt">llms.txt</a>
</p>

## What it is

nextanalytica.app is headless web analytics. Instead of a dashboard you open, your own agent reads the numbers over the
Model Context Protocol and answers in chat.

- **Visits, pages, sources and channels**, with people who arrive from ChatGPT, Perplexity and Claude as their own channel
- **Trends, funnels, retention and paths** from one `query` tool
- **Search Console, Google Analytics 4, ChatGPT Ads and Odoo** next to the visits, read only
- **Cookieless** by default, and each person signs in with OAuth, no shared keys

## Connect your agent

```sh
claude mcp add --transport http nextanalytica https://mcp.nextanalytica.app/mcp
```

Then `/mcp` in Claude Code to sign in. In the Claude app: Settings, Connectors, Add custom connector.
Listed in the official MCP Registry as `app.nextanalytica/mcp`.

## Add the tag

```sh
npm install @nextanalytica/tag
```

Works with Next.js, React, Vue, Nuxt, SvelteKit, Astro and Gatsby. Source: [nextanalytica-tag](https://github.com/nextanalytica-app/nextanalytica-tag).

---

<sub>nextanalytica.app is not affiliated with Next Analytica (nextanalytica.io).</sub>
