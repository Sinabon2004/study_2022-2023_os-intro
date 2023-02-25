---
## Front matter
title: "Отчёт по лабораторной работе №1"
subtitle: "Установка и конфигурация операционной системы на виртуальную машину"
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

Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

# Выполнение лабораторной работы

1. Настроим каталог виртуальных машин (рис. @fig:001).

![Настраиваем каталог](image/1.jpg){#fig:001 width=70%}

2. Запускаем VirtualBox (рис. @fig:002).

![Запуск](image/2.jpg){#fig:002 width=70%}

3. Указываем папку для виртуальных машин (рис. @fig:003).

![Следуем инструкции](image/3.jpg){#fig:003 width=70%}

4. Настроим хост-клавишу (рис. @fig:004).

![Настраиваем](image/4.jpg){#fig:004 width=70%}

5. Запускаем виртуальную машину (рис. @fig:005).

![Запускаем виртуальную машину](image/5.jpg){#fig:005 width=70%}

6. Устанавливаем ОС (рис. @fig:006).

![Установка ОС](image/5,5.jpg){#fig:006 width=70%}

7. Установим необходимые Обновления (рис. @fig:007).

![Следуем инструкциям](image/6.jpg){#fig:007 width=70%}

8. Устанавливаем пакет DKMS (рис. @fig:008).

![Команда для установки](image/7.jpg){#fig:008 width=70%}

9.  Подключаем образ диска дополнений гостевой ОС (рис. @fig:009).

![Подключаем образ диска](image/8.5.jpg){#fig:009 width=70%}

10.  Устанавливаем Pandoc и TeXlive (рис. @fig:010).

![Следуем инструкциям](image/9,5.jpg){#fig:010 width=70%}


# Выводы

Научились создавать виртуальную машину, устанавливать на нее ОС, а также научились устанавливать программное обеспечение при помощи командной строки.

# Список литературы{.unnumbered}

::: {#refs}
:::
