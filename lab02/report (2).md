---
## Front matter
title: "Отчет о выполнении лабораторной работы"
subtitle: "Лабораторная работа №2"
author: "Филипьева Ксения Дмитриевна"

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
linestretch: 1.3
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

Провести работу с атрибутами файлов

# Задание

Провести работу с атрибутами файлов и научиться ими оперирвать

# Выполнение лабораторной работы

Создание пользователя (рис. [-@fig:1]).

![Создание пользователя](image/kl2s2.png){#fig:1 width=100%}

Выдача пароля пользователю (рис. [-@fig:2]).

![Выдача пароля](image/kl2s3.png){#fig:2 width=100%}

Вход под новым пользователем (рис. [-@fig:3]).

![Вход](image/kl2s4.png){#fig:3 width=100%}

Определение текущей директории (рис. [-@fig:4]).

![Текущая дериктория](image/kl2s5.png){#fig:4 width=100%}

Проверка кем является пользователь (рис. [-@fig:5]).

![кто_я](image/kl2s6.png){#fig:5 width=100%}

Проверка групп пользователя (рис. [-@fig:6]).

![Группы](image/kl2s7.png){#fig:6 width=100%}

Еще проверка (рис. [-@fig:7]).

![Группы](image/kl2s8.png){#fig:7 width=100%}

Содержимое файла /etc/passwd (рис. [-@fig:8]).

![паролики](image/kl2s9.png){#fig:8 width=100%}

Соответствие отображенных групп разными командами (рис. [-@fig:9]).

![соответствие](image/kl2s10.png){#fig:9 width=100%}

Проверка прав пользователей к дирректории home (рис. [-@fig:10]).

![проверка](image/kl2s11.png){#fig:10 width=100%}

Проверка прав пользователей к дирректории home (рис. [-@fig:11]).

![проверка](image/kl2s12.png){#fig:11 width=100%}

Создание новой дирректории (рис. [-@fig:12]).

![создание](image/kl2s13.png){#fig:12 width=100%}

Обнуление атрибутов и проверка (рис. [-@fig:13]).

![обнуление](image/kl2s14.png){#fig:13 width=100%}

Попытка создать файл безуспешна (рис. [-@fig:14]).

![фейл](image/kl2s2.png){#fig:14 width=100%}


# Вывод

В данной лабораторной работе мы научились работать с атрибутами.
