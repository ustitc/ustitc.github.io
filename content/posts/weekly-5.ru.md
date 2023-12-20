---
title: "Еженедельный обзор № 5"
date: 2021-10-14
draft: false
---

<!--more-->

**[[Статья] Capitalism, Socialism, and Code Ownership](https://blog.scottlogic.com/2021/09/30/Collective-Code-Ownership.html)**

Взгляд на проекты с точки зрения экономической теории. Почему в классическом open source лучше работает капитализм, а в коммерческой разработке социализм?

**[[Инструмент] Koka lang](https://github.com/koka-lang/koka) и [[Статья] Algebraic Effects for Functional Programming](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/08/algeff-tr-2016-v2.pdf)**

Концепция алгебраических эффектов реализованная на уровне языка программирования. 

Эффект - нечто, что может случится в вызываемой функции и изменить её ход исполнения. Задача пользователя функции определить, что делать, если эффект случится. Похоже на try/catch конструкцию, но

- С возможностью вернуться в место возникновения ошибки
- Можно описывать не только ошибки, но и [другие side-эффекты](https://koka-lang.github.io/koka/doc/book.html#sec-effect-types)
