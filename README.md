<!-- file: README.md v1.0 -->

# RuCloud Web Engine

Mock API & Frontend учебный проект для разработки и тестирования фронтенда без реального сервера.

## Быстрый старт

```bash
# Установка
curl -fsSL https://raw.githubusercontent.com/Armruswest2024/RuCloud/main/install.sh | sudo bash

# Обновление
curl -fsSL https://raw.githubusercontent.com/Armruswest2024/RuCloud/main/update.sh | sudo bash -s -- -y

# Удаление
curl -fsSL https://raw.githubusercontent.com/Armruswest2024/RuCloud/main/delete.sh | sudo bash -s -- -f
```

## Структура

```
├── docker-compose.yml   # Nginx + PHP-FPM
├── install.sh           # Скрипт установки
├── update.sh            # Скрипт обновления
├── delete.sh            # Скрипт удаления
├── data/
│   ├── nginx.conf       # Mock API, security headers
│   ├── index.html       # SPA с Three.js 3D-фоном
│   └── status.php       # Health check endpoint
└── install/
    └── phase*.sh        # Фазы установки
```
