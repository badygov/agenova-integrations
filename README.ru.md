# Agenova — интеграции хоста

[English](README.md) · [Русский](README.ru.md)

**Этот репозиторий — [`github.com/badygov/agenova-integrations`](https://github.com/badygov/agenova-integrations).** Подключение — на [agenova.ru](https://agenova.ru). Только документация: нет исходников MCP-серверов, брокера и продакшен-инфраструктуры.

Это не [polluxchou/agenova.chat](https://github.com/polluxchou/agenova.chat), не R-пакет [statisfactions/genova](https://github.com/statisfactions/genova) и не локальный MCP-сервер Wildberries/Ozon через `npx` (такие листинги — другие репозитории). Здесь нет `npx` и нет публичного MCP URL.

Agenova — размещённый AI-агент для работы в кабинетах селлера и CRM. Интеграции включаются в кабинете Agenova.

## Как подключить

1. Откройте [agenova.ru](https://agenova.ru) и зайдите в размещённого агента.
2. В кабинете подключите нужные сервисы (токен продавца или OAuth — как спросит продукт).
3. Сформулируйте задачу в чате (карточка, сборка FBS, отзыв, сделка).

Каталог живых страниц: [agenova.ru/integrations](https://agenova.ru/integrations/).

## Семь интеграций в hero

Это представительный набор, не официальное партнёрство с Wildberries, Ozon или Битрикс24.

| Работа | Что делает агент на хосте | Страница |
|---|---|---|
| Карточки Wildberries | Находит карточку, сверяет поля категории, готовит цены и атрибуты | [wb-catalog](https://agenova.ru/integrations/wb-catalog/) |
| Сборка FBS Wildberries | Показывает сборочные задания и готовит поставку к сверке с коробами | [wb-fbs](https://agenova.ru/integrations/wb-fbs/) |
| Отзывы и чаты Wildberries | Собирает неотвеченные отзывы и готовит ответ от имени магазина | [wb-comms](https://agenova.ru/integrations/wb-comms/) |
| Товары Ozon | Заводит и обновляет товары, цены и фото | [ozon-catalog](https://agenova.ru/integrations/ozon-catalog/) |
| Сборка FBS Ozon | Показывает горящие отправления и готовит обновление остатков | [ozon-fbs](https://agenova.ru/integrations/ozon-fbs/) |
| Отзывы и чаты Ozon | Читает отзывы и переписку Seller и готовит ответы | [ozon-comms](https://agenova.ru/integrations/ozon-comms/) |
| CRM Битрикс24 | Находит сделку, стадию воронки и KPI; готовит правку записи по просьбе | [bitrix-crm](https://agenova.ru/integrations/bitrix-crm/) |

Отправка: по команде в чате агент умеет отправить. Отдельного экрана подтверждения нет. Уже отправленное следующим сообщением не отозвать.

## Ещё на хосте

Тот же кабинет, не второй продукт. Личные сессии Telegram/WhatsApp здесь не перечисляем.

| Работа | Что делает агент на хосте | Страница |
|---|---|---|
| Яндекс Директ | Кампании, объявления и ставки из чата | [yandex-direct](https://agenova.ru/integrations/yandex-direct/) |
| Яндекс Метрика | Счётчики и отчёты в одном запросе | [yandex-metrica](https://agenova.ru/integrations/yandex-metrica/) |
| VK Реклама | Кампании, объявления и статистика | [vk-ads](https://agenova.ru/integrations/vk-ads/) |
| Telegram-бот | Входящие сообщения бота и ответы | [telegram-bot](https://agenova.ru/integrations/telegram-bot/) |

Остальной живой каталог — на [agenova.ru/integrations](https://agenova.ru/integrations/), без слова MCP на витрине.

## Чем этот репозиторий не является

- Не локальный MCP-сервер для Cursor, Claude Desktop или Smithery.
- Не исходный код Agenova.
- Не заявка в official MCP Registry (она имеет смысл только после публичного remote с OAuth; такого URL здесь нет).
- Не поддержка клиентов. Операционные обращения не через GitHub Issues (Issues выключены).

## Товарные знаки

Wildberries, Ozon, Битрикс24 и другие названия — знаки правообладателей. Упоминание не означает одобрения, сертификации, спонсорства или партнёрства.

## Лицензия и безопасность

Документация в этом репозитории — [CC BY 4.0](LICENSE). Лицензия не даёт прав на товарные знаки Agenova и третьих лиц и не лицензирует хост или исходники серверов.

Как сообщить о подозрении на уязвимость: [SECURITY.md](SECURITY.md).
