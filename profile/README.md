# Squalus Mentor

Авторские курсы и разборы для тех, кто идёт в **DevOps**.

Здесь лежат материалы, которые я использую на занятиях с менти: теория прозой в
`README.md` каждого урока, практика — файлами с заглушками, решения — рядом в
`solutions/` или `resolve/`. Плюс подборка реальных тестовых заданий различных компаний
 — на них удобно тренироваться перед выходом на рынок.

---

## Курсы

### [lessons-devops](https://github.com/squalusmentor/lessons-devops)


### [lessons-python](https://github.com/squalusmentor/lessons-python)


### [lessons-go](https://github.com/squalusmentor/lessons-go)

## Тестовые задания

Репозитории вида `TestTask_ГГММДД` — это **реальные тестовые задания с
собеседований**, выполненные целиком. Дата в названии — когда задание было
получено. Каждое можно взять как эталон разбора: посмотреть постановку,
архитектуру решения и то, как оно оформлено под сдачу.

| Репозиторий | Позиция | Что внутри |
|---|---|---|
| [TestTask_260324](https://github.com/squalusmentor/TestTask_260324) | DevOps, Effective Mobile | Два контейнера в Docker Compose: nginx как reverse proxy и единственная точка входа + Python/FastAPI-приложение без открытого наружу порта. Конфигурация через `.env`. |
| [TestTask_260329](https://github.com/squalusmentor/TestTask_260329) | Python Developer, Effective Mobile | REST API на FastAPI с системой прав: пользователи и админы, владение объектами через `owner_id`, ответы 403 на чужие ресурсы. Swagger UI, сиды тестовых данных, запуск в Docker Compose. |
| [TestTask_260407](https://github.com/squalusmentor/TestTask_260407) | DevOps, GreenApi | Веб-клиент к WhatsApp API (`getSettings`, `getStateInstance`, `sendMessage`, `sendFileByUrl`) на Hugo + Bootstrap 5, раздача через Nginx, деплой одной командой `docker compose up`. |
| [TestTask_260716](https://github.com/squalusmentor/TestTask_260716) | DevOps | Полноценный локальный стенд: Nginx с TLS-termination на 443 (self-signed), Flask-бэкенд, PostgreSQL 15, Redis 7. Rate limiting, проброс `X-Forwarded-*`, healthcheck'и, генерация сертификатов скриптом. |

---

Сделал Григорий Тимонин.

Вопросы по курсам и запись на занятия — в [телеграме](https://t.me/kot_gray).
