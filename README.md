# Сайт бронирования номеров отеля
Этот проект реализован для прохождения второго этапа по обучающей программе frontend разработке от MetaLamp.

## Github pages здесь
[Ссылка на gh.pages этого проекта](https://bunglebrot.github.io/hotel-the-toxin/)

## Как работать? :rocket:
> т.к. все зависимости в этом проекте локальные, необходима установка **node.js**
* склонировать этот репозиторий
* выполнить `npm i` в склонированном репозитории
* выполнить `npm run dev` для работы в live режиме на порту **8081**
* команда `npm run build` выполнит сборку проекта
* команда `npm run deploy` выполнит деплой

## Какие инструменты я использовал? :wrench:
* **Pug** как замена HTML
* **Scss** как замена CSS
* библиотеку **jQuery**
* плагины для jQuery:
  - **ion-rangeslider**
  - **jquery.maskedinput**
  - **air-datepicker**
  - **slick-carousel**
  - **chart.js**
* сборку проекта выполнял **Webpack 4**
* расширение браузера **Pixel Perfect**
* методологию **БЭМ**
* нативный **Javascript**
* иконочные шрифты **Font Awesome** и **Material Icons**

---

## Компоненты :open_file_folder:
### Формы
* price-calculator-form
* registration-form
* search-room-form
* sign-in-form

## Параметры компонентов :key:
### button-UI
- *text* (***String***) - текст внутри кнопки
- *mode* (***String***) - `transparent` || `long` - стилевые модификаторы кнопки
- *type* (***String*** default: `button`) - тип кнопки
- *link* (***Boolean*** default: `false`) - если передать `true` ~~кнопка~~ превратится в ссылку + необходимо будет передать параметр *href*
- *href* (***String***) - путь для ссылки
