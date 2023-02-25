---
## Front matter
title: "Отчёт по 1 этапу персонального проекта"
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

Установить и разоьраться в ПО, создать рабочий шаблон сайта для дальнейшей разработки индивидуального проекта


# Выполнение лабораторной работы

1. Переходим по ссылке (рис. @fig:001).

![Переходим по ссылке в ТУИС](image/1.png){#fig:001 width=70%}

2. Скачиваем hugo (рис. @fig:002).

![Выбираем указанный файл](image/2.png){#fig:002 width=70%}

3. Переносим программу в указанное место + создаем каталог bin (рис. @fig:003).

![Делаем следующие действия](image/3.png){#fig:003 width=70%}

4. Переходим по ссылке для шаблона для сайта (рис. @fig:004).

![Нажимаем use this template](image/4.png){#fig:004 width=70%}

5. Клонируем репозиторий (рис. @fig:005).

![Выполняем указанные команды](image/5.png){#fig:005 width=70%}

6. Создаем сервер (рис. @fig:006).

![Выполняем указанную команду](image/6.png){#fig:006 width=70%}

7. Удаляем demo часть сайта в шаблоне (рис. @fig:007).

![Заходим в md и редактируем](image/7.png){#fig:007 width=70%}

8. Создаем репозиторий четко по рисунку (рис. @fig:008).

![Используем свое имя аккаунта](image/8.png){#fig:008 width=70%}

9. Проверяем наличие репозитория blog (рис. @fig:009).

![Вводим следующие команды](image/9.png){#fig:009 width=70%}

10. После создания именного репозитория, пушим его в гитхаб (рис. @fig:010).

![Выполняем следующие действия](image/10.png){#fig:001 width=70%}

11. Убираем папку public и делаем submodule (рис. @fig:011).

![Вписываем в строку следующую команду](image/11.png){#fig:001 width=70%}

12. Проверяем привязку и высылаем на репозиторий в github (рис. @fig:012).

![Вводим следующие команды](image/12.png){#fig:001 width=70%}

13. Сайт готов и работает исправно (рис. @fig:013).

![Копируем ссылку и вставляем её в строку браузера](image/13.png){#fig:001 width=70%}


# Выводы

Создали рабочий сайт используя шаблон, научились пользоваться всеми необходимыми инструментами, которые понадобятся в дальнейшем

# Список литературы{.unnumbered}

::: {#refs}
:::
