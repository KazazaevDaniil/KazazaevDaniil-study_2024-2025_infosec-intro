---
## Front matter
title: "Индивидуальный проект"
subtitle: "Этап 1"
author: "Казазаев Даниил Михайлович"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

Установить ОС Kali Linux на VirtualBox.

# Задание

Установить ОС Kali Linux на VirtualBox.

# Выполнение лабораторной работы

Создаю новую виртуальную машину для индивидуального проекта (рис. [-@fig:001]).

![Создание новой виртуальной машины](image/1.png){#fig:001 width=70%}

После запуска начинаю установку ОС  (рис. [-@fig:002]).

![Нfчало установки ОС](image/2.png){#fig:002 width=70%}

Выбираю язык ОС (рис. [-@fig:003]).

![Настройка](image/3.png){#fig:003 width=70%}

Жду окончания загрузки (рис. [-@fig:004]).

![Загрузка](image/4.png){#fig:004 width=70%}

Настраиваю пользователя (рис. [-@fig:005]).

![Настройка пользователя](image/5.png){#fig:005 width=70%}

Вибираю программное обеспечение (рис. [-@fig:006]).

![Выбор програмного обеспечения](image/6.png){#fig:006 width=70%}

Жду окончания еще одной загрузки (рис. [-@fig:007]).

![Загрузка](image/7.png){#fig:007 width=70%}

После загрузки перезагрузил систему и зашел в созданного мной пользователя (рис. [-@fig:008]).

![Добро пожаловть](image/8.png){#fig:008 width=70%}

# Выводы

При выполнении этого этапа индивидуального проекта мы установили ОС Kali Linux.

