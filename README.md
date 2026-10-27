# Гороскоп земли 2027

Мини-лендинг в формате игры для Академии земельных инвесторов: выбор знака → 3 вопроса → персональный прогноз → переход в Telegram-бота `@baza_by_land_bot`.

## Структура
- `index.html` — вся страница (HTML, CSS, JS в одном файле, без сборки)
- `docs/` — заметки по проекту
- `.github/workflows/pages.yml` — автопубликация на GitHub Pages
- `.nojekyll` — отключает обработку Jekyll

## Настройка
- Username бота: константа `BOT` в `index.html` (сейчас `baza_by_land_bot`)
- Параметр start для бота: `знак_цель_приоритет_стиль_ld`, например `pisces_money_asset_calc_ld`

## Публикация
Settings → Pages → Source: GitHub Actions. После push в `main` сайт опубликуется автоматически.
