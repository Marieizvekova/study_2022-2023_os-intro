---
## Front matter
title: "Лабораторная работа №8"
subtitle: "Текстовый редактор vi"
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

Познакомиться с операционной системой Linux. Получить практические навыки рабо-
ты с редактором vi, установленным по умолчанию практически во всех дистрибутивах.


# Теоретическое введение

1. Создаем катало lab06, в которой мы будет выполнять лабораторную работу

![рис.1](image/1.jpg){#fig:001 width=70%}

2. Создаем файл text.txt, в котором изучаем опции редактора. Добавляем текст.

![text.txt](image/2.jpg){#fig:002 width=70%}

![текст](image/3.jpg){#fig:003 width=70%}

0 - переход в начало строки
$ - переход в конец строки
G - переход в конец файла
a - вставить текст после курсора
А - вставить текст в конец строки
i - вставить текст перед кусором
о - вставить строку под курсором
О - вставить строку над курсором
х - удалить один символ в буфер
dw - удалить одно слово в буфер
u - отменить последнее изменение
. - повторить последнее изменение
Y - скопировать строку в буфер
:w - записать измененный текст в файл, не выходя из редактора
:q - выйти из редактора
:wq - записать изменения и выйти

# Выполнение лабораторной работы

1. создаем файл hello.sh и открываем его в редакторе

![Название рисунка](image/4.jpg){#fig:004 width=70%}

2. вводим следующий текст

![текст](image/5.jpg){#fig:005 width=70%}

3. записываем файл и выходим из редактора

![запись файла](image/6.jpg){#fig:006 width=70%}

4. делаем файл исполняемым

![команда исполнения](image/7.jpg){#fig:007 width=70%}

5. открываем вновь файл в редакторе, стираем слово LOCAL в 4 строке с помощью команды dw

![удаление](image/8.jpg){#fig:008 width=70%}

6. вставляем слово local

![вставка](image/9.jpg){#fig:009 width=70%}

7. Копируем предпоследнюю строчку с помощью команды Y. Вставляем ее в самый конец текста

![добавление](image/10.jpg){#fig:010 width=70%}

8. удаляем строчку с помощью команды dd

![удаление](image/11.jpg){#fig:011 width=70%}

9.  записываем файл и выходим из редактора

![запись файла](image/12.jpg){#fig:012 width=70%}

# Выводы

Изучили редактор vi и проверили его опции

# Список литературы{.unnumbered}

::: {#refs}
:::
