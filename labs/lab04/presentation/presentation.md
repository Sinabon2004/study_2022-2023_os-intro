---
## Front matter
lang: ru-RU
title: Структура научной презентации
subtitle: Простейший шаблон
author:
  - Кулябов Д. С.
institute:
  - Российский университет дружбы народов, Москва, Россия
  - Объединённый институт ядерных исследований, Дубна, Россия
date: 01 января 1970

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Чесноков артемий павлович
  * НПИбд-02-22, Студент
  * Российский университет дружбы народов
  * [1132222012@pfur.ru](1132222012@pfur.ru)
  * <https://Sinabon2004.github.io>

:::
::: {.column width="30%"}



:::
::::::::::::::


## Цели и задачи

- Научиться пользоваться командной строкой в Unix




##  Узнаем полнуы путь до домашнего каталога (рис. @fig:001).

![С помощью команды pwd](image/1.png){#fig:001 width=70%}

## Смотрим, что содержится в папке tmp (рис. @fig:002).

![Содержимое папки tmp](image/2.png){#fig:002 width=70%}

##  Узнаем подробности содержимого папки tmp (рис. @fig:003).

![Следуя этим командам](image/3.png){#fig:003 width=70%}

## Смотрим наличие папки cron в указанном каталоге (рис. @fig:004).

![Следуем инструкциям](image/4.png){#fig:004 width=70%}

##  В домашнем каталоге создаем указанные папки (рис. @fig:005).

![Создаем](image/5.png){#fig:005 width=70%}

##  Создаем папки и удаляем их одной строкой (рис. @fig:006).

![Таким образом](image/6.png){#fig:006 width=70%}

## Удаляем папку morefun(рис. @fig:007).

![С помощью этой команды](image/7.png){#fig:007 width=70%}

##  Смотрим документацию к команде ls (рис. @fig:008).

![man ls](image/8.png){#fig:008 width=70%}

##  Смотрим полное  содержимое каталога (рис. @fig:009).

![ls -a](image/9.png){#fig:009 width=70%}

##  Сортируем по дате загрузки содержимое (рис. @fig:010).

![ls -c -lt](image/10.png){#fig:010 width=70%}

##  Смотрим документацию ко всем командам (рис. @fig:011).

![Следуем указаниям](image/11.png){#fig:011 width=70%}

## Смотрим историю командной строки (рис. @fig:012).

![С помощью этой команды](image/12.png){#fig:012 width=70%}

## Вызываем команду из истории действий (рис. @fig:013).

![!-n](image/13.png){#fig:013 width=70%}

## Результаты

- УРА!!!! МЫ НАУЧИЛИСЬ ПОЛЬЗОВАТЬСЯ НЕКОТОРЫЕМИ КОМАНДАМИ В системе UNIX





