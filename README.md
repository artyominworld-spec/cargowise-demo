# CargoWise Trust Layer

## За 30 секунд

**Что это:** CargoWise connector — интеграция с логистической платформой для извлечения и проверки данных о перевозках.

**Кому:** Логистические компании на CargoWise — если есть контакт в отрасли.

**Что доказано:** 7 тестов.

**Чего не доказано (честно):** Узкая ниша, без контакта в логистике не продаётся.

---



FastAPI-стек для миграции с legacy SOAP eAdaptor на CargoWise eAdaptor Next (OAuth 2.0 + mTLS).

## What is this

Public demo repository for the CargoWise Trust Layer — a ready-made bridge for forwarders migrating to eAdaptor Next before January 2027.

## What works

- CargoWise eAdaptor Next connector (OAuth 2.0 + mTLS, Universal XML with DataContext)
- HMAC-SHA256 audit journal (tamper-evident)
- PII masking and anti-injection sanitizer
- FastAPI + Pydantic v2
- Mock CargoWise server for testing
- 7 tests passing

## Full source

Available on purchase. Contact for details.

## Pricing

| Уровень | Цена | Кому | Права |
|---|---|---|---|
| **Starter** | 350 000 RUB (one-time) | Малый форвардер, 1 интеграция | Код, 1 инстанс, без перепродажи |
| **Professional** | 900 000 RUB | Средний форвардер, несколько инстансов | Код, интеграция в свои продукты, 3 мес. поддержки |
| **Enterprise / OEM** | от 2 500 000 RUB | Крупный логистический оператор, IT-интегратор | OEM-лицензия, встраивание, 12 мес. поддержки, обновления |

Для покупки и вопросов: apumiaaifund@gmail.com

## Verification status

- Test suite: 7 passed (pytest, Python 3.12)
- FastAPI 0.115, Pydantic v2
- Full code: available on purchase (ZIP)
- Last verified: 2026-11-12

## Data integrity

**No synthetic data in production.** External sources are documented in `sources.yaml` (Private repo) with official URLs, real verification dates, and status. No fabricated dates. Demo artifacts are clearly marked as examples.

**Никакой синтетики в продакшене.** Внешние источники — в `sources.yaml` (Private репо) с официальными URL, реальными датами, статусом. Ни одной придуманной даты. Demo — помечены как примеры.

