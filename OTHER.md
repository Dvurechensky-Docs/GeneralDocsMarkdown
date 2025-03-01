- [Разное](#разное)
  - [Комментарии](#комментарии)
  - [Исключение символов в формате Markdown](#исключение-символов-в-формате-markdown)
  - [Emojis](#emojis)
  - [Перевод строки](#перевод-строки)
  - [Вернуться к началу](#вернуться-к-началу)
- [Инструменты (Пока нужен интернет - переношу к нам)](#инструменты)

# Разное

## Комментарии

<!--
Мы хотим кофе
-->

```md
<!--
Мы хотим кофе
-->
```

## Исключение символов в формате Markdown

- **Before escaping**

```md
* Звездочка
\ Обратный слеш
` Обратный знак
{} фигурные скобки
. Точка
! Восклицательный знак
# Символ тире
- Символ дефиса
() Скобки
+ Символ плюса
[] Квадратные скобки
_ Знак подчеркивания`
```

* Звездочка \
\ Обратный слеш \
` Обратный знак \
{} фигурные скобки \
. Точка \
! Восклицательный знак
# Символ тире
- Символ дефиса \
() Скобки
+ Символ плюса \
[] Квадратные скобки \
_ Знак подчеркивания

- **After escaping**

```md
\* Звездочка
\\ Обратный слеш
\` Обратный знак
\{} фигурные скобки
\. Точка
\! Восклицательный знак
\# Символ тире
\- Символ дефиса
\() Скобки
\+ Символ плюса
\[] Квадратные скобки
\_ Знак подчеркивания
```

\* Звездочка \
\\ Обратный слеш \
\` Обратный знак \
\{} фигурные скобки \
\. Точка \
\! Восклицательный знак \
\# Символ тире \
\- Символ дефиса \
\() Скобки \
\+ Символ плюса \
\_ Знак подчеркивания

## Emojis

```md
:earth_asia:
```
:sparkler:

[Полный список разметки эмодзи на github](https://www.dvurechensky.pro/dvurechensky_pro/EmojiCollectionsMarkdown)

## Перевод строки

<!-- markdownlint-disable-next-line MD038 -->
Вы можете использовать `<br>` для вставки разрыва строки. Обязательно используйте пробел ` `. Например:

```md
<table><tr><td> <br> Все любят чай. <br> </td></tr></table>
```

<table><tr><td> <br>Все
 любят пить кофе и чай с печеньем
  по утрам. <br> </td></tr></table>

Or

```md
<table><tr><td> <br><br><br> Все любят чай. <br><br><br> </td></tr></table>
```

<table><tr><td> <br><br><br> Все
 любят пить кофе и чай с печеньем
  по утрам. <br><br><br> </td></tr></table>

## Вернуться к началу

Сначала поместите следующий код в начало вашего файла с разметкой

```md
<a name="top"></a>
```

Затем используйте один из следующих кодов в том месте, где вы хотите вернуться к началу.

[Back to top](#top)

[:arrow_up:](#top)

```md
[Back to top](#top)

[:arrow_up:](#top)
```

# Инструменты

1. Создайте таблицу содержимого в формате - [binarytree](https://binarytree.dev/markdown/toc), [github-markdown-toc](https://github.com/ekalinin/github-markdown-toc)
2. Создайте пустую таблицу в формате Markdown - [Tablesgenerator](https://www.tablesgenerator.com/markdown_tables)
3. Конвертируйте Excel в таблицу Markdown - [Tableconvert](https://tableconvert.com/)
4. Предварительный просмотр Markdown для Sublime Text 3 - [Packagecontrol](https://packagecontrol.io/packages/MarkdownPreview)
5. Предварительный просмотр в формате Markdown для Visual Studio Code - [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)
6. Коллекция потрясающих возможностей для разметки - [Awesome Markdown](https://github.com/mundimark/awesome-markdown)
7. Markdownlint - [markdownlint](https://github.com/DavidAnson/markdownlint), [markdownlint-cli2](https://github.com/DavidAnson/markdownlint-cli2), [markdownlint-cli2-action](https://github.com/DavidAnson/markdownlint-cli2-action), [vscode-markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)

---