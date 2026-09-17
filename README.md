# Agenova hosted integrations

[English](README.md) · [Русский](README.ru.md)

**This repository is [`github.com/badygov/agenova-integrations`](https://github.com/badygov/agenova-integrations).** Connect the hosted agent at [agenova.ru](https://agenova.ru). Documentation only: no MCP server source, broker, or production infrastructure.

Not [polluxchou/agenova.chat](https://github.com/polluxchou/agenova.chat), not the R package [statisfactions/genova](https://github.com/statisfactions/genova), and not a local Wildberries/Ozon MCP server you run with `npx` (those are other GitHub listings). There is no `npx` install and no public MCP URL here.

Agenova is a hosted AI agent for operations in seller cabinets and CRM. You authorize integrations in the Agenova cabinet.

## Connect

1. Open [agenova.ru](https://agenova.ru) and start the hosted agent.
2. In the cabinet, connect the services you use (seller token or OAuth, as the product asks).
3. Ask for the job in chat (a card, an FBS batch, a review, a deal).

Catalog of live product pages: [agenova.ru/integrations](https://agenova.ru/integrations/).

## Hero integrations

These seven are representative. They are not an official partnership with Wildberries, Ozon, or Bitrix24.

| Job | What the hosted agent does | Product page |
|---|---|---|
| Wildberries product cards | Finds a card, checks category fields, prepares price and attribute updates | [wb-catalog](https://agenova.ru/integrations/wb-catalog/) |
| Wildberries FBS assembly | Shows assembly tasks and prepares a supply against boxes | [wb-fbs](https://agenova.ru/integrations/wb-fbs/) |
| Wildberries reviews and chats | Lists unanswered reviews and drafts a reply in the shop’s voice | [wb-comms](https://agenova.ru/integrations/wb-comms/) |
| Ozon product cards | Creates and updates products, prices, and photos | [ozon-catalog](https://agenova.ru/integrations/ozon-catalog/) |
| Ozon FBS | Shows hot postings and prepares stock updates | [ozon-fbs](https://agenova.ru/integrations/ozon-fbs/) |
| Ozon reviews and chats | Reads Seller reviews and chats and drafts replies | [ozon-comms](https://agenova.ru/integrations/ozon-comms/) |
| Bitrix24 CRM | Finds a deal, funnel stage, and KPIs; prepares a record update if you ask | [bitrix-crm](https://agenova.ru/integrations/bitrix-crm/) |

Writes: on request in chat the agent can send. There is no separate confirmation screen. Already sent output cannot be pulled back by the next message.

## Also on the hosted catalog

Same cabinet, not a second product. Personal Telegram/WhatsApp user sessions are not listed here.

| Job | What the hosted agent does | Product page |
|---|---|---|
| Yandex Direct | Campaigns, ads, and bids from chat | [yandex-direct](https://agenova.ru/integrations/yandex-direct/) |
| Yandex Metrica | Counters and reports in one request | [yandex-metrica](https://agenova.ru/integrations/yandex-metrica/) |
| VK Ads | Campaigns, ads, and stats | [vk-ads](https://agenova.ru/integrations/vk-ads/) |
| Telegram bot | Inbound bot messages and replies | [telegram-bot](https://agenova.ru/integrations/telegram-bot/) |

The rest of the live catalog stays on [agenova.ru/integrations](https://agenova.ru/integrations/) without the word MCP.

## What this repo is not

- Not a local MCP server for Cursor, Claude Desktop, or Smithery.
- Not the Agenova source tree.
- Not a listing on the official MCP Registry (that waits on a public OAuth remote, which is not published here).
- Not customer support. Do not file operational tickets as GitHub issues (Issues are disabled).

## Trademarks

Wildberries, Ozon, Bitrix24, and other product names are trademarks of their owners. Mention does not mean endorsement, certification, sponsorship, or partnership.

## License and security

Documentation in this repository is licensed under [CC BY 4.0](LICENSE). That license does not grant Agenova or third-party trademark rights, and it does not license any hosted service or server source.

See [SECURITY.md](SECURITY.md) for how to report a suspected issue privately.
