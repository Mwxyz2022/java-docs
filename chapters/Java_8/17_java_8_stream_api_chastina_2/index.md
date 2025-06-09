---
layout: default
title: "Java 8: Stream API (Частина 2)"
parent: "Java 8"
has_children: true
nav_order: 17
---

# Java 8: Stream API (Частина 2)

Детальний розбір Stream API: введення, типи операцій (проміжні/кінцеві), lazy evaluation, способи створення стрімів (включно з примітивними), трансформації (`map()` vs `flatMap()`), групування, пошук елементів, а також розширені можливості та нюанси продуктивності.

## Зміст розділу:

- [17.1. Введення в Stream API](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.1_vvedennia_v_stream_api/)
- [17.2. Типи операцій у Stream API](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.2_tipi_operatsii_u_stream_api/)
- [17.3. Ледачість потоків (Lazy Evaluation)](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.3_ledachist_potokiv_lazy_evaluation/)
- [17.4. Способи створення потоків](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.4_sposobi_stvorennia_potokiv/)
- [17.5. Стріми примітивів](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.5_strimi_primitiviv/)
- [17.6. mapToInt() та перетворення типів](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.6_maptoint_ta_peretvorennia_tipiv/)
- [17.7. Трансформація даних: map() vs flatMap()](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.7_transformatsiia_danikh_map_vs_flatmap/)
- [17.8. Робота з Map як джерелом даних](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.8_robota_z_map_iak_dzherelom_danikh/)
- [17.9. Збирання результатів: Collectors.toMap()](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.9_zbirannia_rezultativ_collectors_tomap/)
- [17.10. Групування даних: Collectors.groupingBy()](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.10_grupuvannia_danikh_collectors_groupingby/)
- [17.11. Перетворення примітивів: boxed() та mapToObj()](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.11_peretvorennia_primitiviv_boxed_ta_maptoobj/)
- [17.12. Пошук елементів: findFirst(), findAny(), anyMatch()](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.12_poshuk_elementiv_findfirst_findany_anymatch/)
- [17.13. Паралельні стріми](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.13_paralelni_strimi/)
- [17.14. Інші важливі операції Stream API](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.14_inshi_vazhlivi_operatsii_stream_api/)
- [17.15. Optional та Stream API](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.15_optional_ta_stream_api/)
- [17.16. Продуктивність та дебагінг](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.16_produktivnist_ta_debaging/)
- [17.17. Статистичні операції та агрегація](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.17_statistichni_operatsii_ta_agregatsiia/)
- [17.18. Власні Collector'и](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.18_vlasni_collector_i/)
- [17.19. Складні операції collect()](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.19_skladni_operatsii_collect/)
- [17.20. Stream API з Optional](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.20_stream_api_z_optional/)
- [17.21. Infinite Streams та обмеження](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.21_infinite_streams_ta_obmezhennia/)
- [17.22. Порівняння з традиційними циклами](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.22_porivniannia_z_traditsiinimi_tsiklami/)
- [17.23. Stream API та винятки (Exceptions)](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.23_stream_api_ta_viniatki_exceptions/)
- [17.24. Типові помилки та підводні камені](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.24_tipovi_pomilki_ta_pidvodni_kameni/)
- [17.25. Stream API у багатопотоковому середовищі](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.25_stream_api_u_bagatopotokovomu_seredovishchi/)
- [17.26. Методи порівняння та сортування](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.26_metodi_porivniannia_ta_sortuvannia/)
- [17.27. Integration з іншими API](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.27_integration_z_inshimi_api/)
- [17.28. Питання на співбесіді по Stream API](/java-docs/chapters/Java_8/17_java_8_stream_api_chastina_2/17.28_pitannia_na_spivbesidi_po_stream_api/)
