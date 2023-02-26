---
date: 2021-08-23
categories: [it, programming]
tags: [Python, Сложение двух чисел, Установка]
author: Anton Sergienko
author-email: anton.b.sergienko@gmail.com
license: CC BY 4.0
license-url: https://github.com/Harrix/harrix.dev/blob/main/LICENSE.md
permalink-source: https://github.com/Harrix/harrix.dev-blog-2021/blob/main/add-2-num-pycharm/add-2-num-pycharm.md
permalink: https://harrix.dev/ru/blog/2021/add-2-num-pycharm/
lang: ru
attribution:
- {author: Python Software Foundation, author-site: 'https://www.python.org/psf/',
  license: GNU General Public License, license-url: 'https://en.wikipedia.org/wiki/GNU_General_Public_License',
  permalink: 'https://commons.wikimedia.org/wiki/File:Python_logo_and_wordmark.svg',
  permalink-date: 2021-08-01, name: Python logo and wordmark.svg}
---

# Сложение двух чисел в PyCharm

![Featured image](featured-image.svg)

В статье рассказывается как создать консольное приложения сложения двух чисел в PyCharm на Python.

## Установка программы

Вначале надо установить Python себе на компьютер. Смотрите статью [Установка Python](https://github.com/Harrix/harrix.dev-blog-2021/blob/main/install-python/install-python.md) <!-- https://harrix.dev/ru/blog/2021/install-python/ -->.

Далее устанавливаем сам PyCharm по статье [Установка PyCharm](https://github.com/Harrix/harrix.dev-blog-2021/blob/main/install-pycharm/install-pycharm.md) <!-- https://harrix.dev/ru/blog/2021/install-pycharm/ -->.

## Создание проекта

Открываем программу `PyCharm` и идем `File` → `New`:

![Создание нового проекта](img/new-project_01.png)

_Рисунок 1 — Создание нового проекта_

О параметрах создаваемого проекта рассказано в статье [Установка PyCharm](https://github.com/Harrix/harrix.dev-blog-2021/blob/main/install-pycharm/install-pycharm.md) <!-- https://harrix.dev/ru/blog/2021/install-pycharm/ -->. Так что тут просто скажу, что нужно указать месторасположение нового проекта и убедиться, что `Base interpreter` не горит красным и не пустой:

![Настройка проекта](img/new-project_02.png)

_Рисунок 2 — Настройка проекта_

Если у вас был открыт до этого другой проект в PyCharm, то программа спросит закрыть старый проект и открыть новый (`This Window`) или же оставить открытым старый и открыть еще один экземпляр PyCharm с новым проектом (`New Window`). Например, нам старый проект не нужен:

![Закрытие старого проекта](img/new-project_03.png)

_Рисунок 3 — Закрытие старого проекта_

![Созданный пустой проект](img/new-project_04.png)

_Рисунок 4 — Созданный пустой проект_

## Написание кода

Напишем программу сложения двух чисел, удалив весь код из файла `main.py`:

```python
a = int(input("Введите первое число "))
b = int(input("Введите второе число "))
c = a + b
print("Сумма =", c)
```

![Код программы](img/code.png)

_Рисунок 5 — Код программы_

## Запуск программы

Чтобы запустить код, щелкните правой кнопкой по коду и в появившемся меню выберите команду `Run 'main'`:

![Компиляция и запуск программы](img/run.png)

_Рисунок 6 — Компиляция и запуск программы_

После запустится программа, где мы можете ввести два числа и посмотреть на результат их суммирования:

![Запущенное приложение](img/result_01.png)

_Рисунок 7 — Запущенное приложение_

![Результат выполнения программы](img/result_02.png)

_Рисунок 8 — Результат выполнения программы_
