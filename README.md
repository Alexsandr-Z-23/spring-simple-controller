# Простой Spring Boot контроллер

Простое Spring Boot приложение с двумя эндпоинтами:

1. `GET /` - возвращает "server is running"
2. `GET /ping` - возвращает "pong"

## Как запустить

1. Клонировать репозиторий
2. Собрать проект: `mvn clean install`
3. Запустить приложение: `mvn spring-boot:run`

## Тестирование эндпоинтов

После запуска приложения можно протестировать эндпоинты:

- http://localhost:8080/
- http://localhost:8080/pong
<img width="356" height="140" alt="image" src="https://github.com/user-attachments/assets/f4394686-a996-4c9e-a14e-341a2b640c53" />
<img width="294" height="136" alt="image" src="https://github.com/user-attachments/assets/1a0586b1-24b3-423b-855f-ca8d46fc0db8" />
