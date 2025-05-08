---
## Front matter
title: "Лабораторная работа №"
subtitle: "Админимстрирование локальных сетей"
author: "Дикач Анна Олеговна НПИбд-01-22"

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


# Выполнение лабораторной работы

[@wiki]

1.  (рис. [-@fig:00]).

![](image/.png){#fig:00 width=70%}


# Вывод



# Ответ на вопросы

1. Пример настройки статической маршрутизации

Маршрутизатор 1:

bash
ip route 192.168.2.0 255.255.255.0 192.168.1.2
Маршрутизатор 2:

bash
ip route 192.168.1.0 255.255.255.0 192.168.1.1

2. Обращение между VLAN

Трафик идет на шлюз (L3-коммутатор/маршрутизатор).
Шлюз маршрутизирует трафик в другой VLAN.

3. Проверка маршрута

bash
ping 192.168.2.10  # с устройства из VLAN 1
traceroute 192.168.2.10  # путь трафика

4. Просмотр таблицы маршрутизации

bash
show ip route  # Cisco
ip route show  # Linux
route print    # Windows

# Список литературы {.unnumbered}

::: {#refs}
:::

