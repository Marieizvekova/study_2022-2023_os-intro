---
## Front matter
title: "Лабораторная работа №7"
subtitle: "Командная оболочка Midnight
Commander"
author: "Извекова Мария Петровна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Освоение основных возможностей командной оболочки Midnight Commander. Приоб-
ретение навыков практической работы по просмотру каталогов и файлов; манипуляций
с ними.


# Теоретическое введение

Командная оболочка — интерфейс взаимодействия пользователя с операционной систе-
мой и программным обеспечением посредством команд.
Midnight Commander (или mc) — псевдографическая командная оболочка для UNIX/Linux
систем. Для запуска mc необходимо в командной строке набрать mc и нажать Enter .
Рабочее пространство mc имеет две панели, отображающие по умолчанию списки
файлов двух каталогов .

# Выполнение лабораторной работы

1. в командной строке задаем команду man mc, чтобы узнать больше про командную оболочку.

![man mc](image/8.jpg){#fig:001 width=70%}

2. создаем файл text.txt, с которым мы будем работа в оболочке

![text.txt](image/1.jpg){#fig:002 width=70%}

3. открываем этот файл в командной строке

![файл](image/2.jpg){#fig:003 width=70%}

4. Начинаем его заполнение

![заполнение](image/3.jpg){#fig:004 width=70%}

5. устанавливаем курсор на нужные нам строчки (у меня это 3 и последняя) и с помощью команды Ctrl+y удаляем эти строки

![удаление строк](image/4.jpg){#fig:005 width=70%}

6. с помощью команды Ins (Insert) вставляем нужный нам кусок или целый текст

![вставка](image/5.jpg){#fig:006 width=70%}

7. Команды Shift+Home/End мы можем оказываеться в начале документа или в конце

![начало документа](image/6.jpg){#fig:007 width=70%}

![конец документа](image/7.jpg){#fig:008 width=70%}

8. Создаем новый файл code.cpp куда я записала код для с++

![код с++](image/9.jpg){#fig:009 width=70%}

9. Открываю файл в командной строке

![открытие файла](image/10.jpg){#fig:010 width=70%}

10. В настройках отключаю подсветку синтаксиса

![отключение](image/11.jpg){#fig:011 width=70%}

11. Итог отключения

![синтаксис](image/12.jpg){#fig:012 width=70%}


# Выводы

Освоили основные возможности командной оболочки Midnight Commander.

# Список литературы{.unnumbered}

::: {#refs}
:::
