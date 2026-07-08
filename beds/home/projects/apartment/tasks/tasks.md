---
tags: [index]
---

# Задачи apartment

```dataview
TABLE WITHOUT ID
  file.link AS "Задача",
  status AS "Статус",
  due AS "Срок",
  summary AS "Описание"
FROM "beds/home/projects/apartment/tasks"
WHERE file.name != "tasks"
SORT due ASC
```
