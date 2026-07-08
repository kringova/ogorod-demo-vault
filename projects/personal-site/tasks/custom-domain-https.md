---
id: 2
project: "[[personal-site/personal-site]]"
status: done
tags: [task]
created: 2026-05-18
created_at: 2026-05-18T09:15:00
updated: 2026-05-27
closed_at: 2026-05-27T14:00:00
sp: 2
rice_reach: 6
rice_impact: 4
rice_confidence: 95
rice_effort: 0.4
summary: "Настроить кастомный домен и HTTPS"
roles: [reviewer]
model_tier: junior
cost_io_tokens: 9600
cost_cache_tokens: 24000
cost_by_model: "claude-haiku-4-5-20251001=8400/21000; claude-sonnet-5=1200/3000"
---

## Что нужно сделать
Привязать свой домен к деплою на Vercel, включить автоматический HTTPS-сертификат.

## Почему важно
Ссылка на *.vercel.app не подходит для резюме и подписи письма.

## Критерии готовности (DoD)
- [x] Сайт открывается по своему домену
- [x] HTTP редиректит на HTTPS
- [x] Старый Medium-адрес не используется в новых ссылках

## Пререквизиты
#1 (каркас должен быть задеплоен)

## Вопросы
нет

## Заметки
DNS пока у старого регистратора — перевод на Cloudflare вынесен отдельной задачей (#8).
