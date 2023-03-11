---
## Front matter
title: "Отчёт по лабораторной работе №5"
subtitle: "Анализ файловой системы Linux.
Команды для работы с файлами и каталогами
"
author: "Чесноков А.П."

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

Ознакомление с файловой системой Linux, её структурой, именами и содержанием
каталогов. Приобретение практических навыков по применению команд для работы
с файлами и каталогами, по управлению процессами (и работами), по проверке использования диска и обслуживанию файловой системы.


# Выполнение лабораторной работы

1. Копируем из /ect/include любой файл в доомашний каталог и переименовываем+перемещаем его  (рис. @fig:001).

![такими командами](image/1.png){#fig:001 width=70%}

2. Создается объект abc а в нем md файл (рис. @fig:002).

![Потом удаляем файл и создаем ski.plases](image/2.png){#fig:002 width=70%}

3. Удаляем старое, добавляем equipment(рис. @fig:003).

![Создание новых каталогов](image/3.png){#fig:003 width=70%}

4. Вдобавок создаем каталог ero_plans (рис. @fig:004).

![С помощью команды mv](image/4.png){#fig:004 width=70%}

5. Создание файлов и изменение доступа к ним (рис. @fig:005).

![С помощью chmod](image/5.png){#fig:005 width=70%}

6. Смотрим содержимое файла passwd (рис. @fig:006).

![С помощью команды less](image/6.png){#fig:006 width=70%}

7. Создаем file.old и переименовываем его (рис. @fig:007).

![Таким образом](image/7.png){#fig:007 width=70%}

8. Создаем каталог fun и перекидываем его  в play + переименовываем (рис. @fig:008).

![Таким образом](image/8.png)){#fig:008 width=70%}

9. Меняем доступ к директории (рис. @fig:009).

![и потом обновляем доступ](image/9.png){#fig:009 width=70%}

10. Спомощью команды man узнаем значение новых команд (рис. @fig:010).

![Таким образом](image/10.png){#fig:010 width=70%}



# Выводы

Ознакомились с файловой системой Linux и приобрели навыки в использовании различных команд.

