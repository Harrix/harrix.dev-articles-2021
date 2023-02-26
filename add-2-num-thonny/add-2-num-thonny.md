---
date: 2021-08-23
categories: [it, programming]
tags: [Python, Сложение двух чисел, Установка]
author: Anton Sergienko
author-email: anton.b.sergienko@gmail.com
license: CC BY 4.0
license-url: https://github.com/Harrix/harrix.dev/blob/main/LICENSE.md
permalink-source: https://github.com/Harrix/harrix.dev-blog-2021/blob/main/add-2-num-thonny/add-2-num-thonny.md
permalink: https://harrix.dev/ru/blog/2021/add-2-num-thonny/
lang: ru
attribution:
- {author: Python Software Foundation, author-site: 'https://www.python.org/psf/',
  license: GNU General Public License, license-url: 'https://en.wikipedia.org/wiki/GNU_General_Public_License',
  permalink: 'https://commons.wikimedia.org/wiki/File:Python_logo_and_wordmark.svg',
  permalink-date: 2021-08-01, name: Python logo and wordmark.svg}
---

# Сложение двух чисел в Thonny на Python

![Featured image](featured-image.svg)

В статье рассказывается как создать консольное приложения сложения двух чисел в Thonny на Python.

## Установка программы

Вначале надо установить Python себе на компьютер. Смотрите статью [Установка Python](https://github.com/Harrix/harrix.dev-blog-2021/blob/main/install-python/install-python.md) <!-- https://harrix.dev/ru/blog/2021/install-python/ -->.

После этого на сайте <https://thonny.org/> скачиваем установщик:

![Скачивание установщика](img/download.png)

_Рисунок 1 — Скачивание установщика_

---

**Установка Thonny** <!-- !details -->

![Выбор установки для всех пользователей](img/install-mode.png)

_Рисунок 2 — Выбор установки для всех пользователей_

![Начальное окно установки](img/install_01.png)

_Рисунок 3 — Начальное окно установки_

![Соглашение с условиями](img/install_02.png)

_Рисунок 4 — Соглашение с условиями_

![Выбор пути установки программы](img/install_03.png)

_Рисунок 5 — Выбор пути установки программы_

![Выбор расположения в меню Пуск](img/install_04.png)

_Рисунок 6 — Выбор расположения в меню Пуск_

![Создание ярлыка на рабочем столе](img/install_05.png)

_Рисунок 7 — Создание ярлыка на рабочем столе_

![Окно перед процессом установки](img/install_06.png)

_Рисунок 8 — Окно перед процессом установки_

![Процесс установки](img/install_07.png)

_Рисунок 9 — Процесс установки_

![Окончание установки](img/install_08.png)

_Рисунок 10 — Окончание установки_

При запуске Thonny вас спросят про язык интерфейса (русский там есть тоже, но не советую его выбирать):

![Настройка программы](img/install_09.png)

_Рисунок 11 — Настройка программы_

![Открытая программа Thonny](img/thonny.png)

_Рисунок 12 — Открытая программа Thonny_

---

## Создание проекта

Открываем программу `Thonny`

Сразу уже есть пустой файл, в котором можно писать, но если нужно, то создать пустой файл можно через `File` → `New`:

![Создание пустого файла](img/new-project.png)

_Рисунок 13 — Создание пустого файла_

## Написание кода

Напишем программу сложения двух чисел:

```python
a = int(input("Введите первое число "))
b = int(input("Введите второе число "))
c = a + b
print("Сумма =", c)
```

![Код программы](img/code.png)

_Рисунок 14 — Код программы_

## Запуск программы

Так как мы еще не сохраняли наш файл, то сделаем это:

![Сохранение файла](img/save_01.png)

_Рисунок 15 — Сохранение файла_

Выберите папку и название вашего файла. Для данного примера я файл назвал `add2num.py`:

![Выбор имени сохраняемого файла](img/save_02.png)

_Рисунок 16 — Выбор имени сохраняемого файла_

Скомпилируйте код и запустите его:

![Компиляция и запуск программы](img/run.png)

_Рисунок 17 — Компиляция и запуск программы_

После запустится программа, где мы можете ввести два числа и посмотреть на результат их суммирования:

![Запущенное приложение](img/result_01.png)

_Рисунок 18 — Запущенное приложение_

![Результат выполнения программы](img/result_02.png)

_Рисунок 19 — Результат выполнения программы_
