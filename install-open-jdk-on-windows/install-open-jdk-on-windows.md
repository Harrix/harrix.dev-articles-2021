---
date: 2021-08-09
categories:
  - it
  - program
tags:
  - Установка
  - Java
  - Android
related-id: start-java
author: Anton Sergienko
author-email: anton.b.sergienko@gmail.com
license: CC BY 4.0
license-url: https://github.com/Harrix/harrix.dev/blob/main/LICENSE.md
permalink-source: https://github.com/Harrix/harrix.dev-articles-2021/blob/main/install-open-jdk-on-windows/install-open-jdk-on-windows.md
permalink: https://harrix.dev/ru/articles/2021/install-open-jdk-on-windows/
lang: ru
---

# Установка Open JDK в Windows

![Featured image](featured-image.svg)

Для программирования под Java и, в частности, при создании приложений под Android на компе требуется установка JDK (Java Development Kit). В статье рассказывается как установить версию Open JDK.

Вместо [установки стандартного JDK](https://github.com/Harrix/harrix.dev-articles-2019/blob/main/install-jdk-on-windows/install-jdk-on-windows.md) | [↗️](https://harrix.dev/ru/articles/2019/install-jdk-on-windows/) можно установить [OpenJDK](https://ru.wikipedia.org/wiki/OpenJDK). Найти его можно на сайте <https://openjdk.java.net/>, но там не предоставляются установщики под Windows: «Мы вам сделали версию под GNU GPL? А собирать сами будете». Благо есть много организаций, которые сами собирают OpenJDK и его распространяют. Один из вариантов — это сайт <https://adoptium.net/>, который с 2021 года находится под крылом Eclipse, так что их сборкам можно доверять.

Например, мне нужен OpenJDK для работы Qt под Android. И там на 2021-08 до сих пор нужна версия JDK 8. Поэтому на сайте <https://adoptium.net/> скачиваем именно JDK 8:

![Скачивание установщика](img/download.png)

_Рисунок 1 — Скачивание установщика_

Установка простая:

![Начальное окно установщика](img/install_01.png)

_Рисунок 2 — Начальное окно установщика_

Рекомендую два параметра последних тоже включить, как на скриншоте:

![Выбор устанавливаемых компонентов](img/install_02.png)

_Рисунок 3 — Выбор устанавливаемых компонентов_

![Окно перед установкой](img/install_03.png)

_Рисунок 4 — Окно перед установкой_

![Процесс установки](img/install_04.png)

_Рисунок 5 — Процесс установки_

![Окончание установки](img/install_05.png)

_Рисунок 6 — Окончание установки_

Всё. JDK устанавливается в папку вида `C:\Program Files\Eclipse Foundation\jdk-8.0.302.8-hotspot`.
