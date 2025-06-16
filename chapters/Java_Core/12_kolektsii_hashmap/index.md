---
layout: default
title: "Колекції: HashMap"
parent: "Java Core"
has_children: true
nav_order: 12
---

# Колекції: HashMap

* короткий опис: Детальний розбір внутрішньої роботи `HashMap`, механізмів хешування, обробки колізій, ресайзингу, а також порівняння з `Hashtable` та використання у багатопоточному середовищі.

* поняття: `Map`, `HashMap`, Ключ-значення, `put()`, `get()`, Хешування, Індексація, `hashCode()`, `capacity`, `Node<K, V>`, `bucket[]`, Колізії, `LinkedList` (для колізій), Червоно-чорне дерево (з Java 8), Ресайзинг (`resize`), `load factor`, `threshold`, `rehashing`, `size()`, `containsKey()`, `containsValue()`, `remove()`, `clear()`, `keySet()`, `values()`, `entrySet()`, `Hashtable`, `ConcurrentHashMap`, Потоконебезпека, `race condition`, Порядок елементів.

* ключові моменти: `HashMap` не гарантує порядок, `null` ключ, `O(1)` швидкість у середньому, обробка колізій (список/дерево), `resize` як дорога операція.

* що важливо знати на співбесіді: Внутрішня реалізація `HashMap`; `hashCode()`/`equals()` контракт; колізії (як вирішуються); `resize` (коли, як); `HashMap` vs `Hashtable`; `HashMap` у багатопоточності (небезпечно, `ConcurrentHashMap` як альтернатива).

## Зміст розділу
