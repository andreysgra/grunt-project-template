# Базовый шаблон проекта со сборкой на Grunt
[![Build status][travis-image]][travis-url] [![Dependency status][dependency-image]][dependency-url]

Шаблон предназначен для начала работы над проектом с использованием препроцессора LESS и сборщика проектов Grunt.

---

## Установка шаблона

```

$ git clone git@github.com:andreysgra/grunt-project-template.git project-name
$ cd project-name

```

---

## Как использовать

* `npm install` - установка зависимостей
* `npm run build` - сборка проекта
* `npm test` - запуск теста на наличие стилистических ошибок
* `npm start` - сборка проекта и запуск локального сервера
* `npm run deploy` - сборка проекта и отправка собранного проекта на GitHub Pages

---

## Структура

* `src` - каталог для размещения файлов проекта


[travis-image]: https://travis-ci.org/andreysgra/grunt-project-template.svg?branch=master
[travis-url]: https://travis-ci.org/andreysgra/grunt-project-template
[dependency-image]: https://david-dm.org/andreysgra/grunt-project-template/dev-status.svg?style=flat-square
[dependency-url]: https://david-dm.org/andreysgra/grunt-project-template?type=dev
