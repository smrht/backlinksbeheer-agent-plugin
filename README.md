# Backlinksbeheer agent plugin

Read your existing Backlinksbeheer domains and backlinks, inspect stored check results, find problem links and summarize a domain. Results include the available measurement dates. This plugin reads only your own account; it does not run a new crawl, send partner messages, buy backlinks, modify records or process payments. An existing Backlinksbeheer account is required.

## Connect

Use the public MCP endpoint `https://backlinksbeheer.nl/mcp` in a client supporting Streamable HTTP and OAuth. Sign in to your existing account and review the requested permissions. No API key belongs in this repository.

The root `plugin.json` and `mcp.json` support Agent Plugins clients. The compatibility manifests support Claude Code, Grok Build and Codex. The packaged skill describes when to use each tool and how to handle permissions and confirmations.

## Data and permissions

The connection sends tool arguments to the service at `https://backlinksbeheer.nl/mcp` and returns account-scoped records to your chosen assistant. Disconnecting the OAuth connection revokes future access. Treat returned customer or backlink records as private. No local telemetry or shell hooks are bundled.

[Product](https://backlinksbeheer.nl/plugin/) · [Privacy](https://backlinksbeheer.nl/plugin/privacy/) · [Terms](https://backlinksbeheer.nl/plugin/terms/) · [Support](https://backlinksbeheer.nl/contact/)

## Source and license

Maintained by Samautomation, the operator of this service. This repository contains only the public plugin package; the hosted application and account data are separate. The package is MIT-licensed; the hosted service uses its own terms.
