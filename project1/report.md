---
## Front matter
title: "Отчет о выполнении лабораторной работы"
subtitle: "Проект. Этап 1"
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

Выполнить первичную установку операционной системы.

# Задание

Установить и настроить операционную систему Kali linux.

# Выполнение лабораторной работы

Создание виртуальной машины (рис. [-@fig:1]).

![Виртуальная машина](image/kp1s1.png){#fig:1 width=100%}

Настройка языка (рис. [-@fig:2]).

![Настройка языка](image/kp1s2.png){#fig:2 width=100%}

Настройка клавиатуры (рис. [-@fig:3]).

![Настройка клавиатуры](image/kp1s3.png){#fig:3 width=100%}

Назначение имени компьютера (рис. [-@fig:4]).

![Имя в сети](image/kp1s4.png){#fig:4 width=100%}

Создание учетной записи (рис. [-@fig:5]).

![Новый пользователь](image/kp1s5.png){#fig:5 width=100%}

Настройка учетной записи (рис. [-@fig:6]).

![Новый пользователь](image/kp1s6.png){#fig:6 width=100%}

Установка пароля (рис. [-@fig:7]).

![Пароль](image/kp1s7.png){#fig:7 width=100%}

Разметка дисков (рис. [-@fig:8]).

![Разметка дисков](image/kp1s8.png){#fig:8 width=100%}

Разметка дисков (рис. [-@fig:9]).

![Разметка дисков](image/kp1s9.png){#fig:9 width=100%}

Разметка дисков (рис. [-@fig:10]).

![Разметка дисков](image/kp1s10.png){#fig:10 width=100%}

Процесс установки системы (рис. [-@fig:11]).

![Установка ОС](image/kp1s11.png){#fig:11 width=100%}

Установка предложенного ПО (рис. [-@fig:12]).

![Установка ПО](image/kp1s12.png){#fig:12 width=100%}

Вход в настроенного пользователя (рис. [-@fig:13]).

![Вход](image/kp1s13.png){#fig:13 width=100%}

Работоспособность ОС (рис. [-@fig:14]).

![Работоспособность](image/kp1s14.png){#fig:14 width=100%}

# Вывод

В данном этапе индивидуального проекта мы установили и настроили ОС.
