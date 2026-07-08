---
id: 4
project: "[[personal-site/personal-site]]"
status: done
tags: [task]
created: 2026-06-10
created_at: 2026-06-10T10:30:00
updated: 2026-06-22
closed_at: 2026-06-22T17:00:00
sp: 3
rice_reach: 4
rice_impact: 3
rice_confidence: 85
rice_effort: 0.6
summary: "RSS-фид и sitemap для блога"
roles: [reviewer]
model_tier: middle
cost_io_tokens: 25300
cost_cache_tokens: 65100
cost_by_model: "claude-sonnet-5=22500/61000; claude-haiku-4-5-20251001=2800/4100"
---

## Что нужно сделать
Сгенерировать `rss.xml` и `sitemap.xml` при сборке, подключить их в `<head>`.

## Почему важно
Без RSS блог нельзя читать в ридере; без sitemap хуже индексация поисковиком.

## Критерии готовности (DoD)
- [x] `/rss.xml` валиден и содержит все посты
- [x] `/sitemap.xml` перечисляет все страницы
- [x] Оба файла обновляются автоматически при новом посте

## Пререквизиты
нет

## Вопросы
нет

## Заметки
