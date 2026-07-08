---
id: 12
project: "[[personal-site/personal-site]]"
status: todo
tags: [task]
created: 2026-06-30
created_at: 2026-06-30T11:00:00
updated: 2026-06-30
closed_at:
sp: 5
rice_reach: 2
rice_impact: 2
rice_confidence: 70
rice_effort: 1
summary: "Прогнать Lighthouse и подтянуть LCP на главной"
roles: [reviewer]
model_tier: middle
---

## Что нужно сделать
Разобраться, почему LCP на главной ~2.8с при цели «быстрый статический сайт»:
скорее всего, нужно ужать и переразмерить hero-картинку и подгрузить шрифт локально.

## Почему важно
Метрика проекта «Lighthouse Performance ≥ 90» сейчас на 78 — не дотягиваем.

## Критерии готовности (DoD)
- [ ] Lighthouse Performance на главной ≥ 90 в трёх последовательных прогонах
- [ ] LCP-элемент определён и явно оптимизирован (не случайно попал под порог)

## Пререквизиты
нет

## Вопросы
нет

## Заметки
