---
## Front matter
title: "Отчёт по 2 этапу персонального проекта"
subtitle: "Погдотовка ПО и шаблон сайта"
author: "Чесноков Артемий Павлович НПИбд-02-22"

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

Кастомизировать наш сайт


# Выполнение лабораторной работы

1. В /home/kali/work/blog/content/ меняем наши текстовые данные + в /home/kali/work/blog/content/authors/admin/ меняем аватар (рис. @fig:001).

![Получаем такой вид сайта](image/1.png){#fig:001 width=70%}

2. Изменяем данные под себя, меняем блок интересы и блок образование (рис. @fig:002).

![Таким образом](image/2.png){#fig:002 width=70%}

3. Создаем запись в каталоге post (рис. @fig:003).

![ заполняем его данными о деятельности в прошлой неделе](image/3.png){#fig:003 width=70%}

4. Аналогично создаем статью по системе контроля версий git (рис. @fig:004).

![Так выглядит на сайте](image/4.png){#fig:004 width=70%}




# Выводы

Добавили на сайт собственные данные (интересы, работы и тд) + поставили собственный профиль

# Список литературы{.unnumbered}

::: {#refs}
:::
