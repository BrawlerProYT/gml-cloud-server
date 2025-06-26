# GML Cloud Server (для Railway)

## 🚀 Как запустить через Railway

1. Закинь этот проект в GitHub (например, `gml-cloud-server`)
2. Перейди на https://railway.app и нажми "New Project"
3. Выбери "Deploy from GitHub" и подключи этот репозиторий
4. Railway сам поднимет контейнеры через `docker-compose.yml`

## 🛠 Что внутри

- `docker-compose.yml` — запуск всех сервисов
- `.env` — настройки проекта
- `frontend/Gml.Web.Client` — веб-панель авторизации

## ✅ Не забудь
- После запуска, адрес панели будет: `https://<твой-проект>.up.railway.app` (порт 5003)
- В лаунчере используй этот адрес вместо `localhost`!
