---
layout: article
title: Undefined & Null
urutan: 6
author: A. Akbar Hidayat
---

Suatu *variabel* akan dianggap bernilai `undefined` bila ia memiliki nilai `undefined`.

Ok, dalam kasus apa sebuah variabel memiliki nilai undefined? Ia akan memiliki nilai `undefined` bila ketika ia dideklarasikan, ia tidak diberikan suatu nilai apapun.

``` javascript
var sayaUndefined;

console.log(sayaUndefined); // undefined
```

Ok, bagaimana dengan `null`? Suatu *variabel* akan dianggap bernilai `null` bila ia memiliki nilai `null`. Secara teknis, `null` itu adalah referensi kosong. (TODO)

``` javascript
var sayaNull = null;
```