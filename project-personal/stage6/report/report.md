---
## Front matter
title: "Четвертый этап проекта"
subtitle: "Добавить к сайту ссылки на научные и библиометрические ресурсы."
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


# Задание

1. Зарегистрироваться на соответствующих ресурсах и разместить на них ссылки на сайте:
        eLibrary : https://elibrary.ru/;
        Google Scholar : https://scholar.google.com/;
        ORCID : https://orcid.org/;
        Mendeley : https://www.mendeley.com/;
        ResearchGate : https://www.researchgate.net/;
        Academia.edu : https://www.academia.edu/;
        arXiv : https://arxiv.org/;
        github : https://github.com/.
2. Сделать пост по прошедшей неделе.
3. Добавить пост на тему по выбору:
        Оформление отчёта.
        Создание презентаций.
        Работа с библиографией.



# Выполнение лабораторной работы

1. Регистрируемся на сайтах и в папке admin/authors изменяем маркдауновский файл, добавив туда эти сайты


![рис. 1](image/1.jpg){#fig:001 width=70%}

Как это выглядит на сайте

![рис. 2](image/6.jpg){#fig:002 width=70%}

2. Пишем пост по прошедшей неделе, создав новую папку с маркдауновским файлом.  Тем самым  мы добавлем новую страницу на сайт

![рис. 3](image/2.jpg){#fig:003 width=70%}

Как это выглядит на сайте

![рис. 4](image/5.jpg){#fig:004 width=70%}

3. Пишем пост на любую тему. Реализуем его также, как и с постом про прошедшую неделю

![рис. 5](image/3.jpg){#fig:005 width=70%}
 
Как это выглядит на сайте

![рис. 6](image/4.jpg){#fig:006 width=70%}


# Список литературы{.unnumbered}

::: {#refs}
:::
