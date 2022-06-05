# Тестовое задание для Сферума.

## Стек технологий

Сборщик: **Vite**
**SPA** приложение написанное на **VUE 3**, **Options API**
Именование классов по **BEM**, минимальная ширина: **360 пикселей**,
Кроссбраузерный, без учета **IE 11**
Чуток **A11Y** (переключение по tab)

**axios** для работы с сервером
**stylelint** для валидации scss
**eslint** для валидации js
**legacy** для старых браузеров

- темная тема
- сохранение фильтров в url страницы, при перезагрузке сохраняются наши фильтры

## Мыслишки

Кнопку "Купить" на карточке товара решил сделать не на одинаковом уровне,
а в зависимости от высоты блока с названием и автороми
С сервера не прилетает ID книги (что странно), поэтому присваиваем ID книге сами,
но не факт что такой айдишник будет уникальным, наверное нужно подключить какой
нибудь генератор уникальных значений
Не уверен надо ли почти всё вынести в компоненты

## FIX

- обрезать название книги, если слишком много слов, чтобы не ломалась верстка
- обработка ошибок при получении данных с сервера

## Запуск

1. npm i
2. на любом сервере запустить файл index.html из dist