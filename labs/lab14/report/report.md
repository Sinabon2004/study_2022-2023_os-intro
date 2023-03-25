---
## Front matter
title: "Шаблон отчёта по лабораторной работе"
subtitle: "Простейший вариант"
author: "Дмитрий Сергеевич Кулябов"

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

Освоение основных возможностей командной оболочки Midnight Commander. Приобретение навыков практической работы по просмотру каталогов и файлов; манипуляций
с ними.




# Выполнение лабораторной работы

1. Ознакомились с mc  и открыли (рис. @fig:001).

![man mc /   mc](image/1.png){#fig:001 width=70%}

2. Ознакомились с интерфейсом (рис. @fig:002).

![Ознакомились с основными клавишами](image/2.png){#fig:002 width=70%}

3. Скопировали произвольный файл в другую директорию(рис. @fig:003).

![Таким образом](image/3.png){#fig:003 width=70%}

4. Перенесли произвольный файл в другую директорию (рис. @fig:004).

![Таким образом](image/4.png){#fig:004 width=70%}

5. Отредактировали произвольный файл (рис. @fig:005).

![Попробовали все горячие клавишы](image/5.png){#fig:005 width=70%}

6. Сделали поиск файлов по их имени (рис. @fig:006).

![С помощью mс](image/6.png){#fig:006 width=70%}

7. Создали текстовый файл по заданию (рис. @fig:007).

![Таким образом](image/7.png){#fig:007 width=70%}

8. Попробовали все команды из задания (рис. @fig:008).

![Таким образом](image/8.png){#fig:008 width=70%}


# Выводы

В ходе выполнения лабораторной работы мы ознакомились с MC и научились с его помощью редактировать файлы

