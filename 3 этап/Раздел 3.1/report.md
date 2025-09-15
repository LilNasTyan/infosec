---
# Preamble

## Author

author:
  name: Игнатова Анастасия Александровна
  email: 1132239657@pfur.ru
  affiliation:
    - name: Российский университет дружбы народов
      country: Российская Федерация
      postal-code: 117198
      city: Москва
      address: ул. Миклухо-Маклая, д. 6

## Title

title: "Прохождение внешнего курса stepik 'Основы кибербезопасности'"
subtitle: "3 этап. Защита ПК/телефона"
license: "CC BY"

## Generic options

lang: ru-RU
number-sections: true
toc: true
toc-title: "Содержание"
toc-depth: 2

## Bibliography

bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
format:
  pdf:
    toc: true
    number-sections: true
    colorlinks: false
    toc-depth: 2
    lof: true # List of figures
    lot: true # List of tables
### Document
    documentclass: scrreprt
    papersize: a4
    fontsize: 12pt
    linestretch: 1.5
### Language
    babel-lang: russian
    babel-otherlangs: english
### Fonts
    mainfont: IBM Plex Serif
    romanfont: IBM Plex Serif
    sansfont: IBM Plex Sans
    monofont: IBM Plex Mono
    mathfont: STIX Two Math
    mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
    romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
    sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
    monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
### Biblatex
    cite-method: biblatex
    biblio-style: gost-numeric
    biblatexoptions:
      - backend=biber
      - langhook=extras
      - autolang=other*
      # - parentracker=true
      # - hyperref=auto
      # - language=auto
      # - clearlang=true
      # - citestyle=gost-numeric
### Misc options
    csquotes: true
    indent: true
    header-includes: |
      \usepackage{indentfirst}
      \usepackage{float}
      \floatplacement{figure}{H}

## Crossref customization

crossref:
  lof-title: "Список иллюстраций"
  lot-title: "Список таблиц"
  lol-title: "Листинги"
# figureTitle: "Рис."
# tableTitle: "Таблица"
# listingTitle: "Листинг"
---

# Цель работы

Изучить Шифрование диска, посмотреть лекции и выполнить задания

# Задание

1. Изучить раздел "Шифрование диска"

2. Посмотреть лекцию

3. Выполнить задания

4. Пояснить выбор ответа на задания

# Теоретическое введение

Прохождение курса https://stepik.org/course/111512

# Выполнение лабораторной работы

### Раздел 3.1 "Шифрование диска"

Я посмотрела первую лекцию, изучила новый материал и сделала конспект

![Страница с первой лекцией](image/1.png)
<p align="center">Рис. 1 Просмотр первой лекции</p>


#### Выполнение заданий

1. Приступила к выполнению 1 задания. Я выбрала ответ "Да", потому что зашифровать загрузочный сектор диска можно с помощью технологий вроде Full Disk Encryption (FDE) (например, BitLocker или LUKS), но это требует специальной настройки (например, предзагрузочной аутентификации) для корректной работы системы.

![Выполнение 1 задания](image/2.png)
<p align="center">Рис. 2 Выполнение 1 задания</p>


2. Приступила к выполнению 2 задания. Я выбрала ответ "симметричном шифровании", потому что  шифрование диска (например, BitLocker, LUKS) использует симметричные алгоритмы (AES), так как они обеспечивают высокую скорость шифрования/дешифрования больших объёмов данных, в отличие от асимметричных методов.

![Выполнение 2 задания](image/3.png)
<p align="center">Рис. 3 Выполнение 2 задания</p>


3. Приступила к выполнению 3 задания. Я выбрала ответ "VeraCrypt" и "BitLocker", потому что VeraCrypt, BitLocker и Disk Utility позволяют зашифровать диск, а Wireshark — нет, так как это анализатор трафика.

![Выполнение 3 задания](image/4.png)
<p align="center">Рис. 4 Выполнение 3 задания</p>




# Выводы

Я изучила шифрование диска

# Список литературы

https://stepik.org/course/111512