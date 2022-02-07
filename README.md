# Angular Test Task

## Порядок выполнения

1. Форкнуть репозиторий
2. Добавить CONTRIBUTORS.md со своими данными
3. Сделать задание
4. Сделать pull-request к данному репозиторию

## Задание

Сделать веб-приложение на Angular для добавления и просмотра тезисов API.

API доступно по ссылке:
https://conf.antibiotic.ru/demo/api

Интерфейс Swagger с примерами работы с API доступен по ссылке
https://conf.antibiotic.ru/demo/swagger/index.html

Можно использовать любые фреймворки для оформления: Angular Material, PrimeNg, Bootstrap, Tailwind, и т.д.

По итогу приложение должно содержать четыре экрана:
- Добавление нового тезиса
- Просмотр списка тезисов
- Просмотр одного тезиса
- Редактирование одного тезиса


### Пример формы заполнения

![img](./preview.png)

Если отправке формы на сервер возникла ошибка, она должна отображаться на экране.

Пример сообщения об ошибке:

```json
{
  "type": "https://tools.ietf.org/html/rfc7231#section-6.5.1",
  "title": "One or more validation errors occurred.",
  "status": 400,
  "traceId": "00-6e55b4c27b900788da73c60c0aff997c-d6c3beda2aad2a9a-00",
  "errors": {
    "MainAuthor.FirstName": [
      "The FirstName field is required."
    ]
  }
}
```
