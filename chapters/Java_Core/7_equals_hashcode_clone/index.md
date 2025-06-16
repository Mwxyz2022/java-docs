---
layout: default
title: "`equals()`, `hashCode()`, `clone()`"
parent: "Java Core"
has_children: true
nav_order: 7
---

# `equals()`, `hashCode()`, `clone()`

* короткий опис: Детальний розбір ключових методів з `java.lang.Object` для порівняння, хешування та копіювання об'єктів.

* поняття: `equals()`, `hashCode()`, `clone()`, Контракт `equals()/hashCode()`, Рефлексивність, Симетричність, Транзитивність, Консистентність, Порівняння з `null`, Хеш-колізія, `Cloneable`, Поверхневе копіювання (`Shallow copy`), Глибоке копіювання (`Deep copy`), Альтернативи `clone()` (конструктор копіювання, метод `copy()`, Builder pattern), `Objects.equals()`, `Objects.hash()`, `==` vs `equals()`, `instanceof` vs `getClass()`.

* ключові моменти: Обов'язковість перевизначення `equals()` і `hashCode()` разом, контракт між ними, ризики `clone()`, переваги `deep copy`.

* що важливо знати на співбесіді: 5 правил `equals()`; контракт `equals()/hashCode()`; `shallow` vs `deep copy`; чому `clone()` вважається поганою практикою; `==` vs `equals()`.

## Зміст розділу
