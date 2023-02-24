---
date: 2021-08-23
categories: [it, programming]
tags: [Python, Сложение двух чисел, Установка]
author: Anton Sergienko
author-email: anton.b.sergienko@gmail.com
license: CC BY 4.0
license-url: https://github.com/Harrix/harrix.dev/blob/main/LICENSE.md
---

# Сложение двух чисел в PyCharm

В статье рассказывается как создать консольное приложения сложения двух чисел в PyCharm на Python.

## Установка программы

Вначале надо установить Python себе на компьютер. Смотрите статью [Установка Python](https://github.com/Harrix/harrix.dev-blog-2021/blob/main/install-python/install-python.md).

Далее устанавливаем сам PyCharm по статье [Установка PyCharm](https://github.com/Harrix/harrix.dev-blog-2021/blob/main/install-pycharm/install-pycharm.md).

## Создание проекта

Открываем программу `PyCharm` и идем `File` → `New`:

![Создание нового проекта](img/new-project_01.png)

О параметрах создаваемого проекта рассказано в статье [Установка PyCharm](https://github.com/Harrix/harrix.dev-blog-2021/blob/main/install-pycharm/install-pycharm.md). Так что тут просто скажу, что нужно указать месторасположение нового проекта и убедиться, что `Base interpreter` не горит красным и не пустой:

![Настройка проекта](img/new-project_02.png)

Если у вас был открыт до этого другой проект в PyCharm, то программа спросит закрыть старый проект и открыть новый (`This Window`) или же оставить открытым старый и открыть еще один экземпляр PyCharm с новым проектом (`New Window`). Например, нам старый проект не нужен:

![Закрытие старого проекта](img/new-project_03.png)

![Созданный пустой проект](img/new-project_04.png)

## Написание кода

Напишем программу сложения двух чисел, удалив весь код из файла `main.py`:

```python
a = int(input("Введите первое число "))
b = int(input("Введите второе число "))
c = a + b
print("Сумма =", c)
```

![Код программы](img/code.png)

## Запуск программы

Чтобы запустить код, щелкните правой кнопкой по коду и в появившемся меню выберите команду `Run 'main'`:

![Компиляция и запуск программы](img/run.png)

После запустится программа, где мы можете ввести два числа и посмотреть на результат их суммирования:

![Запущенное приложение](img/result_01.png)

![Результат выполнения программы](img/result_02.png)
