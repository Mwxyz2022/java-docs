---
layout: default
title: Класи та Об'єкти
parent: Об'єктно-орієнтоване Програмування (ООП)
nav_order: 1
permalink: /chapters/OOP/classes_and_objects/
---
# Класи та Об'єкти

## Класи

Клас - це шаблон або креслення для створення об'єктів. Він визначає стан (змінні) та поведінку (методи) об'єкта.

```java
public class Car {
    String make;  // Змінна стану
    String model; // Змінна стану

    // Метод поведінки
    public void accelerate() {
        System.out.println("Автомобіль прискорюється!");
    }
}
```