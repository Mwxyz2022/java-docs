---
layout: default
title: "Stream API"
parent: "Java 8"
has_children: true
nav_order: 17
---

# Java 8: Stream API (Частина 2)

*   короткий опис: Детальний розбір Stream API: введення, типи операцій (проміжні/кінцеві), lazy evaluation, способи створення стрімів (включно з примітивними), трансформації (`map()` vs `flatMap()`), групування, пошук елементів, а також розширені можливості та нюанси продуктивності.
*   поняття: Stream, Проміжні операції, Кінцеві операції, Lazy Evaluation, `short-circuiting`, Способи створення Stream (`collection.stream()`, `Stream.of()`, `Arrays.stream()`, `Stream.generate()`, `Stream.iterate()`, `Files.lines()`), Примітивні стріми (`IntStream`, `LongStream`, `DoubleStream`), `mapToInt()`, `mapToLong()`, `mapToDouble()`, `map()`, `flatMap()`, `flattening`, `Map` як джерело Stream (`entrySet()`, `keySet()`, `values()`), `Collectors.toMap()`, `groupingBy()`, `counting()`, `summingInt()`, `averaging()`, `boxed()`, `mapToObj()`, `findFirst()`, `findAny()`, `anyMatch()`.
*   ключові моменти: Роль проміжних/кінцевих операцій, лінива оцінка, `map()` для трансформації, `flatMap()` для "сплющення" вкладених структур, агрегація даних.
*   що важливо знати на співбесіді: Різниця `map()` vs `flatMap()`; Lazy Evaluation; `parallelStream()` (коли, чому); `Collectors.toMap()`; `Collectors.groupingBy()`; `Optional` та Stream API; `reduce()` vs `collect()`; `IntStream`; Best Practices (продуктивність, дебагінг).


## Зміст розділу: