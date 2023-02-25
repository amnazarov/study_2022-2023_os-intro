---
## Front matter
title: "Отчет лабораторная работа №2"
subtitle: "НММбд-02-22"
author: "Назаров Алексей Михайлович"

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

Познакомиться с системой git, а также с сайтом github.

# Задание

 Настроить GitHub, создать репозиторий и каталог курса.

# Выполнение лабораторной работы

1.Создадим профиль на github

![Создание гитхаба](image/2-1.png){#fig:001 width=70%}

2.Настроим гит.

![Настройка](image/2-2.png){#fig:002 width=70%}

3.Созданим SSH key

![Создание ключа](image/2-5.png){#fig:003 width=70%}

4.Занесем на гитхаб

![Занесение SSH ключа на гитхпб](image/2-4.png){#fig:004 width=70%}

5.Создадим ключ pgp

![Создание ключа gpg](image/2-6.png){#fig:005 width=70%}

6.Вывод следа pgp ключа и копируем его на гитхаб

![Вывод следа pgp ключа](image/2-8.png){#fig:006 width=70%}

7.Создаем новый репозиторий

![Создание репозитория](image/2-11.png){#fig:007 width=70%}

8.Копируем новый репозиторий на наше устройство

![Скопируем репозиторий на ПК](image/2-12.png){#fig:007 width=70%}


# Выводы

В данной лабораторной работе мы познакомились с гитхабои и каталогами, а также настроили их

# Список литературы{.unnumbered}

::: {#refs}
:::
