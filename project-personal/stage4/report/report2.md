---
## Front matter
title: "Второй этап проекта"
subtitle: "Загрузка страниц сайта"
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

Научить дополнять любую информацию на сайт через сервер hugo.

# Задание



1. Список добавляемых данных.
- Разместить фотографию владельца сайта.
- Разместить краткое описание владельца сайта (Biography).
- Добавить информацию об интересах (Interests).
- Добавить информацию от образовании (Education).
2. Сделать пост по прошедшей неделе.
3. Добавить пост на тему: Управление версиями. Git.

# Выполнение лабораторной работы

1. Добавляем свою фотография на собственный сайт. 

![добавляем фотография в папку blog_marie/content/author/admin](image/1.jpg){#fig:001 width=70%}

![с помощью команд git и опций add, commit, push мы загружаем фотография на сайт](image/2.jpg){#fig:001 width=70%}

![переходим в папку public и проделываем те же команды](image/3.jpg){#fig:001 width=70%}

2. Переход на сайт

![сначала строим ветку сайта](image/4.jpg){#fig:001 width=70%}

![переходим на сайт local, где отслеживаем изменения](image/5.jpg){#fig:001 width=70%}

3. Добавляем информация о себе

![в папке blog_marie/content/author/admin редактируем следующий файл](image/6.jpg){#fig:001 width=70%}

![Здесь пишем некоторую информацию о себе](image/7.jpg){#fig:001 width=70%}

4. Пишем образовательный пост. Переходим в папку blog_marie/content/post/getting-started. Редактируем маркадауновский файл индекс

![переходим на сайт local, где отслеживаем изменения](image/8.jpg){#fig:001 width=70%}

![что вышло](image/9.jpg){#fig:001 width=70%}

5. Пишем пост о прошлой неделе. Переходим в папку blog_marie/content/post/jupiter. Редактируем маркадауновский файл индекс. 

![мои изменения](image/10.jpg){#fig:001 width=70%}

![что вышло](image/11.jpg){#fig:001 width=70%}

6. Обновление сайта. 

![с помощью команд git и опций add, commit, push мы загружаем информацию на сайт](image/12.jpg){#fig:001 width=70%}

![переходим в папку public и проделываем те же команды](image/13.jpg){#fig:001 width=70%}

![любуемся обновлениями](image/15.jpg){#fig:001 width=70%}

# Выводы

Научились загружать информацию на собственный сайт

# Список литературы{.unnumbered}

::: {#refs}
:::
