---
## Front matter
title: "Третий этап проекта"
subtitle: "Добавление к сайту достижения."
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


1. Список достижений.
   -    Добавить информацию о навыках (Skills).
   -    Добавить информацию об опыте (Experience).
   -    Добавить информацию о достижениях (Accomplishments).
2. Сделать пост по прошедшей неделе.
3. Добавить пост на тему по выбору:
   -    Легковесные языки разметки.
   -    Языки разметки. LaTeX.
   -    Язык разметки Markdown.

# Выполнение третьего этапа

1. Открываем папку marie-blog, открываем терминал и забиваем hugo server, чтобы можно было вносить изменения на сайт.                                                                                  
                                                                                    
                                                                                                   ![hugo server](image/1.jpg) {#fig:001 width=70%}
                                                                                                   
                                                                                                   
2. Открываем в этом папке маркдауновский файл, изменяем в нем пункты Skills, Experience, Accomplishments. 


![Experience](image/9.jpg) {#fig:002 width=70%}

![Accomplishments](image/10.jpg) {#fig:003 width=70%}

![Skills](image/11.jpg) {#fig:004 width=70%}

3.  Переходим в папку post, создаем дополнительные папку markdown, post 2, для создания дополнительных страниц нашего сайте, где мы пишем новую информацию

![новые папки](image/6.jpg) {#fig:005 width=70%}

4. Добавляем туда маркдауновские файлы и редактируем их под себя

5. Добавляем пост по выбору, я написала про разметку markdown

![markdown](image/8.jpg) {#fig:006 width=70%}

6. Добавляем пост по предыдущей неделе

![пост](image/7.jpg) {#fig:007 width=70%}

7. После добавлений изменений возвращаемся в терминал, переходим в папку блог, открываем терминал, набираем hugo и пишем слудающий команды: git add ., git commit, git push. Переходим в папку public и вбиваем эти же команды

8. Переходим на сайт и любуемся изменениями

![Skills](image/5.jpg) {#fig:008 width=70%}

![Experience](image/4.jpg) {#fig:009 width=70%}

![Accomplishments](image/3.jpg) {#fig:010 width=70%}

![markdown](image/2.jpg) {#fig:011 width=70%}

![last week](image/1.jpg) {#fig:012 width=70%}

# Выводы

На этом этапе я добавила больше информации о себе, а также научилась создавать новые страницы для сайта

# Список литературы{.unnumbered}

::: {#refs}
:::
