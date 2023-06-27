# 💳 Frontend личного кабинета банковского приложения

## Задача

Написать Frontend для банковского приложения при наличии готового бэкенда с API

## Установка

Перед началом работы необходимо установить зависимости из `npm`:

```
npm i
```

Затем нужно перейти в директорию `server` и установить все зависимости для серверной части приложения:

```
npm i
```

Для работы приложения нужно запустить сервер с back-end частью проекта. Для этого из директории `server` нужно выполнить:

```
npm start
```

## Запуск

Далее есть два варианта запуска приложения:

### Запуск в режиме `development`

В этом режиме запускается `webpack-dev-server`

```
npm run dev
```

### Сборка в режиме `production`

В этом режиме проект собирается в директорию `dist`

```
npm run build
```

Необходимо запустить сервер в режиме SPA для корректной работы. Например, `serve -s dist` при использовании `serve`

### Данные для входа

Логин: `developer`

Пароль: `skillbox`

В приложении не предусмотрена регистрация новых пользователей

## Очистка

Команда удаляет папку `dist`

```
npm run clean
```

## Тестирование

Реализованы тесты на базовый функционал через `cypress`

```
npm test
```
