---
date: 2021-08-23
categories: [it, programming]
tags: [Python, Сложение двух чисел, Установка]
author: Anton Sergienko
author-email: anton.b.sergienko@gmail.com
license: CC BY 4.0
license-url: https://github.com/Harrix/harrix.dev/blob/main/LICENSE.md
permalink-source: https://github.com/Harrix/harrix.dev-blog-2021/blob/main/add-2-num-python-idle/add-2-num-python-idle.md
permalink: https://harrix.dev/ru/blog/2021/add-2-num-python-idle/
lang: ru
attribution:
  - author: Python Software Foundation
    author-site: https://www.python.org/psf/
    license: GNU General Public License
    license-url: https://en.wikipedia.org/wiki/GNU_General_Public_License
    permalink: https://commons.wikimedia.org/wiki/File:Python_logo_and_wordmark.svg
    permalink-date: 2021-08-01
    name: Python logo and wordmark.svg
---

# Сложение двух чисел в Python IDLE

![Featured image](featured-image.svg)

Для работы с Python после его установки можно не устанавливать никаких других программ (PyCharm, VSCode, Wing и др.), а воспользоваться тем, что идет с Python.

## Установка программы

Вначале надо установить Python себе на компьютер. Смотрите статью [Установка Python](https://github.com/Harrix/harrix.dev-blog-2021/blob/main/install-python/install-python.md) <!-- https://harrix.dev/ru/blog/2021/install-python/ -->.

При установке Python через официальный установщик в систему устанавливается простая среда разработки IDLE, в которой можно полноценно работать. Ей можно найти через поиск:

![Поиск IDLE](img/search.png)

_Рисунок 1 — Поиск IDLE_

Либо, например, запустить программу `pythonw.exe` с параметром пути к файлу `idle.pyw`. У меня это так выглядит:

```console
C:\Python39\pythonw.exe "C:\Python39\Lib\idlelib\idle.pyw"
```

Но через поиск, конечно, куда проще.

Вот открытая среда IDLE:

![Открытая среда IDLE](img/idle_01.png)

_Рисунок 2 — Открытая среда IDLE_

## Создание проекта

В программе сразу открывается Python интерпретатор, где можно сразу как производить вычисления примеров:

![Пример арифметических действий](img/idle_02.png)

_Рисунок 3 — Пример арифметических действий_

А можно записывать построчно нужный код:

![Пример сложения двух чисел](img/idle_03.png)

_Рисунок 4 — Пример сложения двух чисел_

Но мы хотим писать код в отдельном файле, который и будем запускать. Поэтому идем `File` → `New File`:

![Пункт меню для создания нового файла](img/new-project_01.png)

_Рисунок 5 — Пункт меню для создания нового файла_

![Созданный новый файл](img/new-project_02.png)

_Рисунок 6 — Созданный новый файл_

## Написание кода

Напишем программу сложения двух чисел:

```python
a = int(input("Введите первое число "))
b = int(input("Введите второе число "))
c = a + b
print("Сумма =", c)
```

![Код программы](img/code.png)

_Рисунок 7 — Код программы_

Сохраним файл куда-нибудь. Я для примера сохранил под именем `add2num.py`:

![Сохранение файла](img/save_01.png)

_Рисунок 8 — Сохранение файла_

![Выбор места хранения и названия файла](img/save_02.png)

_Рисунок 9 — Выбор места хранения и названия файла_

## Запуск программы

Чтобы запустить код идем `Run` → `Run Module`:

![Компиляция и запуск программы](img/run.png)

_Рисунок 10 — Компиляция и запуск программы_

После запустится программа, где мы можете ввести два числа и посмотреть на результат их суммирования:

![Запущенное приложение](img/result_01.png)

_Рисунок 11 — Запущенное приложение_

![Результат выполнения программы](img/result_02.png)

_Рисунок 12 — Результат выполнения программы_
