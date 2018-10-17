---
title: Build JavaScript Objects
localeTitle: Создание объектов JavaScript
---
Объекты полезны для хранения данных структурированным способом и могут использоваться для представления объектов реального мира, таких как автомобили или отель, на компьютере.

Объекты похожи на массивы, за исключением того, что вместо использования индексов для доступа и изменения их данных вы получаете доступ к данным в объектах через так называемые свойства. Существует два способа создания объектов: Object Literal и Constructor.

Используя способ Object Literal, вот как мы будем создавать образец объекта:
```
var cat = { 
    name: "Whiskers", 
    legs: 4, 
    tails: 1, 
    enemies: ["Water", "Dogs"] 
 }; 
```

Используя способ Constructor, вот как мы будем создавать образец объекта:
```
var cat = new Object(); 
 cat.name = "Whiskers"; 
 cat.legs = 4; 
 cat.tails = 1; 
 cat.enemies = ["Water", "Dogs"]; 
```

В пути «Конструктор» мы используем `new` ключевое слово вместе с `Object` (с капиталом «O») для создания нового экземпляра объекта. Затем мы используем точечную нотацию для назначения имен свойств и значений объекта.