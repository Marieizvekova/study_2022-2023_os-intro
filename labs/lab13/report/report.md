---
## Front matter
title: "Лабораторная работа 13"
subtitle: "Средства, применяемые при
разработке программного обеспечения в ОС типа UNIX/Linux"
author: "Извекова Мария"

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

Приобрести простейшие навыки разработки, анализа, тестирования и отладки при-
ложений в ОС типа UNIX/Linux на примере создания на языке программирования
С калькулятора с простейшими функциями


# Выполнение лабораторной работы

1. создаем новую папку lab_prog и в нем три файла: calculate.h, calculate.c, main.c.

![создание файлов](image/1.jpg){#fig:001 width=70%}

2. в первый файл мы вставляем программу для реализаций функций калькулятора


![calculate.c](image/2.jpg){#fig:002 width=70%}

3. во второй файл мы вставляем программу для формата вызова функции

![calculate.h](image/3.jpg){#fig:003 width=70%}

4. в третий файл мы вставляем программу для реализации интерфейса

![main.c](image/4.jpg){#fig:004 width=70%}

5. далее с помощью следующих команд мы проводим компиляцию

![компиляция ](image/5.jpg){#fig:005 width=70%}

6. далее создаем новый файл makefile и вставляем следующую команду

![makefile](image/6.jpg){#fig:006 width=70%}

7. запускаем программу с помощью отладчика gdb ./calcul и команды run

![запуск](image/7.jpg){#fig:007 width=70%}

8. с помощью команды list можем посмотреть весь код программы в терминале

![list](image/8.jpg){#fig:008 width=70%}


# Выводы

Мы приобрели простейшие навыки разработки, анализа, тестирования и отладки при-
ложений в ОС типа UNIX/Linux на примере создания на языке программирования
С калькулятора с простейшими функциями

# Список литературы{.unnumbered}

::: {#refs}
:::
