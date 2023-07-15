# Добро пожаловать в API Yatube!

Это API, созданное для управления контентом в социальной сети Yatube. Он предоставляет набор API для работы с различными функциями, такими как создание, обновление, удаление и поиск контента.

Для начала работы с API необходимо выполнить следующие шаги:

1. Клонировать репозиторий на свой компьютер.
2. Создать виртуальную среду и активировать ее.
3. Установить зависимости с помощью pip.
4. Запустить сервер разработки.

Чтобы начать работу с API, вы можете запустить следующие команды:

python manage.py create superuser

python manage.py runserver

## Пример использования api
### Регистрация
`POST /api/v1/users/`
```
{
  "email": "",
  "username": "",
  "password": ""
}
```
### Создание публикации
`POST /api/v1/posts/`

```
{
  "text": "text",
  "group": 1
}
```
