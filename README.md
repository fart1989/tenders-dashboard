# tenders-dashboard

Дашборды по лотам Бикотендера. Генерируются `agent-analitik` после каждого прогона пайплайна.

## Что внутри

- `index.html` — последний дашборд (обновляется автоматически)
- `lots-YYYY-MM-DD.html` — дашборды по датам

## Открыть

- **GitHub Pages:** https://fart1989.github.io/tenders-dashboard/
- Исходник реестра и pipeline — в локальном рабочем каталоге Хозяина.

## Как обновляется

После каждого прогона `agent-bicotender` → `agent-analitik` пушит новый HTML + обновляет `index.html`.
Pages обновляется в течение ~1 минуты.
