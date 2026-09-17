# Wildberries MCP and Ozon MCP — hosted Agenova integrations

[English](README.md) · [Русский](README.ru.md)

**Wildberries MCP**, **Ozon MCP**, and **Bitrix24 MCP** are hosted Model Context Protocol jobs inside the Agenova agent. Connect at [agenova.ru](https://agenova.ru). This repository ([`github.com/badygov/agenova-integrations`](https://github.com/badygov/agenova-integrations)) is documentation only: no server source, no `npx` / `uvx`, no public `mcp.agenova.ru` yet.

Not a local stdio Wildberries MCP you paste into Cursor (`npx`). Not [polluxchou/agenova.chat](https://github.com/polluxchou/agenova.chat) and not the R package [statisfactions/genova](https://github.com/statisfactions/genova). Official MCP Registry `server.json` needs a live remote URL — we do not publish a fake one.

Agenova is a hosted AI agent for seller cabinets and CRM. You authorize integrations in the Agenova cabinet, then ask for the job in chat.

## Connect

1. Open [agenova.ru](https://agenova.ru) and start the hosted agent.
2. In the cabinet, connect the services you use (seller token or OAuth, as the product asks).
3. Ask for the job in chat (a card, an FBS batch, a review, a deal).

Live product pages: [agenova.ru/integrations](https://agenova.ru/integrations/).

## Hosted MCP jobs (hero)

These seven are representative. They are not an official partnership with Wildberries, Ozon, or Bitrix24.

| Search name | What the hosted agent does | Product page |
|---|---|---|
| Wildberries MCP — cards | Finds a card, checks category fields, prepares price and attribute updates | [wb-catalog](https://agenova.ru/integrations/wb-catalog/) |
| Wildberries MCP — FBS | Shows assembly tasks and prepares a supply against boxes | [wb-fbs](https://agenova.ru/integrations/wb-fbs/) |
| Wildberries MCP — reviews | Lists unanswered reviews and drafts a reply in the shop’s voice | [wb-comms](https://agenova.ru/integrations/wb-comms/) |
| Ozon MCP — cards | Creates and updates products, prices, and photos | [ozon-catalog](https://agenova.ru/integrations/ozon-catalog/) |
| Ozon MCP — FBS | Shows hot postings and prepares stock updates | [ozon-fbs](https://agenova.ru/integrations/ozon-fbs/) |
| Ozon MCP — reviews | Reads Seller reviews and chats and drafts replies | [ozon-comms](https://agenova.ru/integrations/ozon-comms/) |
| Bitrix24 MCP — CRM | Finds a deal, funnel stage, and KPIs; prepares a record update if you ask | [bitrix-crm](https://agenova.ru/integrations/bitrix-crm/) |

Writes: on request in chat the agent can send. There is no separate confirmation screen. Already sent output cannot be pulled back by the next message.

## Also on the hosted catalog

Same cabinet, not a second product. Personal Telegram/WhatsApp user sessions are not listed here.

| Job | What the hosted agent does | Product page |
|---|---|---|
| Yandex Direct | Campaigns, ads, and bids from chat | [yandex-direct](https://agenova.ru/integrations/yandex-direct/) |
| Yandex Metrica | Counters and reports in one request | [yandex-metrica](https://agenova.ru/integrations/yandex-metrica/) |
| VK Ads | Campaigns, ads, and stats | [vk-ads](https://agenova.ru/integrations/vk-ads/) |
| Telegram bot | Inbound bot messages and replies | [telegram-bot](https://agenova.ru/integrations/telegram-bot/) |

The rest of the live catalog stays on [agenova.ru/integrations](https://agenova.ru/integrations/). The marketing site does not put MCP in Title/H1 — that phrase lives here, for IDE search.

## What this repo is not

- Not a local MCP server for Cursor, Claude Desktop, or Smithery (`npx` / `uvx`).
- Not the Agenova source tree (`badygov/MCP`).
- Not a listing on the official MCP Registry until a public OAuth remote exists.
- Not customer support. Do not file operational tickets as GitHub issues (Issues are disabled).

## Trademarks

Wildberries, Ozon, Bitrix24, and other product names are trademarks of their owners. Mention does not mean endorsement, certification, sponsorship, or partnership.

## License and security

Documentation in this repository is licensed under [CC BY 4.0](LICENSE). That license does not grant Agenova or third-party trademark rights, and it does not license any hosted service or server source.

See [SECURITY.md](SECURITY.md) for how to report a suspected issue privately.
