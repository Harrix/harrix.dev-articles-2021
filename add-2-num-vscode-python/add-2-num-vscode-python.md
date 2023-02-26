---
date: 2021-08-27
categories: [it, programming]
tags: [Python, Сложение двух чисел, Установка]
author: Anton Sergienko
author-email: anton.b.sergienko@gmail.com
license: CC BY 4.0
license-url: https://github.com/Harrix/harrix.dev/blob/main/LICENSE.md
permalink-source: https://github.com/Harrix/harrix.dev-blog-2021/blob/main/add-2-num-vscode-python/add-2-num-vscode-python.md
permalink: https://harrix.dev/ru/blog/2021/add-2-num-vscode-python/
lang: ru
attribution:
- {author: Python Software Foundation, author-site: 'https://www.python.org/psf/',
  license: GNU General Public License, license-url: 'https://en.wikipedia.org/wiki/GNU_General_Public_License',
  permalink: 'https://commons.wikimedia.org/wiki/File:Python_logo_and_wordmark.svg',
  permalink-date: 2021-08-01, name: Python logo and wordmark.svg}
- {author: Microsoft Corporation, author-site: 'https://www.microsoft.com/', license: Public
    domain, license-url: 'https://en.wikipedia.org/wiki/Public_domain', permalink: 'https://commons.wikimedia.org/wiki/File:Visual_Studio_Code_1.35_icon.svg',
  permalink-date: 20219-08-02, name: Visual Studio Code 1.35 icon.svg}
---

# Сложение двух чисел в VSCode на Python

![Featured image](featured-image.svg)

Используем для программирования на Python самый популярный навороченный блокнот VSCode.

## Установка программы

Вначале надо установить Python себе на компьютер. Смотрите статью [Установка Python](https://github.com/Harrix/harrix.dev-blog-2021/blob/main/install-python/install-python.md) <!-- https://harrix.dev/ru/blog/2021/install-python/ -->.

Установите VSCode. Есть статья по его простой установке [Установка Visual Studio Code (простая)](https://github.com/Harrix/harrix.dev-blog-2021/blob/main/install-vscode-simple/install-vscode-simple.md) <!-- https://harrix.dev/ru/blog/2021/install-vscode-simple/ -->. И есть статья с подробной и хардкорной настройкой [Установка Visual Studio Code](/blog/2022/install-vscode/).

После установите расширение Python в VScode:

![Установка расширения Python](img/extension.png)

_Рисунок 1 — Установка расширения Python_

## Создание файла

Создать новый файл можно стандартно через `File` → `New File`, а потом сохранить как скрипт Python:

![Создание нового файла](img/new-file_01.png)

_Рисунок 2 — Создание нового файла_

Но можно пойти по другому пути, учитывая, что вы скорее всего будете создавать много Python файлов в рамках проекта или процесса обучения. В общем, откроем папку, где будем хранить все наши Python скрипты. Это позволит в VSCode сразу видеть все наши файла.

Создадим где-нибудь пустую папку, например, `C:\python_projects`, а потом откроем её в VSCode через `File` → `Open Folder…`:

![Открытие папки](img/new-file_02.png)

_Рисунок 3 — Открытие папки_

![Выбор папки](img/new-file_03.png)

_Рисунок 4 — Выбор папки_

VSCode стал подстраховываться и спрашивает доверяете ли вы авторам, которые создали папку (вдруг там вирусы). Но папку вы создали сами только что, так что доверяем авторам:

![Подтверждение доверия авторам](img/new-file_04.png)

_Рисунок 5 — Подтверждение доверия авторам_

Откроется панель со всеми файлами папки. В нашем случае папка пуста, поэтому файла мы и не видим. Нажав на первую иконку, создадим новый файл:

![Создание нового файла](img/new-file_05.png)

_Рисунок 6 — Создание нового файла_

Для примера файл назван `add2num.py`

![Созданный файл](img/new-file_06.png)

_Рисунок 7 — Созданный файл_

## Написание кода

Напишем программу сложения двух чисел:

```python
a = int(input("Введите первое число "))
b = int(input("Введите второе число "))
c = a + b
print("Сумма =", c)
```

![Код программы](img/code.png)

_Рисунок 8 — Код программы_

## Запуск программы

Через зеленую стрелку наверху справа, которая обозначена на скриншоте сверху, запускаем программу.

Запустится программа, где мы можете ввести два числа и посмотреть на результат их суммирования:

![Запущенное приложение](img/result_01.png)

_Рисунок 9 — Запущенное приложение_

![Результат выполнения программы](img/result_02.png)

_Рисунок 10 — Результат выполнения программы_
