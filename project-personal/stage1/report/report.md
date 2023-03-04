---
## Front matter
title: "Отчет по 1 этапу индивидуального проекта."
subtitle: "Размещение на Github pages заготовки для персонального сайта"
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

Размещение заготовки сайта на github.

# Выполнение работы

1)Я установил hugo, разархивировал и поместил в папку bin.

![Установка hugo](/home/amnazarov/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/0-1.png){#fig:001 width=70%}

2) В терминале клонируем репозиторий с сайта (предварительно добавив новый репозиторий)

![Клонирование репозитория](/home/amnazarov/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/0-2.png){#fig:002 width=70%}

3) У нас создалось несколько новый папок, после проверки работоспособности, удаляем каталог "public".

![Удаление каталога public](/home/amnazarov/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/0-3.png){#fig:005 width=70%}

4) Cоздаем локальную ссылку, с помощью команды ~/bin/hugo server.

![Создание сайта](home/amnazarov/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/0-4.png){#fig:006 width=70%}

5) Cоздаем новый пустой репозиторий на сайте github и клонируем его на компьютер.

![Клонирование пустого репозитория](home/amnazarov/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/0-5.png){#fig:009 width=70%}

6) Далее в новом репозитории создаем основную ветку "main" и в ней создаем еще один текстовый файл "README.md".

![Создание ветки main](/home/amnazarov/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/0-6.png){#fig:011 width=70%}

7) Отправляем созданную ветку обратно на сайт github, вместо команды "git push", я использовал команду "git push origin main", чтобы отправить именно основную ветку.

![Отправка изменений на github](/home/amnazarov/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/0-7.png){#fig:012 width=70%}

8) После этого объединяем репозитории и с помощью команды "git push origin main" отправляем все изменения на сайт github.

![Изменения в репозитории](/home/amnazarov/work/study/2022-2023/Операционные системы/os-intro/project-personal/stage1/report/image/0-8.png){#fig:018 width=70%}



# Выводы

Я разместил заготовки для сайта на платформе github.

# Список литературы{.unnumbered}

::: {#refs}
:::
