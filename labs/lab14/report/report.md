---
## Front matter
title: "Лабораторная работа №14"
subtitle: "Именованный каналы"
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

Приобретение практических навыков работы с именованными каналами



# Выполнение лабораторной работы

1. создаем текстовый файл MAKEFILE и вписываем туда следующую программу:

![MAKEFILE](image/1.jpg){#fig:001 width=70%}

2. создаем текстовый файл  common.h и вписываем туда следующую программу:

![common.h ](image/2.jpg){#fig:002 width=70%}

3. создаем текстовый файл  client.c и вписываем туда следующую программу:

![client.c ](image/4.jpg){#fig:003 width=70%}

4. создаем текстовый файл  server.c и вписываем туда следующую программу:

![server.c](image/5.jpg){#fig:004 width=70%}

# Выводы

приобрели навыки работы с именованными каналами

# Список литературы{.unnumbered}

::: {#refs}
:::
