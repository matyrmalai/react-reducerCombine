# react-reducerCombine-actionCreator
## Использование Combine
Была создана отдельная папка Store. В ней для кажого reducer созданы отдельные файлы и index.js - Общий файл со store, объединяющий reducer, который передаем в provider.

## Работа с массивами
Добавление.
Раскрываем массив и добавляем туда свой action payload

Удаление.
Удаление элементов происходит через метод Filter

Рендеринг массива объектов происходит через метод map. Есть условие если массив пуст, то выводим предупреждение, иначе выводим объект.

## ActionCreater
Т.к. в dispatch передаются однотипные объекты, то это можно оптимизировать.
Для этого создается функция actionCreater ( простейшая фун-кция, которая будет возваращть нам объект и параметром принимать данные).
Создан рядом c reducer.
