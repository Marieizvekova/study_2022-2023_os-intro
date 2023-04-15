---
## Front matter
title: "Лабораторная работа №10"
subtitle: "Основы программирования в оболочке ОС UNIX/Linux."
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

Изучить основы программирования в оболочке ОС UNIX/Linux. Научиться писать
небольшие командные файлы.


# Теоретическое введение

Командный процессор (командная оболочка, интерпретатор команд shell) — это про-
грамма, позволяющая пользователю взаимодействовать с операционной системой
компьютера. В операционных системах типа UNIX/Linux наиболее часто используются
следующие реализации командных оболочек:
– оболочка Борна (Bourne shell или sh) — стандартная командная оболочка UNIX/Linux,
содержащая базовый, но при этом полный набор функций;
– С-оболочка (или csh) — надстройка на оболочкой Борна, использующая С-подобный
синтаксис команд с возможностью сохранения истории выполнения команд;
– оболочка Корна (или ksh) — напоминает оболочку С, но операторы управления програм-
мой совместимы с операторами оболочки Борна;
– BASH — сокращение от Bourne Again Shell (опять оболочка Борна), в основе своей сов-
мещает свойства оболочек С и Корна (разработка компании Free Software Foundation).
POSIX (Portable Operating System Interface for Computer Environments) — набор стандартов
описания интерфейсов взаимодействия операционной системы и прикладных программ.
Стандарты POSIX разработаны комитетом IEEE (Institute of Electrical and Electronics
Engineers) для обеспечения совместимости различных UNIX/Linux-подобных опера-
ционных систем и переносимости прикладных программ на уровне исходного кода.
POSIX-совместимые оболочки разработаны на базе оболочки Корна.
Рассмотрим основные элементы программирования в оболочке bash. 

# Выполнение лабораторной работы

1. создаем папку backup, куда мы будем копировать первый файл code1.sh

![backup](image/1.jpg){#fig:001 width=70%}

В файле code1.sh пишем следующий код, который создаст нам директорию с сжатой папкой и поместит туда наш первый файл с кодом

![code1.sh](image/2.jpg){#fig:002 width=70%}

![папка backup](image/10.jpg){#fig:003 width=70%}

![наш файл с кодом](image/12.jpg){#fig:004 width=70%}

чтобы у нас появился этот файл в нашей директории, мы забиваем следующую команду
 
 ![команда bash](image/3.jpg){#fig:005 width=70%}
 
 2. для вывода следующих числе мы пишем следующий код с циклом (чтобы он считывал и выводил наши числа) в наш новый файл с тем же расширением
 
 ![code 2](image/4.jpg){#fig:006 width=70%}
 
 пишем команду bash для вывода действия кода на экран
 
 ![вывод на экран](image/5.jpg){#fig:007 width=70%}
 
 
3. для считывания файла и дериктории мы пишем следующую программу, которая будет выводить на экран информацию о каталоге и о ее доступе

![code 3](image/6.jpg){#fig:008 width=70%}

с помощью команды bash выводим действие команды на экран

![вывод третьего кода](image/7.jpg){#fig:009 width=70%}

4. для определения сколько файлов определенного формата находятся в нашем каталоге мы пишем в следующую команду


![code 4](image/8.jpg){#fig:010 width=70%}

с помощью команды bash выводим действие команды на экран

![вывод четвертого кода](image/9.jpg){#fig:011 width=70%}

# Выводы

Изучили основы программирования в оболочке ОС UNIX/Linux. Научились писать
небольшие командные файлы.

# Список литературы{.unnumbered}

::: {#refs}
:::
