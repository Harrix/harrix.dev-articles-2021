---
date: 2021-08-09
categories:
  - it
  - program
tags:
  - Установка
  - Visual Studio
  - C++
author: Anton Sergienko
author-email: anton.b.sergienko@gmail.com
license: CC BY 4.0
license-url: https://github.com/Harrix/harrix.dev/blob/main/LICENSE.md
permalink-source: https://github.com/Harrix/harrix.dev-articles-2021/blob/main/install-visual-studio-2019/install-visual-studio-2019.md
permalink: https://harrix.dev/ru/articles/2021/install-visual-studio-2019/
lang: ru
attribution:
  - author: Microsoft Corporation
    author-site: https://www.microsoft.com/
    license: Public domain
    license-url: https://en.wikipedia.org/wiki/Public_domain
    permalink: https://commons.wikimedia.org/wiki/File:Visual_Studio_Icon_2019.svg
    permalink-date: 2021-08-09
    name: Visual Studio Icon 2019.svg
---

# Установка Visual Studio 2019 Community

![Featured image](featured-image.svg)

В статье приведена инструкция по установке бесплатной версии Visual Studio 2019 Community на Windows 10 для программирования на C++.

На сайте <https://visualstudio.microsoft.com/ru/> скачиваем установщик:

![Скачивание установщика](img/download.png)

_Рисунок 1 — Скачивание установщика_

Запускаем скаченный файл:

![Начальное окно установщика](img/install_01.png)

_Рисунок 2 — Начальное окно установщика_

![Подзагрузка нужных файлов](img/install_02.png)

_Рисунок 3 — Подзагрузка нужных файлов_

После этого откроется окно с большим количеством пакетов для скачивания и установки в `Visual Studio`. Там и средства для программирования для мобильных устройств и под Node.js и так далее. Причем каждый пункт имеет справа список загружаемых файлов.

Нас интересует программирование на C++ под обычный Windows.

Если вы хотите программировать так называемые универсальные приложения (это те, что с Metro стилем и могут распространяться с магазином), то выберите первый блок и такие подпункты справа (обратите внимание, что пакет `Windows 10 SDK` лучше выбирать последний версии, который будет показываться у вас):

![Пакеты для UWP приложений](img/install_03.png)

_Рисунок 4 — Пакеты для UWP приложений_

Для классических приложений выберите эти пакеты:

![Пакеты для классических приложений](img/install_04.png)

_Рисунок 5 — Пакеты для классических приложений_

Для программирования на C# это выбираем:

![Пакеты для классических приложений под .NET](img/install_05.png)

_Рисунок 6 — Пакеты для классических приложений под .NET_

Лично я еще удаляю пакет русского языка и устанавливаю только английский язык. Но это исключительно на ваш выбор:

![Выбор языковых пакетов](img/languages.png)

_Рисунок 7 — Выбор языковых пакетов_

После выбора пакетов нужно запустить долгую-долгую установку:

![Процесс установки](img/install_06.png)

_Рисунок 8 — Процесс установки_

После установки всех пакетов запустите Visual Studio:

![Первое окно при запуске Visual Studio](img/install_07.png)

_Рисунок 9 — Первое окно при запуске Visual Studio_

Настоятельно рекомендую войти под учетной записью Visual Studio, чтобы через месяц программа не перестала работать:

![Вход в учетку](img/install_08.png)

_Рисунок 10 — Вход в учетку_

![Вход в учетку](img/install_09.png)

_Рисунок 11 — Вход в учетку_

После этого откроется готовая к работе `Visual Studio 2019 Community`:

![Открытая Visual Studio](img/visual-studio.png)

_Рисунок 12 — Открытая Visual Studio_

## Дополнительно

Если вы хотите разрабатывать универсальные UWP приложения, то не забудьте включить режим `Режим разработчика` в параметрах Windows 10:

![Раздел «Обновление и безопасность»](img/parameters_01.png)

_Рисунок 13 — Раздел «Обновление и безопасность»_

![Вкладка «Для разработчиков»](img/parameters_02.png)

_Рисунок 14 — Вкладка «Для разработчиков»_
