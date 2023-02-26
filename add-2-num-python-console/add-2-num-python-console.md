---
date: 2021-08-23
categories: [it, programming]
tags: [Python, Сложение двух чисел, Установка]
author: Anton Sergienko
author-email: anton.b.sergienko@gmail.com
license: CC BY 4.0
license-url: https://github.com/Harrix/harrix.dev/blob/main/LICENSE.md
permalink-source: https://github.com/Harrix/harrix.dev-blog-2021/blob/main/add-2-num-python-console/add-2-num-python-console.md
permalink: https://harrix.dev/ru/blog/2021/add-2-num-python-console/
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

# Сложение двух чисел в Python через консоль и блокнот

![Featured image](featured-image.svg)

Для работы с Python после его установки можно не устанавливать никаких других программ (PyCharm, VSCode, Wing и др.), а воспользоваться обычным блокнотом.

## Установка программы

Вначале надо установить Python себе на компьютер. Смотрите статью [Установка Python](https://github.com/Harrix/harrix.dev-blog-2021/blob/main/install-python/install-python.md) <!-- https://harrix.dev/ru/blog/2021/install-python/ -->.

## Создание проекта

Вместо навороченных сред программирования откроем обычный блокнот:

![Блокнот](img/notepad.png)

_Рисунок 1 — Блокнот_

## Написание кода

Напишем программу сложения двух чисел:

```python
a = int(input("Введите первое число "))
b = int(input("Введите второе число "))
c = a + b
print("Сумма =", c)
```

![Код программы](img/code.png)

_Рисунок 2 — Код программы_

Сохраним файл куда-нибудь. Я для примера сохранил под именем `add2num.py` в папке `C:\projects`:

![Сохранение файла](img/save_01.png)

_Рисунок 3 — Сохранение файла_

![Выбор места хранения и названия файла](img/save_02.png)

_Рисунок 4 — Выбор места хранения и названия файла_

То есть полный путь к файлу у меня такой `C:\projects\add2num.py`.

## Запуск программы

Нам нужна командная строка, терминал или что-нибудь в этом роде. Покажу, как открыть обычную командную строку через поиск в Windows:

![Открытие командной строки через поиск](img/cmd_01.png)

_Рисунок 5 — Открытие командной строки через поиск_

![Открытая командная строка](img/cmd_02.png)

_Рисунок 6 — Открытая командная строка_

Теперь просто пропишем такую команду и нажмем `Enter`:

```console
python C:\projects\add2num.py
```

![Запуск Python скрипта](img/run.png)

_Рисунок 7 — Запуск Python скрипта_

Если у вас путь к сохраненному файлу с кодом другой, то поменяйте в примере вызова этот путь. Если вдруг не сработает, то попробуйте такой вариант:

```console
python3 C:\projects\add2num.py
```

После запустится программа, где мы можете ввести два числа и посмотреть на результат их суммирования:

![Запущенное приложение](img/result_01.png)

_Рисунок 8 — Запущенное приложение_

![Результат выполнения программы](img/result_02.png)

_Рисунок 9 — Результат выполнения программы_
