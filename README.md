# \<CooBook\>

Простейшее PWA, написанное буквально за ночь на Polymer. Писалось для получения автомата. Но преподаватель автомат зажал =( (Не понравился гугловый Material Design 0_O).

Приложение способно работать оффлайн благодаря service-worker. Данные хранит в локальной IndexedDB.
На самом деле хотел использовать async/await и другие преимущества ES7, но дедлайн был таааааак близок... поэтому мне пришлось использовать коллбэки IndexedDB.

The simplest PWA, written literally overnight at Polymer. Wrote to get the A grade and for avoid going to the exam. But the teacher was greedy =( (He did not like Google's Material Design 0_O).

The application is able to work offline thanks to the service-worker. The data is stored in the local IndexedDB.
Really wanted to use async/await and other advantages of ES7, but the deadline was sooooo close... so i had to use a IndexedDB callback's.

Cook Book for IT guys.

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create builds of your application in the `build/` directory, optimized to be served in production. You can then serve the built versions by giving `polymer serve` a folder to serve from:

```
$ polymer serve build/default
```
