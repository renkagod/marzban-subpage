# Marzban Subpage

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Статическая страница подписки для панели [Marzban](https://github.com/Gozargah/Marzban): отображение конфигов, QR-кодов и ссылок для клиентов.

## Особенности

- Одностраничный `index.html` без сборки
- Тёмная тема, QR-коды, анимация фона
- Подходит для размещения за reverse proxy (nginx/Caddy)

## Быстрый старт

1. Клонируйте репозиторий:

   ```bash
   git clone https://github.com/renkagod/marzban-subpage.git
   cd marzban-subpage
   ```

2. Разместите файлы на веб-сервере (корень сайта или подкаталог).

3. Настройте Marzban и URL подписки по [документации Marzban](https://github.com/Gozargah/Marzban).

## Структура

| Путь | Назначение |
|------|------------|
| `index.html` | Страница подписки |

## Документация

Подробная настройка панели — в репозитории и вики Marzban (см. ссылку выше).

## Лицензия

[MIT](LICENSE) — Copyright (c) 2026 [renkagod](https://github.com/renkagod).
