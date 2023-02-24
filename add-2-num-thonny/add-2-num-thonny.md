---
date: 2021-08-23
categories: [it, programming]
tags: [Python, Сложение двух чисел, Установка]
author: Anton Sergienko
author-email: anton.b.sergienko@gmail.com
license: CC BY 4.0
license-url: https://github.com/Harrix/harrix.dev/blob/main/LICENSE.md
url-src: https://github.com/Harrix/harrix.dev-blog-2021/blob/main/add-2-num-thonny/add-2-num-thonny.md
---

# Сложение двух чисел в Thonny на Python

В статье рассказывается как создать консольное приложения сложения двух чисел в Thonny на Python.

## Установка программы

Вначале надо установить Python себе на компьютер. Смотрите статью [Установка Python](https://github.com/Harrix/harrix.dev-blog-2021/blob/main/install-python/install-python.md).

После этого на сайте <https://thonny.org/> скачиваем установщик:

![Скачивание установщика](img/download.png)

---

**Установка Thonny** <!-- !details -->

![Выбор установки для всех пользователей](img/install-mode.png)

![Начальное окно установки](img/install_01.png)

![Соглашение с условиями](img/install_02.png)

![Выбор пути установки программы](img/install_03.png)

![Выбор расположения в меню Пуск](img/install_04.png)

![Создание ярлыка на рабочем столе](img/install_05.png)

![Окно перед процессом установки](img/install_06.png)

![Процесс установки](img/install_07.png)

![Окончание установки](img/install_08.png)

При запуске Thonny вас спросят про язык интерфейса (русский там есть тоже, но не советую его выбирать):

![Настройка программы](img/install_09.png)

![Открытая программа Thonny](img/thonny.png)

---

## Создание проекта

Открываем программу `Thonny`

Сразу уже есть пустой файл, в котором можно писать, но если нужно, то создать пустой файл можно через `File` → `New`:

![Создание пустого файла](img/new-project.png)

## Написание кода

Напишем программу сложения двух чисел:

```python
a = int(input("Введите первое число "))
b = int(input("Введите второе число "))
c = a + b
print("Сумма =", c)
```

![Код программы](img/code.png)

## Запуск программы

Так как мы еще не сохраняли наш файл, то сделаем это:

![Сохранение файла](img/save_01.png)

Выберите папку и название вашего файла. Для данного примера я файл назвал `add2num.py`:

![Выбор имени сохраняемого файла](img/save_02.png)

Скомпилируйте код и запустите его:

![Компиляция и запуск программы](img/run.png)

После запустится программа, где мы можете ввести два числа и посмотреть на результат их суммирования:

![Запущенное приложение](img/result_01.png)

![Результат выполнения программы](img/result_02.png)
