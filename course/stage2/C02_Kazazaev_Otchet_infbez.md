---
## Front matter
title: "Отчет по второму этапу внешнего курса"
subtitle: "Дисциплина: основы информационнной безопасности"
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
lot: false # List of tables
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

Внешний кур состоит из трех этапов.

# Этап первый

Первый этап курса состоит из 5 частей:

1. Шифрование диска
2. Пароли
3. Фишинг
4. Вирусы
5. Безопасность мессенджеров

# Выполнение первого этапа внешнего курса.

## Шифрование диска

Загрузочный сектор диска можно зашифровать. (рис. [-@fig:001])

![Первый вопрос](image/1.jpg){#fig:001 width=70%}

Симметричное шифрование - основа шифрования диска. (рис. [-@fig:002])

![Второй вопрос](image/2.jpg){#fig:002 width=70%}

BitLocker - шифратор ОС Windwos, VeraCrypt - утилита для шифрования. (рис. [-@fig:003])

![Третий вопрос](image/3.jpg){#fig:003 width=70%}

# Пароли

Хороший пароль тот, который является нестандартым и его сложно подобрать. (рис. [-@fig:004])

![Первый вопрос](image/4.jpg){#fig:004 width=70%}

Лучше всего хранить пароли в менеджерах паролей, так как они обеспечены большей степенью защиты. (рис. [-@fig:005])

![Второй вопрос](image/5.jpg){#fig:005 width=70%}

Капчк нужна для предотвращения автоматизированных атак, которые могут подобрать пароль автоматически.(рис. [-@fig:006])

![Третий вопрос](image/6.jpg){#fig:006 width=70%}

Хеширование необхлодимо, чтобы защитить пароль, а не хранить его на сервере в открытом виде.(рис. [-@fig:007])

![Четвертый вопрос](image/7.jpg){#fig:007 width=70%}

Если злоумышленник получил доступ к серверу, метот соли не поможет от перебора паролей.(рис. [-@fig:008])

![Пятый вопрос](image/8.jpg){#fig:008 width=70%}

Все перечисленные методы хороши для защиты пароля.(рис. [-@fig:009])

![Шестой вопрос](image/9.jpg){#fig:009 width=70%}


## Фишинг

Фишинговыми ссылками являются те, у которых домене есть непонятные симфолы или слова.(рис. [-@fig:010])

![Первый вопрос](image/10.jpg){#fig:010 width=70%}

Фишинговая ссылка может прийти от знакомого пользователя, так как сущетсвует метод Спуфинга, когда злоумышленник подделывает адрес. (рис. [-@fig:011])

![Второй вопрос](image/11.jpg){#fig:011 width=70%}

# Вирусы

Спуфинг - подмена адреса отправителя. (рис. [-@fig:012])

![Первый вопрос](image/12.jpg){#fig:012 width=70%}

Вирус Троян - вирус, который маскеруется под обычный файл, но внутри у него вредоносный код. (рис. [-@fig:013])

![Второй вопрос](image/13.jpg){#fig:013 width=70%}

# Безопасность мессенджерей

Ключ шифрования Signal формируется на этапе генерации сообщения со стороны-отправителя. (рис. [-@fig:014])

![Первый вопрос](image/14.jpg){#fig:014 width=70%}

Суть сквозного шифрования в передачи сообщения по ущлам связи в зашифрованном виде. (рис. [-@fig:015])

![Второй вопрос](image/15.jpg){#fig:015 width=70%}

# Вывод

Выполнен второй этап внешнего курса
