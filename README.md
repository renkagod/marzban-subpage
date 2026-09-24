# Marzban Subpage

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Страница подписки для панели [Marzban](https://github.com/Gozargah/Marzban): Jinja2-шаблон с отображением конфигов, QR-кодов и статуса подписки, который рендерит сама панель.

## Особенности

- Один файл `index.html`, без сборки
- Jinja2-переменные (`{{ user.username }}`, `{{ user.expire }}`, `{{ user.data_limit }}` и другие) заполняются бэкендом Marzban при рендере страницы
- Тёмная тема, QR-коды, анимация фона

## Быстрый старт

1. Клонируйте репозиторий:

   ```bash
   git clone https://github.com/renkagod/marzban-subpage.git
   cd marzban-subpage
   ```

2. Скопируйте `index.html` в каталог шаблонов Marzban (например, `subscription/index.html` внутри `CUSTOM_TEMPLATES_DIRECTORY`) и укажите его в `.env` панели:

   ```dotenv
   CUSTOM_TEMPLATES_DIRECTORY=/var/lib/marzban/templates/
   SUBSCRIPTION_PAGE_TEMPLATE=subscription/index.html
   ```

3. Перезапустите Marzban — страница подписки начнёт рендериться из этого шаблона.

## Структура

| Путь | Назначение |
|------|------------|
| `index.html` | Шаблон страницы подписки |

## Документация

Настройка кастомного шаблона подписки — в [документации Marzban](https://gozargah.github.io/marzban/).

## Лицензия

[MIT](LICENSE) — Copyright (c) 2026 [renkagod](https://github.com/renkagod).
