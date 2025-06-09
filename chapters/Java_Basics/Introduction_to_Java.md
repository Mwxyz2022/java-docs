---
layout: default
title: Вступ до Java
parent: Основи Java # Батьківський розділ
nav_order: 1 # Порядок в межах розділу "Основи Java"
permalink: /chapters/Java_Basics/Introduction_to_Java/ 
---
# Вступ до Java

## Що таке Java?

**Java** - це високорівнева, об'єктно-орієнтована мова програмування, розроблена Sun Microsystems (нині Oracle) у 1995 році. Вона відома своїм принципом "Напиши один раз, запускай скрізь" (WORA - Write Once, Run Anywhere), завдяки використанню Java Virtual Machine (JVM).

## Особливості Java:

*   **Незалежність від платформи:** Код компілюється в байт-код, який виконується на будь-якій JVM.
*   **Об'єктно-орієнтована:** Все в Java - це об'єкт (майже).
*   **Безпечна:** Вбудовані механізми безпеки.
*   **Надійна:** Механізми обробки винятків, управління пам'яттю.
*   **Багатопоточна:** Підтримує паралельне виконання завдань.

## Перша програма "Hello World":

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Привіт, Світ!");
    }
}
```
## Компіляція та запуск:
* Збережіть код як HelloWorld.java.
* Компіляція: javac HelloWorld.java
* Запуск: java HelloWorld