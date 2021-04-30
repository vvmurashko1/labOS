---
# Front matter
lang: ru-RU
title: "Отчёт по лабораторной работе №4"
subtitle: "Знакомство с операционной системой Linux"
author: "Мурашко Виктория Витальевна"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Познакомиться с операционной системой Linux,получить практические навыки работы с консолью и некоторыми графическими менеджерами рабочих столов операционной системы.

# Выполнение лабораторной работы

1. Я ознакомилась с теоретическим материалом.
2. Я загрузила компьютер.
3. Я перешла на текстовую консоль. На моём компьютере доступно 6 текстовых консолей.
4. Я перемещаюсь между текстовыми консолями с помощью сочетания клавиш Cltr+Alt с одной из функциональных клавиш (F1-F6).
5. Я зарегистрировалась в текстовой консоли операционной системы. Я использовала логин vvmurashko1. При вводе пароля никакие символы не отображаются.
6. Я завершила консольный сеанс с помощью комбинации клавиш Ctrl+Alt+F7.
7. Для перехода из текстового режима в графический необходимо нажать комбинацию клавиш Ctrl+Alt+FNN.
8. Я ознакомилась с менеджером рабочих столов. Менеджер рабочих столов GNOME.
9. Я поочерёдно зарегистрировалась в разных графических менеджерах рабочих столов (GNOME,KDE,XFCE) и оконных менеджерах (Openbox).

GNOME
![](image/04.png){ #fig:001 width=70% }

Plasma (KDE)
![](image/01.png){ #fig:001 width=70% }

XFCE
![](image/03.png){ #fig:001 width=70% }

Openbox
![](image/02.png){ #fig:001 width=70% }

На моём компьютере установлены следующие графические менеджеры: GNOME, XSession, awesome и т.д.

10. Я изучила список установленных программ и запустила поочерёдно браузер, текстовой редактор, текстовой процессор, эмулятор консоли. Названия программ: браузер Mozilla Firefox, текстовый редактор Geany, текстовый процессор Microsoft Word, эмулятор консоли Konsole.

# Выводы

Я познакомилась с операционной системой Linux, получила практические навыки работы с консолью и некоторыми графическими менеджерами рабочих столов операционной системы.
