---
## Front matter
lang: ru-RU
title: Лабораторная работа №5
subtitle: Администрирование локальных сетей
author:
  - Дикач А.О.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 11 марта 2025

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

Получить основные навыки по настройке VLAN на коммутаторах сети.

# Выполнение лабораторной работы

##  Используя последовательность из текста лабораторной работы провожу конфигурацию Trunk-порта на коммутатору msk-donskaya-aodikach-sw-01

![Настройка Trunk-портов](image/1.png){#fig:001 width=60%}

##  Используя последовательность из текста лабораторной работы провожу конфигурацию Trunk-порта на коммутатору msk-pavlovskaya-aodikach-sw-1

![Настройка Trunk-портов](image/2.png){#fig:002 width=60%}

##  Прописываю конфигурацию диапазонов портов и конфигурации VTP msk-donskaya-aodikach-sw-01

![Настройка коммутаторов](image/3.png){#fig:003 width=60%}

##

![Настройка коммутаторов](image/4.png){#fig:004 width=60%}

##  Провожу настройку конфигурации Trunk-портов, VTP и диапазона портов для msk-donskaya-aodikach-sw-02

![Настройка Trunk-портов](image/5.png){#fig:005 width=60%}

##

![Настройка VTP и диапазона портов](image/6.png){#fig:006 width=60%}

##  Провожу настройку конфигурации Trunk-портов, VTP и диапазона портов для msk-donskaya-aodikach-sw-03

![Настройка коммутатора](image/7.png){#fig:007 width=70%}

##  Провожу настройку конфигурации Trunk-портов, VTP и диапазона портов для msk-donskaya-aodikach-sw-04

![Настройка коммутатора](image/8.png){#fig:008 width=70%}

##  

![Настройка коммутатора](image/9.png){#fig:009 width=70%}

##  Проверяю состояние сети

![Построенная и настроенная сеть](image/12.png){#fig:012 width=70%}

##  Проверяю результат проделанной работы на dep-donskaya-aodikach-1 и пробую пропинговать устройство из другой сети. Неудачно

![Проверка корректности](image/10.png){#fig:010 width=30%}

![Неудачная попытка](image/11.png){#fig:011 width=30%}

##  Запускаю симуляцию. В сети на одной улице пакеты коммуницируют друг с другом верно, однако при попытке передать пакеты на другую улицу вылезает ошибка

![Запуск симуляции](image/13.png){#fig:013 width=30%}

![Разбор одного из отправленных пакетов](image/14.png){#fig:014 width=30%}

## Вывод

Получила основные навыки по настройке VLAN на коммутаторах сети.

