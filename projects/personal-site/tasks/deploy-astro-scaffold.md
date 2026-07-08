---
id: 1
project: "[[personal-site/personal-site]]"
status: done
tags: [task]
created: 2026-05-10
created_at: 2026-05-10T10:00:00
updated: 2026-05-20
closed_at: 2026-05-20T16:40:00
sp: 5
rice_reach: 8
rice_impact: 5
rice_confidence: 90
rice_effort: 1
summary: "Собрать каркас на Astro и задеплоить на Vercel"
roles: [reviewer]
model_tier: middle
cost_by_model: "claude-sonnet-5=48200/152000; claude-haiku-4-5-20251001=6100/9800"
---

## Что нужно сделать
Инициализировать проект на Astro + Tailwind, настроить деплой на Vercel из git.

## Почему важно
Без каркаса и автодеплоя нет площадки для остального контента — фаза 1 роадмапа.

## Критерии готовности (DoD)
- [x] Сайт открывается по адресу *.vercel.app
- [x] Пуш в main деплоит новую версию без ручных действий
- [x] Есть базовый layout (шапка, футер, контейнер контента)

## Пререквизиты
нет

## Вопросы
нет

## Заметки
Выбор Astro вместо Next — см. `decisions.md` (2026-05-08).
