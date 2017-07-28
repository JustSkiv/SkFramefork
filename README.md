# SK-Framework v0.1

## Описание

Данный проект представляет собой небольшой MVC-фреймворк, написанный в образовательных целях.

На данный момент в проекте имеется несколько тестовых контроллеров, представлений и моделей. В скором времени я их уберу.


## Краткая справка по структуре


```
- public/index.php - основной скрипт, принимающий пользовательские запросы

- vendor/core - ядро фреймворка
-- vendor/core/base - базовые контроллер, модель и представление
-- vendor/core/Db.php - подключение к БД
-- vendor/core/Router.php - маршрутизация

- vendor/libs - подключаемые библиотеки
-- vendor/libs/helpers - классы со вспомогательными методами

- app - приложение (контроллеры, модели, представления)

- config - конфигурация приложения (настройка подключения к БД)

```

## Обратная связь
По всем вопросам обращаться сюда: tuzov.n@gmail.com
