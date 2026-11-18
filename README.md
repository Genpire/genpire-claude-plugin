# Genpire for Claude

Genpire is a product design studio. This plugin connects Claude to your Genpire account, so you can design products
from a chat: create a product from a description or a product idea, change or redraw it, compare three options and keep
one, restyle it in your brand style, make a size guide, specs or a full tech pack, try colours and find the nearest
Pantone codes, make moodboards, factory print files and Studio images, write a sales description, and prepare a factory
quote request. Everything you make is saved in your own Genpire account.

## What is inside

- **Genpire connector** (`.mcp.json`): the remote Genpire server at `https://mcp.genpire.com/mcp`. You sign in with your
  Genpire account (OAuth); nothing is stored in this plugin.
- **Skill** `design-with-genpire`: tells Claude when and how to use the Genpire tools.

## Install

- **Claude (web and desktop):** Customize › Plugins › Add, then find Genpire, or upload this folder as a ZIP. Open the
  plugin's Connectors tab and connect Genpire.
- **Claude Code:** `/plugin marketplace add Genpire/genpire-claude-plugin` then `/plugin install genpire@genpire`, then run `/mcp`
  and sign in to Genpire.

## Plan and privacy

Genpire tools use your existing Genpire plan; usage is shown only as the percentage left. Your shipping address and
phone number stay in Genpire. Docs: https://www.genpire.com/integrations/ai-assistants · Privacy:
https://www.genpire.com/privacy · Terms: https://www.genpire.com/terms · Support: support@genpire.com

Built and powered by Genpire.
