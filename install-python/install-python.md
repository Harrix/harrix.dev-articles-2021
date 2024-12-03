---
date: 2021-08-03
update: 2024-01-25
categories: [it, program]
tags: [Установка, Python]
author: Anton Sergienko
author-email: anton.b.sergienko@gmail.com
license: CC BY 4.0
license-url: https://github.com/Harrix/harrix.dev/blob/main/LICENSE.md
permalink-source: https://github.com/Harrix/harrix.dev-articles-2021/blob/main/install-python/install-python.md
permalink: https://harrix.dev/ru/articles/2021/install-python/
lang: ru
attribution:
  - {
      author: Python Software Foundation,
      author-site: "https://www.python.org/psf/",
      license: GNU General Public License,
      license-url: "https://en.wikipedia.org/wiki/GNU_General_Public_License",
      permalink: "https://commons.wikimedia.org/wiki/File:Python_logo_and_wordmark.svg",
      permalink-date: 2021-08-01,
      name: Python logo and wordmark.svg,
    }
---

# Установка Python

![Featured image](featured-image.svg)

Рассказываем, как установить Python на Windows.

## Скачивание

Переходим на сайт <https://www.python.org/> и скачиваем версию под Windows:

![Выбор последней версии Python под Windows](img/download_01.png)

_Рисунок 1 — Выбор последней версии Python под Windows_

Но обычно с момента выхода новой версии Python проходит несколько месяцев или год, когда известные и нужные библиотеки адаптируются под новую версию. Поэтому есть смысл установить предыдущую версию Python. То есть, например, на скрине выше последняя версия — 12 (у вас может быть уже другая). Значит стоит выбрать Python 11. Для этого на странице <https://www.python.org/downloads/windows/> находим такой последний релиз Python, в котором присутствует строка `Download Windows installer (64-bit)` и скачиваем этот файл:

![Выбор предыдущей версии Python под Windows](img/download_02.png)

_Рисунок 2 — Выбор предыдущей версии Python под Windows_

---

## Установка

На первом шаге **обязательно** поставьте галочку у пункта `Add Python to PATH`:

![Выбор установки по умолчанию](img/install_01.png)

_Рисунок 3 — Выбор установки по умолчанию_

![Выбор установки по умолчанию](img/install_02.png)

_Рисунок 4 — Выбор установки по умолчанию_

Также возможен пункт на удаление ограничение на длину пути к файлу в Windows:

![Снятие ограничение на длину пути](img/install_03.png)

_Рисунок 5 — Снятие ограничение на длину пути_

![Конец установки](img/install_04.png)

_Рисунок 6 — Конец установки_

## Проверка Python

Эта часть необязательная, но желательно проверить, как вы установили Python.

Запустите командную строку `cmd` или любой другой терминал (например, `Windows Terminal`). Это можно сделать многими способами. Можно, например, через поиск:

![Запуск командной строки в Windows 10](img/cmd_old.png)

_Рисунок 7 — Запуск командной строки в Windows 10_

![Запуск командной строки в Windows 11](img/cmd_01.png)

_Рисунок 7 — Запуск командной строки в Windows 11_

Введите команду `python` и нажмите `Enter`, чтобы запустить интерпретатор Python:

![Запуск интерпретатора Python](img/cmd_02.png)

_Рисунок 8 — Запуск интерпретатора Python_

Введите какой-нибудь код, например, `1+1` и нажмите `Enter`. Если выведется 2, то всё отлично и у вас Python установился правильно:

![Пример арифметического действия](img/cmd_03.png)

_Рисунок 9 — Пример арифметического действия_

После этого командную строку можно закрывать.

Кстати, если вы хотите выйти из интерпретатора Python, чтобы продолжать работать в командной строке, но нажмите `Ctrl` + `Z`, а затем `Enter`.

Иногда у вас могут возникать проблемы из-за не обновленного `pip`, который можно обновить в консоли через:

```powershell
python -m pip install --upgrade pip
```
