# Бумеранг — 3D-модель

Статическая страница с 3D-моделью бумеранга для GitHub Pages.

- `index.html`, `boomerang.js` — генерируются скриптом сборки из папки проекта. Руками не править:
  пересобрать и закоммитить.
- `three.min.js` — three.js r128.

## Подставки под бумеранг-волну

- `volna/podstavki/index.html` — страница для клиента (шесть вариантов формы).
- `volna/podstavki/rabota/index.html` — рабочая страница со всеми вариантами.

Обе генерируются скриптом `stand_concepts.py` из папки проекта
(`KnowledgeBase/_data/Lobaro/Бумеранг-сувенир/Запрос-Re-презент/Подставка-модель`,
запуск `blender -b --factory-startup -P stand_concepts.py`). Руками не править.
