---
## Front matter
title: "Индивидуальный проект"
subtitle: "Этап 2"
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

Установить DVWA.

# Выполнение лабораторной работы

После запуска сисетмы клонирую репозиторий DVWA. (рис. [-@fig:001]).

![Клонирование репозитория](image/1.jpg){#fig:001 width=70%}

Переношу директорию DVWA в ```/var/www/html/```.  (рис. [-@fig:002]).

![Перенос диреткории](image/2.jpg){#fig:002 width=70%}

Проверяю, перенеслась ли директория. (рис. [-@fig:003]).

![Проверка](image/3.jpg){#fig:003 width=70%}

Запускаю apache2, чтобы сайт заработал. (рис. [-@fig:004]).

![Запуск apache2](image/4.jpg){#fig:004 width=70%}

Захожу на https:/localhost/, чтобы убедится в том, что наши файлы работают, и попадаю на сайт Acpache2 (рис. [-@fig:005]).

![Сайт с адресом localhost](image/5.jpg){#fig:005 width=70%}

Преходу на страницу https:/localhost/DVWA, чтобы убедится, что фалый DVWA работают. (рис. [-@fig:006]).

![Преход на https:/localhost/DVWA](image/6.jpg){#fig:006 width=70%}

На открывшейся вкладке меня настойчиво попросили отредактировать формат config файла, чтобы его настройки вступили в силу.

Копирую config файл, меняя его формат. (рис. [-@fig:007]).

![Копирование конфиг файла](image/7.jpg){#fig:007 width=70%}

После обновления страницы, попадаю на дальнейшие указания по утсановке DVWA. (рис. [-@fig:008]).

![Обновленная страница](image/8.jpg){#fig:008 width=70%}

Спускаюсь в самый низ страницы и жму кнопку создания базы данных. (рис. [-@fig:009]).

![Кнопка создания базы данных](image/9.jpg){#fig:009 width=70%}

База данных не создается.

Запускаю базу данных и настраиваю MySql, который предустановлел в ОС Kali. Устанавливаю логин, пароль и права на базу данных. (рис. [-@fig:010]).

![Заупск](image/10.jpg){#fig:010 width=70%}

![Настройка MySql](image/11.jpg){#fig:011 width=70%}

![Настройка MySql](image/12.jpg){#fig:012 width=70%}

После настройки проверяю, работают ли установленные логин и пароль. (рис. [-@fig:013]).

![Проверка работы](image/13.jpg){#fig:013 width=70%}

Захожу на сайт еще раз, где меня просят войти в аккаунт. (рис. [-@fig:014]).

![Обновленная страница](image/14.jpg){#fig:014 width=70%}

После захода в аккаунт попадаю на главную страницу DVWA. (рис. [-@fig:015]).

![Главная страница](image/15.jpg){#fig:015 width=70%}

# Выводы

При выполнении этого этапа индивидуального проекта мы установили DVWA.

