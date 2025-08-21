---
layout: default
title: 'Подсветка синтаксиса 🔥'
description: 'Подсветка синтаксиса в Markdown'
author: 'Dvurechensky'
date: 2025-08-21
published: true
tags:
  - syntax
  - highlighting
  - markdown
---

**[⬆ Вернуться к оглавлению](../index.md)**

# Подсветка синтаксиса

- [Встроенный код](#встроенный-код)
- [Блок кода](#блок-кода)
- [Блок дифф-кода](#блок-дифф-кода)

## Встроенный код

Метод класса - это метод экземпляра объекта класса. При создании нового класса инициализируется объект типа `Class`, которому присваивается глобальная константа (в данном случае Mobile).

Вы можете использовать <kbd>command + e </kbd> на Mac или <kbd>control + e</kbd> на Windows чтобы вставить встроенный код.

## Блок кода

```csharp
public static String monthNames[] = {"January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"};
```

````md
```csharp
public static String monthNames[] = {"January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"};
```
````

```java
public static String monthNames[] = {"January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"};
```

````md
```java
public static String monthNames[] = {"January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"};
```
````

## Блок дифф-кода

```diff
## git diff a/test.txt b/test.txt
diff --git a/a/test.txt b/b/test.txt
index 309ee57..c995021 100644
--- a/a/test.txt
+++ b/b/test.txt
@@ -1,8 +1,6 @@
-Все любят чай.
+Все не любят пить кофе и чай с печеньем по утрам.

 a
-b
 c
 d
-e
 f
```

````md
```diff
## git diff a/test.txt b/test.txt
diff --git a/a/test.txt b/b/test.txt
index 309ee57..c995021 100644
--- a/a/test.txt
+++ b/b/test.txt
@@ -1,8 +1,6 @@
-Все любят чай.
+Все не любят пить кофе и чай с печеньем по утрам.

 a
-b
 c
 d
-e
 f
```
````

```diff
- Красный текст
+ Зелёный текст
! Синий текст
# Серый текст
@@ Пурпурный и жирный текст @@
```

````md
```diff
- Красный текст
+ Зелёный текст
! Синий текст
# Серый текст
@@ Пурпурный и жирный текст @@
```
````
