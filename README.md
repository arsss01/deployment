# Air Astana Deployment

## Назначение проекта
Проект предназначен для запуска сервисов в docker, а также запуска postgres

## Требования
* Java 17
* Maven 3.8.5 >
* PostgreSQL latest
* Docker
* Docker Compose

## Запуск проекта

### 1. Запуск проекта в Docker
* переходим в корневую директорию deployment проекта
  > cd /deployment
* запускаем docker-compose файл
  > docker-compose up -d --build