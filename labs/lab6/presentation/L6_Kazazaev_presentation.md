---
## Front matter
lang: ru-RU
title: Лабораторная работа № 6
subtitle: Основы информационной безопасности 
author:
  - Казазаев Д. М.
institute:
  - Российский университет дружбы народов, Москва, Россия

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

  * Казазаев Даниил Михайлович
  * Студент бакалавриата
  * Российский университет дружбы народов
  * [1132231427@rudn.ru]
  * <https://github.com/KazazaevDaniil/study_2024-2025_infosec-intro>

:::
::: {.column width="30%"}



:::
::::::::::::::

# Вводная часть

## Цели и задачи

Развитие навыков администрирования ОС Linux. Получение практических навыков в работе с технологией SELinux. Проверка работы SELinux совестно с Apache.

## Материалы и методы

Для выполнения лабораторной работы мы воспользуемся виртуальной машиной Oracle VM Virtual Box.
Лабораторные работы выполняется на домашнем оборудовании.


## Содержание исследования

- Этапы работы
 - 1. Выполнение лабораторной работы.
 
# Выполнение лабораторной работы.

## Выполнение лабораторной работы.

После запуска проверяю, работает-ли SELinux. (рис. 1)

![Информация о SELinux](image/1.png){width=70%}

## Выполнение лабораторной работы.

Проверяю запущен-ли Apache. Так как он не запущен, запускаю его. (рис. 2)

![Проверка и запуск Apache](image/2.png){width=70%}

## Выполнение лабораторной работы.

Смотрю контекст безопасности веб-сервера Apache.(рис. 3)

![Контекст безопасности](image/3.png){width=70%}

## Выполнение лабораторной работы.

![Контекст безопасности](image/4.png){width=70%}

## Выполнение лабораторной работы.

Смотрю состояние переключаетелей SELinux.(рис. 5)

![Состояние переключателей](image/5.png){width=70%}

## Выполнение лабораторной работы.

Смотрю статистику по политеке SELinux.(рис. 6)

![Статистика по политеке](image/6.png){width=70%}

## Выполнение лабораторной работы.

Смотрю, какие типы файлов есть в директории /var/www и права доступа к этим файлам.(рис. 7)

![Контекст файлов в директории](image/7.png){width=70%}

## Выполнение лабораторной работы.

Создаю html файл в /var/www/html.(рис. 8)

![Создание html файла](image/8.png){width=70%}

## Выполнение лабораторной работы.

Переношу простую программу в созданный файл.(рис. 9)

![Код программы](image/9.png){width=70%}

## Выполнение лабораторной работы.

Проверяю контекст нового файла.(рис. 10)

![Контекст нового файла](image/10.png){width=70%}

## Выполнение лабораторной работы.

По умолчанию присваевается контекст вида ```unconfident_u:object_r:httpd_sys_content_t:s0```

## Выполнение лабораторной работы.

Запускаю тестовый файл в веб-сервисе. (рис. 11)

![Запущенный тестовый файл](image/11.png){width=70%}

## Выполнение лабораторной работы.

Изучаю, какие контексты могут быть присвоеный файлам. (рис. 12)

![Справка по контекстам](image/12.png){width=70%}

## Выполнение лабораторной работы.

Детальнее изучаю контекст созданного файла. (рис. 13)

![Контекст созданного файла](image/13.png){width=70%}

## Выполнение лабораторной работы.

Меняю контекст файла на ```samba_share_t```. (рис. 14)

![Меняю контекст](image/14.png){width=70%}

## Выполнение лабораторной работы.

После сменя контекста перезапускаю веб-сервис. При попытке запуска файла выводится ошибка прав доступа. (рис. 15)

![Запуск файла с новым контекстом](image/15.png){width=70%}

## Выполнение лабораторной работы.

Недостаток доступа обусловлен тем, что новый контестк непубличный.

## Выполнение лабораторной работы.

Проверяю права доступа html файла. (рис. 16)

![Проверка прав доступа](image/16.png){width=70%}

## Выполнение лабораторной работы.

В конфиг файле Apache меняю прослушивание TCP-порта на 81. (рис. 17)

![Смена TCP-порта](image/17.png){width=70%}

## Выполнение лабораторной работы.

Добавляю новый TCP-порт. (рис. 18)

![Добавление и проверка](image/18.png){width=70%}

## Выполнение лабораторной работы.

После добавление 81-го порта сайт должен был запуститься, но у меня этого не произошло.

## Выполнение лабораторной работы.

Удаляю новый порт. (рис. 19)

![Удаление и проверка](image/19.png){width=70%}

## Выполнение лабораторной работы.

Удаляю созданный в ходе лабораторной работы html файл. (рис. 20)

![Удаление и проверка](image/20.png){width=70%}

# Вывод

В ходе лабораторной работы я познакомился с администрированием ОС Linux. Полученил практические навыкы в работе с технологией SELinux. Проверил работу SELinux совестно с Apache.

