---
## Front matter
title: "Лабораторная работа №9"
subtitle: "Текстовой редактор emacs"
author: "Извеклва Мария Петровна"

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

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs

# Теоретическое введение

Буфер — объект, представляющий какой-либо текст
Фрейм соответствует окну в обычном понимании этого слова. Каждый фрейм содержит область вывода и одно или несколько окон Emacs.
Окно — прямоугольная область фрейма, отображающая один из буферов.
Область вывода — одна или несколько строк внизу фрейма, в которой Emacs выводит различные сообщения, а также запрашивает подтверждения и дополнительную информацию от пользователя
Минибуфер используется для ввода дополнительной информации и всегда отображается в области вывода.
Точка вставки — место вставки (удаления) данных в буфере.

# Выполнение лабораторной работы

1. с помощью команды emacs открываем редактор.

![открытие редактора](image/1.jpg){#fig:001 width=70%}

2. Создаем файла lab07  с расширением sh.

![создание файла](image/2.jpg){#fig:002 width=70%}

3. с помощью этого редактора вбиваем в этот файл след текст: 

![текст](image/2.jpg){#fig:003 width=70%}

4. с помощью клавишей ctrl и alt и дополнительных функций мы проделываем след процедуры: выделение, удаление, вставка

![удаление строки с помощью команды ctrl-k](image/7.jpg){#fig:004 width=70%}

![вставка строки ctrl-y](image/8.jpg){#fig:005 width=70%}

5. Можно проделывтаь опции с самим файлом. С помощью команд ctrl-h f и ctrl-h v мы можем увидеть информацию по функции и переменной

![информация по функции](image/4.jpg){#fig:006 width=70%}

![информация по переменной](image/5.jpg){#fig:007 width=70%}

6. С помощью команды ctrl-b ctrl-x мы выводим список активных буферов

![списки буферов](image/9.jpg){#fig:008 width=70%}

7. с помощью команды ctrl-x мы переключаем окно на активный буфер

![активный буфер](image/10.jpg){#fig:009 width=70%}

8. с помощью команды ctrl- x 3 ctrl- x 2 мы делим окно на 3 части

![разделение окна](image/11.jpg){#fig:010 width=70%}

9. как в пункте 7 мы переключаем окна на активный буфер

![активный буфер](image/12.jpg){#fig:011 width=70%}

10. с помощью команды ctrl-x ctrl-c мы сохраняем файл и выходим из редактора

![выход с сохраненим](image/6.jpg){#fig:012 width=70%}


# Контрольные вопросы
1. Усиленная программа для работы с текстом
2. Большое количество команд с дополнительными опциями, которые работают совместно. Для одного действия нам нужно соединить две команды
3. Окно, выводящее результат текста (ошибки, подсказки)
4. чтобы поделить окно на 2 части нужно набрать команду ctrl- x 3
5. редактор vi мне показался удобнее, так как он легче в использовании и освоении.

# Выводы

Ознакомились с текстовым редактором emacs и освоили некоторые функции и команды этого редактора.

# Список литературы{.unnumbered}

::: {#refs}
:::
