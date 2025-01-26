---
date: 2021-08-20
categories:
  - it
  - programming
tags:
  - Dev C++
  - C++
  - Сложение двух чисел
  - Установка
author: Anton Sergienko
author-email: anton.b.sergienko@gmail.com
license: CC BY 4.0
license-url: https://github.com/Harrix/harrix.dev/blob/main/LICENSE.md
permalink-source: https://github.com/Harrix/harrix.dev-articles-2021/blob/main/add-2-num-code-blocks/add-2-num-code-blocks.md
permalink: https://harrix.dev/ru/articles/2021/add-2-num-code-blocks/
lang: ru
attribution:
  - author: The Code::Blocks team
    author-site: https://www.codeblocks.org/
    license: GNU General Public License
    license-url: https://en.wikipedia.org/wiki/GNU_General_Public_License
    permalink: https://wiki.codeblocks.org/index.php/File:Cb_splash.png
    permalink-date: 2021-08-20
    name: Cb_splash.png
---

# Сложение двух чисел в Code::Blocks

![Featured image](featured-image.svg)

В статье рассказывается как создать консольное приложения сложения двух чисел в Code::Blocks.

- [Установка программы](#установка-программы)
- [Создание проекта](#создание-проекта)
- [Написание кода](#написание-кода)
- [Запуск программы](#запуск-программы)

## Установка программы

На сайте <https://www.codeblocks.org/downloads/binaries/> скачиваем установщик. Скачиваем версию с подписью **mingw-setup**, так как в основном установщике нет компилятора C++, и скорее всего у вас его нет на компьютере:

![Скачивание установщика](img/download.png)

_Рисунок 1 — Скачивание установщика_

<details>
<summary>Установка Code::Blocks</summary>

![Первое окно установки](img/install_01.png)

_Рисунок 2 — Первое окно установки_

![Соглашение с условиями](img/install_02.png)

_Рисунок 3 — Соглашение с условиями_

![Выбор компонентов для установки](img/install_03.png)

_Рисунок 4 — Выбор компонентов для установки_

![Выбор пути установки программы](img/install_04.png)

_Рисунок 5 — Выбор пути установки программы_

![Процесс установки](img/install_05.png)

_Рисунок 6 — Процесс установки_

При запуске программы появится такое окно, где показывается найденный компилятор. Если он не определился, то что-то пошло не так, или вы скачали версию Code::Blocks без компилятора:

![Окно выбора компилятора](img/install_06.png)

_Рисунок 7 — Окно выбора компилятора_

![Окончание установки](img/install_07.png)

_Рисунок 8 — Окончание установки_

![Открытая программа Code::Blocks](img/code-blocks.png)

_Рисунок 9 — Открытая программа Code::Blocks_

</details>

## Создание проекта

Открываем программу `Code::Blocks` и создаем пустой файл (можно создать сразу файл C++, но там путь сего создания дольше):

![Создание пустого файла](img/new-project_01.png)

_Рисунок 10 — Создание пустого файла_

Сразу файл сохраняем, чтобы при написании кода была подсветка синтаксиса:

![Пункт меню для сохранения файла](img/new-project_02.png)

_Рисунок 11 — Пункт меню для сохранения файла_

Выбираем название и папку сохранение нашего файла. **Обязательно** в расширении файла дописываем дву буквы **pp**, чтобы название файла, например, из `Untitled1.c` стало `Untitled1.cpp`. Это нужно, чтобы Code::Blocks понимал, что перед ним будет код на C++, а не языке C:

![Сохранение файла кода](img/new-project_03.png)

_Рисунок 12 — Сохранение файла кода_

![Программа Code::Blocks с пустым сохраненным файлом](img/new-project_04.png)

_Рисунок 13 — Программа Code::Blocks с пустым сохраненным файлом_

Напишите болванку приложения:

```cpp
#include <iostream>

using namespace std;

int main () {

  return 0;
}
```

![Болванка кода на C++](img/new-project_05.png)

_Рисунок 14 — Болванка кода на C++_

Скомпилируйте код и запустите его:

![Компиляция и запуск программы](img/new-project_06.png)

_Рисунок 15 — Компиляция и запуск программы_

У вас должно запуститься пустое приложение, которое ничего не делает:

![Запущенное приложение](img/new-project_07.png)

_Рисунок 16 — Запущенное приложение_

## Написание кода

Перейдем теперь к написанию программы сложения двух чисел.

В функции `main` добавьте код:

```cpp
int a, b, c;

cout << "Input first number" << endl;
cin >> a;

cout << "Input second number" << endl;
cin >> b;

c = a + b;

cout << "Sum " << c << endl;
```

![Код программы сложения двух чисел](img/new-project_06.png)

_Рисунок 17 — Код программы сложения двух чисел_

Полный вид программы будет такой:

```cpp
#include <iostream>

using namespace std;

int main () {

  int a, b, c;

  cout << "Input first number" << endl;
  cin >> a;

  cout << "Input second number" << endl;
  cin >> b;

  c = a + b;

  cout << "Sum " << c << endl;

  return 0;
}
```

На всякий случай упрощенный вариант программы:

```cpp
#include <iostream>

using namespace std;

int main () {

  int a, b, c;

  cin >> a >> b;
  c = a + b;

  cout << c;

  return 0;
}
```

![Код программы сложения двух чисел](img/new-project_08.png)

_Рисунок 18 — Код программы сложения двух чисел_

Сохраните файл:

![Сохранение файла исходного кода](img/new-project_02.png)

_Рисунок 19 — Сохранение файла исходного кода_

## Запуск программы

Скомпилируйте код и запустите его:

![Компиляция и запуск программы](img/new-project_06.png)

_Рисунок 20 — Компиляция и запуск программы_

После запустится программа, где мы можете ввести два числа и посмотреть на результат их суммирования:

![Компиляция и запуск программы](img/new-project_09.png)

_Рисунок 21 — Компиляция и запуск программы_
