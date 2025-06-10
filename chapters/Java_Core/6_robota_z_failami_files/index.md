---
layout: default
title: "Робота з файлами (Files)"
parent: "Java Core"
has_children: true
nav_order: 6
---

# Робота з файлами (Files)

## 6. Робота з файлами (Files)
*   короткий опис: Огляд API для роботи з файловою системою, читання/запису текстових і бінарних файлів, серіалізації об'єктів та обробки типових помилок.
*   поняття: `java.io.File`, `FileWriter`, `BufferedWriter`, `PrintWriter`, `java.nio.file.Files`, `Path`, `FileReader`, `BufferedReader`, `Scanner`, `Files.readAllLines()`, `Files.readAllBytes()`, Абсолютний шлях, Відносний шлях, Обхід директорій (`listFiles()`, `Files.walk()`), Дозапис (`append`), Кодування (`UTF-8`), Великі файли, `flush()`, Серіалізація, `ObjectOutputStream`, `ObjectInputStream`, `Serializable`, `transient`, `serialVersionUID`, `IOException`, `FileNotFoundException`.
*   ключові моменти: Різниця між `java.io` і `java.nio.file`, буферизація, кодування, потокова обробка великих файлів, механізм серіалізації.
*   що важливо знати на співбесіді: `File` vs `Files`; `FileReader` vs `BufferedReader`; `FileWriter` vs `BufferedWriter` vs `PrintWriter`; серіалізація (`Serializable`, `transient`, `serialVersionUID`); обробка `IOException`.


## Зміст розділу: