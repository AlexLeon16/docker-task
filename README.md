# Домашнее задание: PostgreSQL в Docker

## Описание
В проекте настроен запуск PostgreSQL в Docker Compose и подключение готового Java-приложения `db-api.jar` к базе данных PostgreSQL.

## Состав проекта
- `.gitignore`
- `db-api.jar`
- `application.properties`
- `docker-compose.yml`
- `README.md`

## Запуск

### 1. Запустить PostgreSQL
```bash
docker-compose up