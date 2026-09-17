# Wildberries MCP и Ozon MCP — интеграции хоста Agenova

[English](README.md) · [Русский](README.ru.md)

**Wildberries MCP**, **Ozon MCP** и **Bitrix24 MCP** — это hosted-инструменты Model Context Protocol внутри агента Agenova. Подключение — на [agenova.ru](https://agenova.ru). Этот репозиторий ([`github.com/badygov/agenova-integrations`](https://github.com/badygov/agenova-integrations)) только документация: нет исходников серверов, нет `npx` / `uvx`, публичного `mcp.agenova.ru` пока нет.

Это не локальный stdio Wildberries MCP для Cursor через `npx`. Не [polluxchou/agenova.chat](https://github.com/polluxchou/agenova.chat) и не R-пакет [statisfactions/genova](https://github.com/statisfactions/genova). В official MCP Registry `server.json` нужен живой remote URL — фейк не публикуем.

Agenova — размещённый AI-агент для кабинетов селлера и CRM. Интеграции включаются в кабинете, задача — в чате.

## Как подключить

1. Откройте [agenova.ru](https://agenova.ru) и зайдите в размещённого агента.
2. В кабинете подключите нужные сервисы (токен продавца или OAuth — как спросит продукт).
3. Сформулируйте задачу в чате (карточка, сборка FBS, отзыв, сделка).

Живые страницы: [agenova.ru/integrations](https://agenova.ru/integrations/).

## Hosted MCP (семь в hero)

Это представительный набор, не официальное партнёрство с Wildberries, Ozon или Битрикс24.

| Как ищут | Что делает агент на хосте | Страница |
|---|---|---|
| Wildberries MCP — карточки | Находит карточку, сверяет поля категории, готовит цены и атрибуты | [wb-catalog](https://agenova.ru/integrations/wb-catalog/) |
| Wildberries MCP — FBS | Показывает сборочные задания и готовит поставку к сверке с коробами | [wb-fbs](https://agenova.ru/integrations/wb-fbs/) |
| Wildberries MCP — отзывы | Собирает неотвеченные отзывы и готовит ответ от имени магазина | [wb-comms](https://agenova.ru/integrations/wb-comms/) |
| Ozon MCP — товары | Заводит и обновляет товары, цены и фото | [ozon-catalog](https://agenova.ru/integrations/ozon-catalog/) |
| Ozon MCP — FBS | Показывает горящие отправления и готовит обновление остатков | [ozon-fbs](https://agenova.ru/integrations/ozon-fbs/) |
| Ozon MCP — отзывы | Читает отзывы и переписку Seller и готовит ответы | [ozon-comms](https://agenova.ru/integrations/ozon-comms/) |
| Bitrix24 MCP — CRM | Находит сделку, стадию воронки и KPI; готовит правку записи по просьбе | [bitrix-crm](https://agenova.ru/integrations/bitrix-crm/) |

Отправка: по команде в чате агент умеет отправить. Отдельного экрана подтверждения нет. Уже отправленное следующим сообщением не отозвать.

## Ещё на хосте

Тот же кабинет, не второй продукт. Личные сессии Telegram/WhatsApp здесь не перечисляем.

| Работа | Что делает агент на хосте | Страница |
|---|---|---|
| Яндекс Директ | Кампании, объявления и ставки из чата | [yandex-direct](https://agenova.ru/integrations/yandex-direct/) |
| Яндекс Метрика | Счётчики и отчёты в одном запросе | [yandex-metrica](https://agenova.ru/integrations/yandex-metrica/) |
| VK Реклама | Кампании, объявления и статистика | [vk-ads](https://agenova.ru/integrations/vk-ads/) |
| Telegram-бот | Входящие сообщения бота и ответы | [telegram-bot](https://agenova.ru/integrations/telegram-bot/) |

Остальной живой каталог — на [agenova.ru/integrations](https://agenova.ru/integrations/). Слово MCP в Title/H1 витрины **не** ставим — здесь, для поиска из IDE.

## Чем этот репозиторий не является

- Не локальный MCP-сервер для Cursor, Claude Desktop или Smithery (`npx` / `uvx`).
- Не исходный код Agenova (`badygov/MCP`).
- Не заявка в official MCP Registry, пока нет публичного remote с OAuth.
- Не поддержка клиентов. Операционные обращения не через GitHub Issues (Issues выключены).

## Товарные знаки

Wildberries, Ozon, Битрикс24 и другие названия — знаки правообладателей. Упоминание не означает одобрения, сертификации, спонсорства или партнёрства.

## Лицензия и безопасность

Документация в этом репозитории — [CC BY 4.0](LICENSE). Лицензия не даёт прав на товарные знаки Agenova и третьих лиц и не лицензирует хост или исходники серверов.

Как сообщить о подозрении на уязвимость: [SECURITY.md](SECURITY.md).
