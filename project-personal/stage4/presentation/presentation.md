---
## Front matter
lang: ru-RU
title: Отчет по 4 этапу персонального проекта
subtitle: Основы информационной безопасности
author:
  - Ничипорова Е.Д.
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
---

# Цель работы

Научиться тестированию веб-приложений с помощью сканера nikto

# Задание

Использование nikto.

# Выполнение лабораторной работы

Чтобы работать с nikto, необходимо подготовить веб-приложение, которое будем сканировать. Это будет DVWA. Для этого запустила apache2 (рис. [-@fig:001]).

![Запуск apache2](image/1.jpg){#fig:001 width=70%}

Ввожу в адресной строке браузера адрес DVWA, перехожу в режим выбора уровня безопасности, ставлю минимальный (необязательно, nikto при обычном сканировании для режима impossible и low выдаст одинаковые потенциальные уязвимости, что логично, ведь они остаются, но изменяется сложность, с которой их можно использовать) (рис. [-@fig:002]).

![Запуск DVWA](image/2.jpg){#fig:002 width=70%}
# Выполнение лабораторной работы
Запускаю nikto (рис. [-@fig:003]).

![Запуск nikto](image/3.jpg){#fig:003 width=70%}

Проверить веб-приложение можно, введя его полный URL и не вводя порт, попробовала просканировать так (рис. [-@fig:004]).

![Название рисунка](image/4.jpg){#fig:004 width=70%}
# Выполнение лабораторной работы
Затем попробовала просканировать введя адрес хоста и адрес порта, результаты незначительно отличаются (рис. [-@fig:005]).

![Название рисунка](image/5.jpg){#fig:005 width=70%}

# Выводы

Научилась использовать сканер nikto для тестирования веб-приложений

