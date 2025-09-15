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
subtitle: "4 этап. Криптография на практике"
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

Изучить цифровую подпись, посмотреть лекции и выполнить задания

# Задание

1. Изучить раздел "Цифровая подпись"

2. Посмотреть лекцию

3. Выполнить задания

4. Пояснить выбор ответа на задания

# Теоретическое введение

Прохождение курса https://stepik.org/course/111512

# Выполнение лабораторной работы

### Раздел 4.2 "Цифровая подпись"

Я посмотрела первую лекцию, изучила новый материал и сделала конспект

![Страница с первой лекцией](image/1.png)
<p align="center">Рис. 1 Просмотр первой лекции</p>


#### Выполнение заданий

1. Приступила к выполнению 1 задания. Я выбрала ответ "протоколам с публичным (или открытым) ключом", потому что электронная цифровая подпись (ЭЦП) использует асимметричную криптографию: секретный ключ для создания подписи и открытый ключ для её проверки, что исключает необходимость общего секрета между сторонами.
![Выполнение 1 задания](image/2.png)
<p align="center">Рис. 2 Выполнение 1 задания</p>


2. Приступила к выполнению 2 задания. Я выбрала ответ "подпись, открытый ключ, сообщение", потому что секретный ключ не используется при проверке — он нужен только для создания подписи.
![Выполнение 2 задания](image/3.png)
<p align="center">Рис. 3 Выполнение 2 задания</p>


3. Приступила к выполнению 3 задания. Я выбрала ответ "конфиденциальность", потому что ЭЦП гарантирует аутентификацию (подтверждение отправителя), целостность (данные не изменены) и неотказ от авторства, но не шифрует данные, поэтому конфиденциальность не обеспечивается.
![Выполнение 3 задания](image/4.png)
<p align="center">Рис. 4 Выполнение 3 задания</p>


4. Приступила к выполнению 4 задания. Я выбрала ответ "усиленная квалифицированная", потому что для отправки налоговой отчётности в ФНС требуется именно усиленная квалифицированная электронная подпись (КЭП), так как она соответствует требованиям законодательства (ФЗ №63) и имеет юридическую силу, равную handwritten подписи.
![Выполнение 4 задания](image/5.png)
<p align="center">Рис. 5 Выполнение 4 задания</p>


5. Приступила к выполнению 5 задания. Я выбрала ответ "в удостоверяющем (сертификационном) центре", потому что квалифицированные сертификаты ЭП выдаются только аккредитованными удостоверяющими центрами (УЦ), соответствующими требованиям Минцифры РФ и ФСБ (например, УЦ СберКорус, Тензор, КРИПТО-ПРО).
![Выполнение 5 задания](image/6.png)
<p align="center">Рис. 6 Выполнение 5 задания</p>

# Выводы

Я изучила цифровую подпись

# Список литературы

https://stepik.org/course/111512