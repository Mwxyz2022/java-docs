---
layout: default
title: "PECS (Producer Extends, Consumer Super)"
parent: "Java Core"
has_children: true
nav_order: 11
---

# PECS (Producer Extends, Consumer Super)

*   короткий опис: Поглиблене вивчення варіантності у дженеріках, символів підстановки (`? extends`, `? super`) та принципу PECS, його застосування у стандартній бібліотеці Java та при дизайні власного API.
*   поняття: Варіантність (інваріантність, коваріантність, контраваріантність), Символ підстановки (`Wildcard`, `?`), Коваріантність (`? extends T`), Контраваріантність (`? super T`), Принцип PECS (Producer Extends, Consumer Super), `Type Erasure`, `PECS` у стандартній бібліотеці (`Collections.copy()`, `Comparator`, `Consumer`, `Function`), Вибір варіантності у власному API.
*   приклади: `List<? extends Number>`, `List<? super Integer>`, `Collections.copy(dest, src)`, `Comparator<? super T>`.
*   ключові моменти: `extends` для читання ("виробник"), `super` для запису ("споживач"), `Type Erasure` як причина обмежень.
*   що важливо знати на співбесіді: Розшифровка та застосування PECS; `? extends` vs `? super` (що можна/не можна робити); why `Type Erasure` affects variance; PECS у `Collections.copy()`.


## Зміст розділу:
