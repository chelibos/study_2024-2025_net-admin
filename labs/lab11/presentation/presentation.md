---
## Front matter
lang: ru-RU
title: Лабораторная работа №11
subtitle: Администрирование локальных сетей
author:
  - Дикач А.О.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 

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

# Информация

## Докладчик

  * Дикач Анна Олеговна
  * НПИбд-01-22 (1132222009)
  * Российский университет дружбы народов
  * <https://github.com/chelibos?tab=repositories>

## Цель работы

Провести подготовительные мероприятия по подключению локальной сети организации к Интернету.

# Выполнение лабораторной работы

##  Строю схему подсоединения локальной сети к Интернету, модельные сети провайдера в сети Интернет (схемы L1, L2, L3), а также распределение IP-адресов 

![L1](image/L1.png){#fig:001 width=40%}

##

![L2](image/L2.png){#fig:002 width=70%}

##

![L3](image/L3.png){#fig:003 width=40%}

![Распределение ip-адресов модельного Интернета](image/L4.png){#fig:004 width=50%}

##  Размещаю на схеме проекта 4 медиаконвертера, 2 коммутатора, маршрутизатор и 4 сервера, присваиваю им названия 

![Размещение](image/1.png){#fig:005 width=70%}

## В физической рабочей области добавляю 2 здания - Internet и Provider. Переношу всё необходимое оборудывание в соответсвующие здания

![Размещение в здании Internet](image/2.png){#fig:006 width=20%}

![Размещение в здании Provider](image/3.png){#fig:007 width=20%}

## На медиаконвертерах заменяю модули на PT-REPEATER- NM-1FFE и PT-REPEATER-NM-1CFE для подключения витой пары по технологии Fast Ethernet и оптоволокна соответственно

![Изменение настроек](image/4.png){#fig:008 width=70%}

## Провожу соединение объектов согласно скорректированной схеме

![Соединение](image/5.png){#fig:009 width=70%}

##  Прописываю IP-адреса серверам согласно таблице распределения

![Настройка www.yandex.ru](image/7.png){#fig:011 width=30%}

![Настройка www.yandex.ru](image/8.png){#fig:012 width=30%}

## 

![Настройка stud.rudn.university](image/9.png){#fig:013 width=30%}

![Настройка esystem.pfur.ru](image/10.png){#fig:014 width=30%}

## 

![Настройка www.rudn.ru](image/11.png){#fig:015 width=70%}

## Прописываю свдеения о серверах на DNS-сервер сети "Донская" 

![Прописанные сервера](image/12.png){#fig:016 width=70%}

## Вывод

Провела подготовительные мероприятия по подключению локальной сети организации к интернету.

