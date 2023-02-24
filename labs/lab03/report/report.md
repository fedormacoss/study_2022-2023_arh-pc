---
## Front matter
title: "отчёт по лабораторной работе №3"
author: "Архипов Фёдор Александрович"

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

изучение основного синтаксиса языка разметки МД

# Задание

изучение основного синтаксиса языка разметки МД

# Теоретическое введение


Чтобы создать заголовок, используйте знак ( # ), например:

Чтобы задать для текста полужирное начертание, заключите его в двойные звездочки:

Чтобы задать для текста курсивное начертание, заключите его в одинарные звездочки:

Чтобы задать для текста полужирное и курсивное начертание, заключите его в тройные
звездочки:

Блоки цитирования создаются с помощью символа >:

Неупорядоченный (маркированный) список можно отформатировать с помощью звездочек или тире:


# Выполнение лабораторной работы
Чтобы создать заголовок, используйте знак ( # ), например:
![](image/Screenshot_40.png){#fig:001 width=70%}

Чтобы задать для текста полужирное начертание, заключите его в двойные звездочки:

Чтобы задать для текста курсивное начертание, заключите его в одинарные звездочки:

Чтобы задать для текста полужирное и курсивное начертание, заключите его в тройные
звездочки:

Блоки цитирования создаются с помощью символа >:

![](image/Screenshot_41.png){#fig:001 width=70%}
![](image/Screenshot_42.png){#fig:001 width=70%}

Внутритекстовые формулы делаются аналогично формулам LaTeX. Например, формула
sin2(𝑥) + cos2(𝑥) = 1

![](image/Screenshot_43.png){#fig:001 width=70%}

# Выводы

в ходе лабораторной работы был повторно изучен язык разметки МД

# Список литературы{.unnumbered}

::: {#refs}
:::
