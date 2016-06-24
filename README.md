# Markdwn Cheatsheet

![markdown_speak](./markdown_speak.jpg)


# Table of Contents

* [Headers](#headers)
* [Bold, Italic and Strikethrough](#bold-italic-and-strikethrough)
* [Lists](#lists)
 * [Ordered Lists](#ordered-lists)
 * [Unordered Lists](#unordered-lists)
* [Links](#links)
* [Images](#images)
* [Image Size](#image-size)
* [Codeblocks and Inline Code](#codeblocks-and-inline-code)
* [Tables](#tables)
* [Blockquotes](#blockquotes)
* [Inline HTML](#inline-html)
* [Horizonatl Rule](#horizontal-rule)
* [Table of Contents](#table-of-contents)
* [E-Mail Addresses](#e-mail-addresses)

---

This is my little markdown cheatsheet to look if I ever forget a syntax string.

## Headers

To create headers just use ```#```:
```
# h1
## h2
### h3
#### h4
##### h5
###### h6
```
# Header 1
## Header 2
## Header 3
---

If you want a header with a unterline use ```=``` or ```-```:
```
Header
======

Header
------
```
Header
======

Header
------

---

## Bold, Italic and Strikethrough

**Bold Text** can be written with ```**```:
```
**Bold Text**
```
*Italic text* can be written with ```*```:
```
*Italic Text*
```
~~Strikethrough Text~~ can be written with ```~~```:
```
~~Strikethrough Text~~
```
---

## Lists

## Ordered Lists

Ordered Lists start with numbers:
```
1. List 1
2. List 2
3. List 3
 * List 3.x
4. List 4
```
1. List 1
2. List 2
3. List 3
 * List 3.x
4. List 4

## Unordered Lists

Unordered lists start with ```*```, ```-``` or ```+```:
```
* unoredered 1
- unoredered 2
+ unoredered 3
```
* unoredered 1
- unoredered 2
+ unoredered 3

---

## Links

You can use an inline link:
```
[Link-Text](http://link-url/)
```

Or you can use URLs directly:
```
https://google.de/
```
[Link-Text](http://link-url/)

https://google.de/

---

## Images

Inline images:
```
![alt_text](path/to/picture or /link/to/picture/)
```

Reference Images:
```
![alt_text][bla]

[bla](path/to/picture or /link/to/picture/)
```

![markdown_speak](./markdown_speak.jpg)

![markdown_speak][markdown]
[markdown](./markdown_speak.jpg)

---

## Image Size

You can also insert images with defined sizes:
```
![](./wwe_markdown.png =100x20)
```

Or just without height:
```
![](./wwe_markdown.png =250x)
```

## Codeblocks and Inline Code

Codeblocks ban be used with 4 spaces or 3 backticks:
```
    4 spaces for code
```

    ```
    backticks for code
    ```

Inline code is written with backticks:

    ```inlinde code```

-

    Codeblock

Or ```Inline Code```.

---

## Tables

Tables are written with pipes and dashes:

```
| Column 1 | Column 2 | Column 3 |
| -------- | -------- | -------- |
| Just | insert | dahses |
| And | also | new lines |
```
| Column 1 | Column 2 | Column 3 |
| -------- | -------- | -------- |
| Just | insert | dahses |
| And | also | new lines |

---

## Blockquotes

Blockquotes can be inserted with ```>```:
```
> Blockquote


> Multiline
> Blockquote
```

> Blockquote

-

> Multiline</br>
> Blockquote

---

## Inline HTML
You can use almost every HTML tag in markdown without a problem. Just play with it.

---

## Horizonatl Rule

Can be inserted on multiple ways. With 3 underscores, 3 stars or 3 hyphens:
```
---
***
___
```

---

## Table of Contents

You can also use a table of contents:

```
# Table of Contents
1. [Example](#example)
2. [Example2](#example2)
3. [Third Example](#third-example)

## Example
## Example2
## Third Example
```

---

## E-Mail Addresses

E-Mail addresses can be simply added:
```
<mail@example.com>
```
<mail@example.com>
