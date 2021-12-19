---
categories: [it, program]
tags: [VSCode, Текстовой редактор, FAQ, Установка]
---

# Установка и настройка Visual Studio Code

## Ссылки

- [Stable Build](https://code.visualstudio.com/).
- [Insiders Edition](https://code.visualstudio.com/insiders/).
- [Документация официальная](https://code.visualstudio.com/docs).
- [Плагины](https://marketplace.visualstudio.com/VSCode).
- [Темы](https://marketplace.visualstudio.com/search?target=VSCode&category=Themes&sortBy=Installs).

Расширения, рассмотренные в статье:

- [Flat UI](https://marketplace.visualstudio.com/items?itemName=lkytal.FlatUI) — светлая тема оформления.
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) — иконки типов файлов.
- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) — проверка орфографии.
- [Russian - Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker-russian) — проверка орфографии русского языка.
- [Russian Language Pack for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=MS-CEINTL.vscode-language-pack-ru) — руссификатор интерфейса (сам не использую).
- [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks) — закладки в VSCode.
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) — форматирование кода.
- [Image preview](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-gutter-preview) — вплывающие превью изображений.
- [SVG Viewer](https://marketplace.visualstudio.com/items?itemName=cssho.vscode-svgviewer) — просмотрщик SVG изображений.
- [colorize](https://marketplace.visualstudio.com/items?itemName=kamikillerto.vscode-colorize) — подсветка кодов цвета.
- [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree) — показывает список `TODO` и `FIXME`.
- [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner) — Позволяет запускать код на C++, Python, Java, JavaScript, PHP и др.
- [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) — дополнительные возможности Git (обычно неактивен у меня).
- [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory) — история коммитов репозитория (сам не использую).
- [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) — основное расширение для работы с Python.
- [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) — расширения по работе с Jupyter блокнотами.
- [Jupyter Keymap](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter-keymap) — горячие клавиши по работе с Jupyter.
- [Pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance) — статическая проверка Python кода.
- [Qt for Python](https://marketplace.visualstudio.com/items?itemName=seanwu.vscode-qt-for-python) — поддержка работы PyQt6 и PyQt5.
- [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced) — превью для Markdown файлов.
- [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) — линтер (статический анализатор) Markdown файлов.
- [Markdown Table Prettifier](https://marketplace.visualstudio.com/items?itemName=darkriszty.markdown-table-prettify) — выравниватель таблиц в Markdown.
- [Excel to Markdown table](https://marketplace.visualstudio.com/items?itemName=csholmq.excel-to-markdown-table) — копирование таблицы из Excel в Markdown.
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one) — дополнительные возможности Markdown (сам не использую).

TODO доделать список плагинов

## Скачивание

Есть две версии VSCode:

- Стандартная версия: <https://code.visualstudio.com/>.
- Инсайдерская сборка: <https://code.visualstudio.com/insiders/>.

Вторая сборка программы обновляется каждый день и содержит самые последние возможности программы. За это придется платить возможным наличием багов. Но лично я уже несколько лет пользуюсь инсайдерской версией, и лишь несколько раз встречались критичные баги, которые оперативно исправлялись, и выходила версия без них. Поэтому буду показывать всё на примере инсайдерской версии.

Итак, перейдя по ссылке, скачиваем файл:

![Скачивание файла](img/download.png)

## Установка

Запускаем файл и проходим стандартную установку:

![Соглашение с условиями](img/install_01.png)

![Выбор пути установки программы](img/install_02.png)

![Выбор расположения программы в главном меню](img/install_03.png)

Так как VSCode возможно будет основным текстовым редактором у вас, то рекомендую выделить эти пункты:

![Настройка программы](img/install_04.png)

![Выбранные параметры установка](img/install_05.png)

![Конец установки](img/install_06.png)

![Запущенное приложение](img/install_07.png)

## Выбор темы приложения

Да, я понимаю, что многие любят темные темы в программах, но лично я всегда устанавливаю светлую тему. Что сейчас и сделаем.

Посмотреть все темы, которые можно установить, можно [тут](https://marketplace.visualstudio.com/search?target=VSCode&category=Themes&sortBy=Installs).

Перейдем в раздел расширений:

![Раздел расширений](img/theme_01.png)

Мне нравится тема [Flat UI](https://marketplace.visualstudio.com/items?itemName=lkytal.FlatUI), поэтому в поиске вбиваю тему и устанавливаю её.

![Установка темы](img/theme_02.png)

![Выбор установленной темы](img/theme_02.png)

Все установленные темы можно посмотреть и выбрать через `File` → `Preferences` → `Color Theme`:

![Все установленные темы](img/theme_04.png)

![Список установленных тем](img/theme_05.png)

Кроме темы оформления можно выбрать отдельно тему значков для обозначения расширений файлов. Мне нравится [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme).

Опять в разделе расширений находим наш пакет, устанавливаем и выбираем:

![Поиск и установка пакета](img/theme_06.png)

![Выбор пакета иконок](img/theme_07.png)

Все установленные наборы иконок можно посмотреть и выбрать через `File` → `Preferences` → `File Icon Theme`.

Пока у нас программа выглядит так с установленными темами:

![VSCode со светлой темой](img/theme_08.png)

## Настройки VSCode

Когда мы выбирали наши расширения как активные, то эти расширения прописывались в настройках приложения. Посмотрим, где они находятся.

Идем `File` → `Preferences` → `Settings`:

![Настройки VSCode](img/settings_01.png)

Настройки можно редактировать в графическом виде:

![Настройки в графическом виде](img/settings_02.png)

А если нажать на кнопку, которая на предыдущем скрине показана стрелкой, то перейдем в классический текстовой режим, где все настройки представлены в виде JSON файла:

![Настройки в текстовом виде](img/settings_03.png)

Теперь вы знаете, где это находится. И мы будем не раз возвращаться в настройки.

## Меняем шрифт

Одной из холиварных тем среди программистов является тема шрифтов. Сам в своё время сидел на Courier New, [PT Sans](https://github.com/google/fonts/tree/main/ofl/ptsansnarrow), [Roboto Mono](https://github.com/googlefonts/RobotoMono), а теперь перешел [JetBrains Mono](https://www.jetbrains.com/ru-ru/lp/mono/). Вот его и установлю. Но справедливости ради скажу, что большинство программистов сидят на [
FiraCode](https://github.com/tonsky/FiraCode).

На сайте <https://www.jetbrains.com/ru-ru/lp/mono/> скачаем архив со шрифтами:

![Сайт шрифта JetBrains Mono](img/font_01.png)

Распаковываем его и копируем все файлы расширения `.ttf` в папке `\fonts\ttf`:

![Файлы шрифта JetBrains Mono](img/font_02.png)

А потом их вставляем или перетаскиваем в `Панели управления` или в `Параметрах`:

![Раздел шрифтов в Панели управления](img/font_03.png)

![Раздел шрифтов в Параметрах](img/font_04.png)

Перезагружаем VSCode и переходим в настройки VSCode, которые обсуждались выше. Поле `Font Family` выглядит так:

```text
Consolas, 'Courier New', monospace
```

Меняем его на:

```text
'JetBrains Mono','Roboto Mono', 'Fira Code', 'Courier New', monospace
```

![Изменение шрифта](img/font_05.png)

Да, я прописал два лишних шрифта (`Roboto Mono`, `Fira Code`), чтобы, если установите их, то могли быстро поставить нужный вам на первое место. Тут работает такой принцип: если нет первого, то включается второй шрифт, если и его нет, то третий и так далее. Шрифты `'Courier New', monospace` устанавливать специально не надо: они должны быть на любом компе (monospace — это вообще псевдоним какого-то системного моно-шрифта, то есть все символы в нем одной ширины).

Кстати, после изменений в графическом режиме настроек, в JSON файле тоже произошли изменения (точнее они там и происходили):

![Измененные настройки](img/settings_04.png)

Теперь наш текстовой редактор будет выглядеть так:

![VSCode со светлой темой и новым шрифтом](img/theme_09.png)

## Дополнительные настройки VSCode

Как вы можете видеть в графическом режиме, настроек в VSCode очень много. Покажу только те, которые я лично меняю. Но рекомендую полазить по ним, чтобы отыскать настройки под себя.

Всегда включая мгновенное автосохранение документа при его редактировании:

![Автосохранение документа](img/auto-save.png)

Включаю перенос слов:

![Перенос слов](img/word-wrap.png)

Перенос слов включил, но по правилам хорошего тона во многих языках программирования длинные строки не приветствуются. Поэтому хочу поставить три вертикальные линии на 80 (стандарт со времен перфокарт), 88 (black для Python) и 120 символов (ESLint), чтобы можно было отслеживать в на глаз длину строк. Но тут есть один нюанс: некоторые настройки не редактируются в графическом режиме настроек VSCode. Например, наша настройка `editor.rulers`. Поэтому в JSON файле настроек пишем вручную `"editor.rulers": [80, 88, 120],`:

![Настройка вертикальных линий в редакторе](img/editor-rulers_01.png)

На скрине ниже вы видите две вертикальные линии, которые ни к чему вас не обязывают, но мы можете контролировать по ним сами себя:

![Вертикальные линии в редакторе](img/editor-rulers_02.png)

Следующая настройка позволяет при удалении файла не показывать предупреждения об удалении:

![Удаление файлов без запроса подтверждения](img/confirm-delete.png)

А через следующую настройку `files.associations` можно соотносить подсветку синтаксиса с расширениями файлов, которые пишутся немного по другому. Непонятно? Например, файлы с расширением `.inc` VSCode не умеет распознавать, но это просто файлы настроек программ как и файлы с расширением `.ini`. А мы можем научить VSCode правильно такие файлы распознавать:

```text
"files.associations": {
  "*.inc": "ini"
},
```

![Настройка файловых ассоциаций](img/files-associations_01.png)

![Было](img/files-associations_02.png)

![Стало](img/files-associations_03.png)

Настройка `"files.trimTrailingWhitespace": true,` позволяет VSCode автоматически удалять лишние пробелы в конце строк, когда вы начнете редактировать другие строки. Например, вот эти пробелы будут удалены:

![Пробелы, которые будут удалены](img/trim-trailing-whitespace.png)

Выше мы попросили не просить подтверждение на удаление файлов. Попросим, чтобы этого не было и при перетаскивании файлов через `"explorer.confirmDragAndDrop": false,`. Ниже я перетаскиваю файл, и раздражающего запроса об подтверждении действий не будет:

![Перетаскивание файла](img/confirm_drag_and_drop.png)

С помощью настройки `"editor.mouseWheelZoom": true,` можно увеличивать или уменьшать размер шрифта через колесико мыши при зажатом `Ctrl`:

![Увеличенный текст](img/mouse-wheel-zoom.png)

Сейчас настройки программы выглядят так:

```json
{
    "workbench.colorTheme": "FlatUI",
    "workbench.iconTheme": "material-icon-theme",
    "files.autoSave": "afterDelay",
    "editor.wordWrap": "on",
    "editor.rulers": [80, 120],
    "editor.fontFamily": "'JetBrains Mono','Roboto Mono', 'Fira Code', 'Courier New', monospace",
    "explorer.confirmDelete": false,
    "files.associations": {
        "*.inc": "ini"
    },
    "files.trimTrailingWhitespace": true,
    "explorer.confirmDragAndDrop": false,
    "editor.mouseWheelZoom": true,
}
```

Потом появятся другие настройки, когда будем рассматривать плагины.

## Настройка горячих клавиш

Профессиональный инструмент программирования должен давать возможность переназначать горячие клавиши под себя.

Например, в большинстве средах программирования дублирование текущей строки (`Copy line down`) стоит на комбинации `Ctrl` + `D`, а в VSCode по умолчанию это делается через `Shift` + `Alt` + `Down` (попробуйте). Исправим это. Для этого идем `File` → `Preferences` → `Keyboard Shortcuts`:

![Пункт меню по настройке горячих клавиш](img/keyboard_01.png)

В появившемся списке введем название команды (`Copy line down`), чтобы показать нашу команду. Как видим, она висит на `Shift` + `Alt` + `Down`:

![Список команд с горячими клавишами](img/keyboard_02.png)

Двойной клик по команде, и внизу откроется поле для ввода новой комбинации клавиш, где я ввел `Ctrl` + `D`:

![Изменение горячих клавиш на команду](img/keyboard_03.png)

После этого нажимаем на `Enter` и получаем нужное нам переназначение:

![Команда с измененными горячими клавишами](img/keyboard_04.png)

Кстати, помните, что настройки в графическом виде производились в JSON файле? Также и с настройками горячих клавиш. Если вы щелкните на кнопку, которая стрелкой на скрине выше отмечена, то попадете в JSON файл измененных горячих клавиш, где прописано наше переназначение:

![JSON файл с настройками горячих клавиш](img/keyboard_05.png)

## Работа в программе

Рассмотрим некоторые элементы управления в программе.

### Палитра команд

Если нажать `F1`, то вызовется палитра команд с очень большим количеством команд:

![Палитра команд](img/command-palette_01.png)

Например, ниже показано, как сделать выделенный текст прописными буквами через эту палитру команд:

![Палитра команд](img/command-palette_02.mp4)

### Работа с папками

Вы можете открывать целые папки со всеми файлами, включая картинки, документы и др. через `File` → `Open Folder`:

![Команда открытия папки](img/open-folder_01.png)

![Пример открытия папки](img/open-folder_02.png)

### Рабочие области

Вы можете часто работать с одним и тем же набором открытых файлов и папок. И такое состояние называется **Workspace** (Рабочая область). И такую рабочую область можно сохранять как файл, а при его открытии откроются все папки и файлы, которые там были записаны.

Например, выше я открыл в VSCode папку `C:\GitHub\Harrix-HTML-Template`. Через `File` → `Add Folder to Workspace` добавлю, например, папку `C:\GitHub\static-site-webpack-habr`:

![Две открытые папки](img/workspace_01.png)

Теперь через `File` → `Save Workspace As…` сохраняю рабочую область, например, как `temp.code-workspace`. И это будет обычный JSON файл с таким содержимым:

```json
{
  "folders": [
    {
      "path": "C:\\GitHub\\Harrix-HTML-Template"
    },
    {
      "path": "C:\\GitHub\\static-site-webpack-habr"
    }
  ],
  "settings": {}
}
```

Через команду `File` → `Open Workspace` откроются все те же самые папки:

![Пример открытия рабочей области](img/workspace_02.mp4)

Лично я использую несколько рабочих областей, каждую из которых открываю в отдельном окне через `File` → `New Window`.

### Сохранение вкладки

Когда вы открываете файл, в котором не вносите никаких изменений, то название файла будет во вкладке написано курсивом:

![Название файла написано курсивом](img/tabs_01.png)

Это означает, что если открыть любой другой файл, то наш файл закроется. Чтобы он не закрывался, то в контекстном меню вкладки можно выбрать `Keep Open`:

![Сохранение вкладки открытой](img/tabs_02.mp4)

Если в файл вносятся какие-то изменения, то вкладка не закроется в любом случае.

### Терминал

В VSCode встроен удобный терминал, который часто заменяет тот же Windows Terminal или cmd во многих задачах. Вызывается через `Ctrl` → `` ` ``:

![Открытый консольный терминал](img/terminal_01.png)

В этом терминале можно выполнять любые задачи, которые выполняются в командной строке.

Если нужно, то любую папку можно открыть в терминале через контекстное меню через команду `Open in Integrated Terminal`:

![Открытый консольный терминал](img/terminal_02.png)

Терминалов может несколько, они могут одновременно отображаться на экране, можно открыть разные терминалы, которые есть на компьютере (например, PowerShell, GitBash, cmd и др.):

![Работа с несколькими терминалами](img/terminal_03.mp4)

Напоминаю, что выход в терминале из какой-нибудь выполняющейся программы можно сделать через `Ctrl` + `C`.

### Поиск и замена

В VSCode встроен мощный поиск и замена по файлам проекта (рабочей области):

![Вкладка поиска](img/search_01.png)

Поиск можно производить с учетом регистра, использовать регулярные выражения.

В строке `Replace` располагается текст для замены. Справа от нее находится кнопка для вызова команды замены:

![Пример замены script на noscript во всех файлах проекта](img/replace_01.png)

Если нужен поиск по конкретной папке, то можно в контекстном меню папки найти команду `Find in Folder…`:

![Поиск по папке](img/search_02.png)

Тогда в панели поиска появится название папки, в которой нужно производить поиск:

![Имя папки в панели поиска](img/search_03.png)

Если же нужен поиск и замена только в одном открытом файле, то вызываем через стандартные `Ctrl` + `F`:

![Поиск в открытом файле](img/search_04.png)

Если щелкнем по стрелке слева, то откроется окно для замены в открытом файле:

![Замена в открытом файле](img/replace_02.png)

### Быстрый переход к файлу

Если нужно быстро перейти к файлу проекта, зная его название, то это можно сделать через `Ctrl` + `P`:

![Быстрый переход к файлу](img/open.png)

### Автодополнение

Как и во многих редакторах в VSCode работает автодополнение, которое принудительно можно вызвать через `Ctrl` + `Space`:

![Вызов автодополнения](img/auto-completion.png)

### Переход к расположению файла

Если кликнуть по файлу правой кнопкой мыши и выбрать `Reveal in File Explorer`, то вы попадете в папку, где данный файл располагается:

![Переход к расположению файла](img/file-explorer_01.png)

![Папка с файлом](img/file-explorer_02.png)

### Разделение вкладок

TODO

### CLI

CLI — Интерфейс командной строки ([Command line interface](https://ru.wikipedia.org/wiki/%D0%98%D0%BD%D1%82%D0%B5%D1%80%D1%84%D0%B5%D0%B9%D1%81_%D0%BA%D0%BE%D0%BC%D0%B0%D0%BD%D0%B4%D0%BD%D0%BE%D0%B9_%D1%81%D1%82%D1%80%D0%BE%D0%BA%D0%B8)). Когда мы открываем VSCode, то видим полноценный оконный интерфейс. А в терминале программы запускаются без данного интерфейса, что вы уже, конечно, давно знаете. Но многие программы, которые имеют интерфейс можно запустить как консольную программу в том же терминале. И VSCode не исключение.

Подробно об таком режиме работы можно прочитать в [официальной документации](https://code.visualstudio.com/docs/editor/command-line).

Если у вас стандартный VSCode, то в командной строке команды будут начинаться с `code`, а если, как у нас, VSCode Insiders, то `code-insiders`.

Например, через команду `code-insiders --list-extensions` мы получим список установленных расширений:

![Список установленных расширений](img/cli_01.png)

Это можно использовать, например, в собственных скриптах, где в процессе работы нужно вызвать VSCode, чтобы пользователь что-то сделал в файле.

## Настройка сниппетов

Программисты — люди ленивые. И они очень не любят дублировать повторяющиеся куски кода. У каждого программиста есть свой список заготовок (шаблоны HTML файла, подпись в письме и др.), которые они любят вставлять в свои коды. И такие подготовленные куски кода или текста называются сниппетами.

Также регулярно нужно вставлять в текст нестандартные символы, которых нет на клавиатуре (`«»`, `©`, `→` и др.), что тоже можно описать в виде сниппетов (именно эту задачу можно еще решить через плагин [Insert Unicode](https://marketplace.visualstudio.com/items?itemName=brunnerh.insert-unicode)).

Как вы поняли, в VSCode есть инструмент по работе со сниппетами. Идем `File` → `Preferences` → `User Snippets`:

![Пункт меню с настройками сниппетов](img/snippets_01.png)

Вы можете сделать сниппеты как глобальные, так и специализированные, которые будут работать в определенных типов файлов. Создадим глобальный:

![Создание новой коллекции сниппетов](img/snippets_02.png)

Введем имя коллекции, например, `common` и нажмем `Enter`:

![Ввод имени коллекции сниппетов](img/snippets_03.png)

После этого откроется JSON файл с комментариями, где мы можем вставлять свои сниппеты. Для примера я вставлю код вот такого сниппета, который будет добавлять стрелку вправо:

```json
"Insert →": {
  "prefix": "->",
  "body": [
    "→"
  ]
},
```

![Введенный сниппет](img/snippets_04.png)

Теперь, если мы в VSCode нажнем писать `->`, то у нас появится выбор, чтобы заменить эти два символа на нормальную стрелку:

![Пример использования сниппета](img/snippets_05.png)

То есть в сниппете раздел `prefix` означает, с чего начинается подмена, а `body` означает то, на что мы будем заменять префикс.

Вот пример сниппета, который вместо `doctype` будет подставлять HTML болванку:

```json
"Insert HTML": {
  "prefix": "doctype",
  "body": [
    "<!DOCTYPE html>",
    "<html>",
    "  <head>",
    "    <meta charset=\"utf-8\">",
    "    <title></title>",
    "  </head>",
    "  <body>",
    "  </body>",
    "</html>"
  ],
   }
```

![Пример использования сниппета](img/snippets_06.mp4)

Обратите внимание на то, как построен этот многострочный сниппет. Мне это не нравится, и в том же Atom или Sublime Text сделано куда лучше, но что есть, то есть. На сайте <https://snippet-generator.app/> можно генерировать свои собственные многострочные сниппеты.

Ниже под спойлером лежит мой список сниппетов, в котором я использую часто встречаемые Unicode символы:

---

**Сниппеты** <!-- !details -->

**common.code-snippets**:

```json
{
    "Insert «»": {
      "prefix": "<<>>",
      "body": [
        "«»"
      ]
    },
    "Insert «": {
      "prefix": "<<",
      "body": [
        "«"
      ]
    },
    "Insert »": {
      "prefix": ">>",
      "body": [
        "»"
      ]
    },
    "Insert ©": {
      "prefix": "(c)",
      "body": [
        "©"
      ]
    },
    "Insert ×": {
      "prefix": "x",
      "body": [
        "×"
      ]
    },
    "Insert →": {
      "prefix": "->",
      "body": [
        "→"
      ]
    },
    "Insert …": {
      "prefix": ",,,",
      "body": [
        "…"
      ]
    },
    "Insert em dash (век живи — век учись)": {
      "prefix": "---",
      "body": [
        "—"
      ]
    },
    "Insert en dash (2010–2018)": {
      "prefix": "--",
      "body": [
        "–"
      ]
    },
    "Insert keyboard shortcut": {
      "prefix": "``",
      "body": [
        "`` → ``"
      ]
    },
    "Insert HTML": {
      "prefix": "doctype",
      "body": [
        "<!DOCTYPE html>",
        "<html>",
        "  <head>",
        "    <meta charset=\"utf-8\">",
        "    <title></title>",
        "  </head>",
        "  <body>",
        "  </body>",
        "</html>"
      ],
      }
}
```

А тут пример сниппета исключительно под Markdown.

**markdown.json**:

```json
{
    "Insert image": {
      "prefix": "img",
      "body": [
        "![](img/.png)"
      ]
    }
}
```

---

## Проверка орфографии

Для проверки орфографии нужно установить расширение [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) и [Russian - Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker-russian).

![Установка расширений](img/code-spell-checker_01.png)

После установки лучше перезапустить VSCode, потом вызвать панель команд через `F1`, где выбрать команду `Enable Russian Spell Checker Dictionary`, которая и включит проверку орфографии:

![Включение проверки русского языка](img/code-spell-checker_02.png)

Очень вероятно, что вам захочется одновременно проверять как русский язык, так и английский. Для этого в настройках можно ввести настройку:

```json
 "cSpell.language": "en,ru",
```

![Настройки проверки орфографии](img/code-spell-checker_03.png)

Теперь, слова с ошибками будут подсвечиваться, а также отображаться в списке проблем:

![Примеры орфографических ошибок](img/code-spell-checker_04.png)

Также при наведении на неправильное слово появится возможность исправить слово на правильное:

![Исправление ошибки](img/code-spell-checker_05.mp4)

Иногда может оказаться, что вы слово написали правильно, но его просто нет в словаре:

![В словаре нет слова «сниппета»](img/code-spell-checker_06.png)

Еще совсем недавно новые слова добавлялись в файл настроек VSCode, что сильно его засоряло. В новом обновлении плагина появилась возможность создавать файл своего собственного словаря. Для этого щелкаем правой кнопкой по слову, выбираем `Create a Custom Dictionary File`:

![Выбор команды «Create a Custom Dictionary File»](img/code-spell-checker_07.png)

Можно выбрать место действия данного словаря: папка, рабочая область или везде. Последний вариант `User` я и выбираю:

![Выбор место действия словаря](img/code-spell-checker_08.png)

будет создан файл, где в столбик можно размещать слова для словаря:

![Добавление вручную слова в словарь](img/code-spell-checker_09.png)

После создания файла словаря новые словаря можно добавлять через команду `Add Word to User Dictionary` в контекстном меню:

![Добавление нового слова в словарь](img/code-spell-checker_10.png)

Обратите внимание на путь создания файла словаря. У меня это `C:\Users\sergi\.cspell\custom-dictionary-user.txt`.

TODO будет ли синхронизироваться словарь в настройках?

## Расширения

Рассмотрим расширения, которые нам могут помочь в работе.

Все расширения устанавливаются через раздел, в котором мы уже были:

![Раздел расширений](img/extensions.png)

А посмотреть их, выбрать, оценить можно на официальном сайте <https://marketplace.visualstudio.com/VSCode>.

### Russian Language Pack for Visual Studio Code

[Russian Language Pack for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=MS-CEINTL.vscode-language-pack-ru) — руссификатор интерфейса программы. Но я настоятельно не рекомендую использовать руссификатор. Привыкайте работать с английским языком. Так будет выглядеть программа:

![VSCode с русским интерфейсом](img/russian-language-pack.png)

### Bookmarks

[Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks) — закладки в VSCode.

После установки вы через контекстное меню сможете устанавливать закладки в любом документе в любом месте:

![Включение закладки в контекстном меню](img/bookmarks_01.png)

Также слева появится раздел с вашими закладками:

![Раздел с закладками](img/bookmarks_02.png)

### Prettier - Code formatter

[Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) — плагин, который позволяет красиво отформатировать ваш код на языках: JavaScript, TypeScript, JSON, CSS, SCSS, HTML, Markdown и др.

Когда вам нужно будет отформатировать код, то из палитры команда `F1` выбираете команду `Format document`:

![Format document](img/prettier_01.png)

При первом использовании будет предложено выбрать плагин для форматирования кода.

![Запрос на выбор плагина для форматирования кода](img/prettier_02.png)

![Выбор плагина для форматирования кода](img/prettier_03.png)

Покажем, как работает код. Например, есть такой код:

```html
<!DOCTYPE                html>
<html>
                <head>
    <meta
    charset=    "utf-8">
    <title></title>
                </head>
          <body>
  </body>
</html>
```

Плагин нам его преобразует вот в такой:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title></title>
  </head>
  <body></body>
</html>
```

Из дополнительных настроек плагина я использую `printWidth`:

```json
"prettier.printWidth": 120,
```

Этот параметр позволяет разбивать длинные строки на строки по 120 символов.

Было:

![HTML с длинной строкой](img/prettier_04.png)

Стало:

![HTML разбит на короткие строки](img/prettier_05.png)

### Image preview

[Image preview](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-gutter-preview) — вплывающие превью изображений.

Во-первых, слева в документе, где приводится ссылка на картинку, показывается мини версия картинки.

Во-вторых, при наведении на ссылку картинки, появится всплывающее окно с миниатюрой картинки:

![Пример работы плагина](img/image-preview.png)

Размер миниатюр небольшой, поэтому я их увеличиваю настройкой:

```json
"gutterpreview.imagePreviewMaxHeight": 200,
```

### SVG Viewer

[SVG Viewer](https://marketplace.visualstudio.com/items?itemName=cssho.vscode-svgviewer) — просмотрщик SVG изображений.

![Кнопка просмотра SVG](img/svg-viewer_01.png)

![Код SVG вместе с его визуализацией](img/svg-viewer_02.png)

### colorize

[colorize](https://marketplace.visualstudio.com/items?itemName=kamikillerto.vscode-colorize) — подсветка кодов цвета цветом, который они обозначают.

Было:

![Пример CSS кода с кодами цветов](img/colorize_01.png)

Стало:

![Пример CSS кода с подсвеченными кодами цветов](img/colorize_02.png)

Можно в настройках указать, в каких [типах файлов](https://code.visualstudio.com/docs/languages/overview) будет подсветка цветов. Мне этот плагин нужен в Markdown документах. Поэтому у меня такая настройка:

```json
"colorize.languages": ["css", "scss", "sass", "javascript", "html", "markdown"],
```

### Todo Tree

[Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree) — показывает список `TODO` и `FIXME`, расставленных в коде и документах проекта, что позволяет быть в курсе того, куда в коде нужно вернуться и доделать недоделанное.

![Список todos](img/todo_01.png)

Через какое-то время плагин попросил добавить расширенную настройку на TODO в Markdown документах:

![Запрос на добавление настройки](img/todo_02.png)

В `settings.json` это выглядит так:

```json
"todo-tree.regex.regex": "(//|#|<!--|;|/\\*|^|^\\s*(-|\\d+.))\\s*($TAGS)",
```

### Code Runner

[Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner) — Позволяет запускать код на C++, Python, Java, JavaScript, PHP и многих других языках программирования.

Во избежание многих проблем добавьте в настройки VSCode запуск расширения через встроенный терминал. При этом исчезнут проблемы с кодировкой русского языка, возможностью ввода данных и др.:

```json
"code-runner.runInTerminal": true,
```

Примеры использования будут рассмотрены ниже в разделе о программировании на Python и C++.

TODO Code Runner

## Работа с Git

### Встроенный функционал

Вам вначале нужно будет установить Git отдельно на компьютер (после этого перезапустите VSCode). Об этом можно прочитать в статье [Установка Git](/blog/2021/install-git/).

Лично я с Git предпочитаю работать через стороннюю программу (GitHub Desktop, GitKraken и др.), которая не привязывается к конкретной среде разработке, так как в проекте над файлами работа может производиться в разных программах. Но VSCode имеет мощные встроенные средства по работе с Git.

Во вкладке `Source Control` вы увидите изменения во всех репозиториях рабочей области (в примере ниже открыто три репозитория, и в одном из них есть изменения). При щелчке по файлу откроется оно со сравнением изменений файла:

![Изменения в файле с момента последнего коммита](img/git_01.png)

При вводе названия коммита и нажатии `Ctrl` + `Enter` изменения сформируются в коммит:

![Создание коммита](img/git_02.png)

Но отправки коммита на сервер GitHub не произойдет, для этого нужно нажать кнопку `Push`:

![Отправка коммита на сервер](img/git_03.png)

При щелчке на обозначение текущей ветки репозитория откроется список команд по работе с ветками: создание новых, переключение между ветками и др.:

![Команды по работе с ветками](img/git_04.png)

При щелчке на многоточие мы получим меню с множеством команд по работе с Git:

![Команды по работе с git](img/git_05.png)

### GitLens — Git supercharged

[GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) — расширение, сильно расширяющая возможности по работе с Git. Но жрет ресурсов он много, так что на слабых машинах лучше его не ставить.

Например, он на текущей строке любого документа репозитория покажет, когда и кем эта строка последний раз менялась, а также название коммита с этим изменением:

![Кто и когда менял эту строку](img/git-lens_01.png)

Также слева наверху появится кнопка, которая позволит перемещаться между изменениями разных коммитов:

![Перемещение по истории коммитов](img/git-lens_02.png)

Подробнее о плагине читайте в его документации.

### Git History

[Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory) — история коммитов репозитория.

Через панель команд `F1` вызываем команду `Git: View History` и видим историю коммитов:

![Команда показа истории коммитов](img/git-history_01.png)

![История коммитов](img/git-history_02.png)

А по команде `Git: View File History` можно увидеть историю коммитов именно данного файла:

![История коммитов файла](img/git-history_03.png)

Опять таки напишу, что для работы с Git использую GitHub Desktop, так что эти два плагина я не использую у себя. Правда GitLens стоит, но не активен, чтобы изредка им пользоваться.

## Программирование на Python

Есть официальная документация о работе с Python в VSCode: [Python in Visual Studio Code](https://code.visualstudio.com/docs/languages/python).

Вам вначале нужно будет установить Python отдельно на компьютер (после этого перезапустите VSCode). Об этом можно прочитать в статье [Установка Python](/blog/2021/install-python/).

И на всякий случай обновите у себя `pip` (терминал или командную строку лучше открывать с правами администратора):

```console
python -m pip install --upgrade pip
```

Не забудьте после установки Python перезапустить VSCode.

### Расширения для Python

Установите [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python) — основное расширение для работы с Python.

Вместе с ним автоматически (на август 2021) установятся расширения (если не установились, то установите):

- [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) — расширения по работе с Jupyter блокнотами.
- [Jupyter Keymap](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter-keymap) — горячие клавиши по работе с Jupyter.
- [Pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance) — статическая проверка кода, автодополнения, справка и так далее.

Рекомендую также следующие расширения, которые могут пригодиться:

- [Qt for Python](https://marketplace.visualstudio.com/items?itemName=seanwu.vscode-qt-for-python) — поддержка работы PyQt6 и PyQt5, если вы работаете с Qt.

### Запуск Python кода

В VSCode есть несколько способов запуска вашего Python кода.

#### Стандартный запуск

Когда вы создаете файл с кодом Python, то наверху справа появится кнопка запуска кода:

![Запуск скрипта](img/run-py-standard_01.png)

![Результат выполнения программы](img/run-py-standard_02.png)

#### Запуск в режиме отладки

Можно запустить код в режиме отладки с точками остановки:

![Запуск кода через панель отладки](img/run-py-debug_01.png)

![Пример запуска кода](img/run-py-debug_02.mp4)

Также в режиме отладки можно запустить через знакомую кнопку в форме треугольника:

![Запуск кода через кнопку старта](img/run-py-debug_03.png)

#### Запуск через консоль с Jupyter

Вы можете запустить код в интерактивном виде через использование Jupyter через клик правой кнопкой по коду через `Run Current File in Interactive Window` (вас возможно попросят доустановить глобальные python пакеты `ipykernel` и др.):

![Запуск кода через Jupyter](img/run-py-jupyter-console_01.png)

![Пример запуска кода](img/run-py-jupyter-console_02.mp4)

#### Запуск через Code Runner

Если вы установили [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner), о котором говорилось выше, то в меню кнопки запуска появится пункт `Run Code`:

![Запуск через Code Runner](img/run-py-code-runner_01.png)

Вы же не забыли включить в настройках VSCode эту настройку:

```json
"code-runner.runInTerminal": true,
```

Если нет, то получите стандартный запуск кода в терминале:

![Запуск скрипта в терминале](img/run-py-code-runner_02.png)

Если забыли, то получите проблемы с русским языком, а также невозможность ввести данные при выполнении `int(input())`, например:

![Запуск скрипта в output](img/run-py-code-runner_03.png)

Как видите, что особого смысла в Code Runner для Python нет, так как и без него можно запускать код в терминале.

#### Запуск в Jupyter

Официальная документация по работе  Jupyter: [Jupyter Notebooks in VS Code](https://code.visualstudio.com/docs/datascience/jupyter-notebooks).

Для работы с Jupyter нужен пакет [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter), который ставится автоматически при установке пакета [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python).

Создать новый блокнот Jupyter можно через `F1` → `Jupyter: Create New Blank  Notebook`:

![Создание нового блокнота](img/run-py-jupyter_01.png)

После этого будет создан новый полноценный блокнот Jupyter, с которым можно работать:

![Созданный блокнот](img/run-py-jupyter_02.png)

Например, я ввожу код тестового примера, который запускаю через треугольник слева от куска кода:

![Ввод кода и его запуск](img/run-py-jupyter_03.png)

Команды `input()` будут выполняться через всплывающие окна:

![Ввод данных](img/run-py-jupyter_04.png)

После отобразится результат выполнения программы:

![Результат выполнения программы](img/run-py-jupyter_05.png)

### Виртуальные среды

В Python, в отличии от других языков программирования, не принято (но можно) работать с головным интерпретатором Python, который у вас установлен на компьютере. Желательно под каждый проект создавать специальную папку (виртуальная среда), в которой будет свой экземпляр Python (копируясь с головного интерпретатора). В ней же будут храниться все установленные пакеты под ваш проект.

Зачем это? Разные версии Python могут быть несовместимы друг с другом. Тоже самое касается и пакетов. И чтобы разные проекты не конфликтовали друг с другом, была предложена идея виртуальных сред.

В примерах запуска кода, которые приведены выше, все эксперименты проводились без использования виртуальных сред, и запускался головной файл `python.exe` (у меня он располагается по пути `C:\Python39\python.exe`).

Итак, у нас есть папка, например, `python-test` со скриптами, открытая в VSCode. Также открыт терминал через `Ctrl` + `` ` ``:

![Открытая папка в VSCode](img/virtual_environment_01.png)

#### Venv

Новую виртуальную среду под наш проект можно создать через команду:

```console
python -m venv .venv
```

![Ввод команды python -m venv venv](img/virtual_environment_02.png)

Надеюсь, что вы понимаете, что в терминале вы должны находиться в папке, в которой вы хотите создать виртуальную среду.

После этого VSCode попросит использовать созданную виртуальную среду у себя для запуска скриптов:

![Запрос на использование виртуальной среды](img/virtual_environment_03.png)

![Отображение виртуальной среды](img/virtual_environment_04.png)

Кстати, если вы свой проект храните в git (например, в GitHub), то не забудьте в файл `.gitignore` добавить папку виртуальной среды. Её не нужно добавлять в git историю:

![Возможные варианты называния папки виртуальной среды](img/virtual_environment_05.png)

#### Virtualenv

Кроме встроенной системы виртуальных сред Venv есть и другие системы. Например, PyCharm использует [Virtualenv](https://virtualenv.pypa.io/en/stable/) по умолчанию. Вначале устанавливаем глобальный пакет:

```console
python -m pip install virtualenv
```

В папке проекта виртуальную среду можно создать через:

```console
python -m virtualenv .env
```

![Создание виртуальной среды](img/virtual_environment_06.png)

VSCode также обнаружит её и попросит выбрать:

![Выбор созданной виртуальной среды](img/virtual_environment_07.png)

![Выбранная виртуальная среда](img/virtual_environment_08.png)

[Путь к виртуальному окружению]\Scripts\activate.bat

c:\projects\harrix-test-package\.env\Scripts\activate.bat

Когда вы устанавливаете пакеты в проект, то в проекте создается файл `requirements.txt` (этот файл в отличии от папки с виртуальной средой нужно в git добавлять) со списком пакетов. И на другой машине можно восстановить пакеты через команду:

```console
python -m pip install -r requirements.txt
```

#### Pipenv

Ну, а лично я использую [Pipenv](https://github.com/pypa/pipenv). Он работает с виртуальными средами Virtualenv, но также фиксирует все версии пакетов, включая внутренние зависимости, что позволяет однозначно развернуть ваш проект на другой машине.

Установка глобального пакета (лучше устанавливать под администратором):

```console
python -m pip install virtualenv
python -m pip install pipenv
```

По умолчанию Pipenv использует папку `C:\Users\[User]\.virtualenvs` для сохранения виртуальных сред в отличии от двух предыдущих инструментов, которые соответствующую виртуальные среды сохраняют в папку проекта. Есть способ это поменять через `set PIPENV_VENV_IN_PROJECT=1`, но не советую, так как папки виртуальных сред будут называться, например, для проекта `python-test` как `python-test-TCOhYAuY`, что усложнит добавление папки в `.gitignore`.

Виртуальную среду можно создать через две команды:

```console
pipenv install
pipenv shell
```

![Создание виртуальной среды](img/virtual_environment_09.png)

Появится, например, папка `C:\Users\sergi\.virtualenvs\python-test-TCOhYAuY` с виртуальной средой, а в папке с проектом появятся два файла `Pipfile` и `Pipfile.lock`, которые нужно добавлять в git.

И вот тут VSCode не подхватит сразу созданную виртуальную среду, так как она создается не в папке с проектом. Поэтому добавьте в файл настроек VSCode следующую строку с вашим путем, куда Pipenv сохраняет виртуальные среды:

```json
"python.venvPath": "C:\\Users\\sergi\\.virtualenvs",
```

![Установка пути к виртуальным средам](img/virtual_environment_10.png)

Перезапустите VSCode после этого.

Теперь внизу слева вы можете выбрать вашу виртуальную среду:

![Выбор виртуальной среды](img/virtual_environment_11.png)

![Выбранная виртуальная среда](img/virtual_environment_12.png)

Также при использовании Pipenv при установке пакетов для вашего проекта внутри виртуальной среды вместо команд `pip install numpy` (`python -m pip install numpy`) теперь надо использовать `pipenv install numpy` (`python -m pipenv install numpy`).

А если вы хотите развернуть ваш проект на другой машине, то установите Pipenv на другой машине и вызовите команду (это аналог `python -m pip install -r requirements.txt`):

```console
pipenv install
pipenv shell
```

И иногда может пригодится команда, которая для Pipenv укажет путь к Python: `pipenv --python C:\Python39\python.exe` (у вас будет другой путь). Например, ниже на скриншоте я на новой машине пытался через `pipenv install --dev` поднять свой проект, но на прошлой машине у меня был Python 3.8, а теперь перешел на 3.9. И пришлось через вышеуказанную команду указывать путь к Python:

![Переназначение пути к Python](img/virtual_environment_13.png)

Через команду `pipenv update` в проекте можно обновить все пакеты.

#### Несколько виртуальных сред

Как вы уже знаете, VSCode может в одном окне открыть несколько папок, каждая из которых может быть полноценным Python проектом:

![Три проекта в одном окне](img/virtual_environment_14.png)

И возникает проблема переключения виртуальных сред между проектами. К счастью, VScode можно научить, что в каждом проекте будет своя виртуальная среда. Для этого для каждого проекта щелкаем на выбор виртуальной среды, выбираем проект, а потом под него виртуальную среду:

![Выбор проекта](img/virtual_environment_15.png)

![Выбор виртуальной среды под проект](img/virtual_environment_16.png)

В качестве общей виртуальной среды выбирает общий интерпретатор Python:

![Выбор рабочей области](img/virtual_environment_17.png)

![Выбор интерпретатора](img/virtual_environment_18.png)

После этого при переключении файлов разных проектов будет выбираться виртуальная среда соответствующего проекта:

![Переключение виртуальных сред](img/virtual_environment_19.mp4)

Есть еще одна потенциальная опасность. Например, вы добавляете еще один проект, в котором в терминале хотите через `pipenv install` создать виртуальную среду под новый проект:

![Открытие нового проекта в терминале](img/virtual_environment_20.png)

И возможно, что у вас в терминале откроется не чистый терминал, а с открытой виртуальной средой предыдущего проекта:

![Открытие нового проекта в терминале](img/virtual_environment_21.png)

И тут команда `pipenv install` сработает не так как нужно. Поэтому в этом случае выходим из виртуальной среды через команду `deactivate`, как на скриншоте выше.

#### Принудительный выбор виртуальной среды

Может так быть, что виртуальная среда не появится сразу в списке. Тогда её можно выбрать через `Enter interpreter path…`:

![Выбор ввода пути виртуальной среды](img/virtual_environment_22.png)

Например, тут я посмотрел в папке виртуальных сред `C:\Users\[User]\.virtualenvs\` папку своей среды `C:\Users\sergi\.virtualenvs\HarrixSpace-hgtVR0PE`, ввел ёё и нажал на `Enter`:

![Ввод пути виртуальной среды](img/virtual_environment_23.png)

### Автоформатирование кода

VSCode поддерживает автоформатирование кода. Например, у вас есть такой код:

```py
a = int(input(  "Введите первое число "))
b = int(   input("Введите второе число "))
c =a +   b
print("Сумма =",     c)
```

Как и всегда, команду можно вызвать через панель команд `F1`, а после написав `format`

![Вызов команды Format Document](img/format_01.png)

Будет преложено установить один из трех плагинов: `autopep8`, `black`, `yapf`

![Выбор плагина](img/format_02.png)

![Установка пакета](img/format_03.png)

Обратите внимание на то, что это установка глобального пакета Python, а не установка расширения в VSCode.

И после этого вышеприведенный код будет отформатирован так:

![Результат форматирования](img/format_04.png)

Но лично я предпочитаю плагин [black](https://github.com/psf/black), отличительной особенностью которого является то, что он почти никак не настраивается: общие правила для всех.

А мы только что установили autopep8. Будем менять. Вначале установим глобально плагин black:

```console
pip install black
```

![Установка пакета black](img/format_05.png)

А потом меняем в настройках плагин для автоформатирования:

![Выбор плагина](img/format_06.png)

Либо меняете в настройках в виде JSON:

```json
"python.formatting.provider": "black",
```

![Результат форматирования](img/format_07.png)

Сравнение плагинов автоформатирования можно почитать [тут](https://blog.frank-mich.com/python-code-formatters-comparison-black-autopep8-and-yapf/).

## Работа с Markdown

Работа с Markdown файлами заложена по умолчанию в VSCode. Даже математические формулы теперь работают по умолчанию (раньше требовалось отдельное [расширение](https://marketplace.visualstudio.com/items?itemName=goessner.mdmath)).

Когда вы открываете Markdown файл, то справа наверху есть кнопка для показа отрендеренного файла:

![Кнопка показа превью Markdown файла](img/markdown_01.png)

Слева вы можете редактировать файл, а справа видеть, что получается в режиме реального времени:

![Markdown файл и его превью](img/markdown_02.png)

Попробуйте создать Markdown файл `test.md` с таким [содержимым](files/test.md):

![Markdown файл с формулами и таблицей](img/markdown_03.png)

Слева внизу есть раздел `Outline`, при раскрытии которого вы увидите структуру вашего Markdown файла:

![Область Outline](img/outline.png)

Теперь посмотрим на дополнительные расширения.

### Markdown Preview Enhanced

[Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced) — превью для Markdown файлов.

После установки плагина появится вторая иконка (она будет первой) для открытия просмотра Markdown файла:

![Кнопка открытия превью Markdown файла](img/markdown-preview-enhanced_01.png)

Да, в VSCode уже встроен просмотрщик Markdown файлов в отрендеренном виде, что рассматривалось выше. Но этот плагин более крутой. Например, в нем есть встроенное содержание документа:

![Кнопка открытия содержания Markdown файла](img/markdown-preview-enhanced_02.png)

![Превью Markdown файла с содержанием](img/markdown-preview-enhanced_03.png)

Если кликнуть правой кнопкой мыши, то обнаружим богатое меню с разными командами. Есть много команд по экспорту Markdown документа в PDF, HTML:

![Контекстное меню](img/markdown-preview-enhanced_04.png)

Например, команда `HTML` → `HTML (offline)` сгенерирует HTML файл в той же папке, что и Markdown файл, открыв который, мы увидим отрендеренный файл:

![HTML файл](img/markdown-preview-enhanced_05.png)



TODO Markdown Preview Enhanced

### markdownlint

[markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) — линтер (статический анализатор) Markdown файлов. Другими словами ищет ошибки в документе, которые отображает в панели `Problems`:

![Ошибки в документе](img/markdownlint.png)

### Markdown Table Prettifier

[Markdown Table Prettifier](https://marketplace.visualstudio.com/items?itemName=darkriszty.markdown-table-prettify) — позволяет привести таблицы к нормальному виду. Делается это через клик правой кнопки по выделенной таблице `Format Selection`:

![Исправление таблицы](img/markdown-table-prettifier.mp4)

### Excel to Markdown table

[Excel to Markdown table](https://marketplace.visualstudio.com/items?itemName=csholmq.excel-to-markdown-table) — позволяет копировать таблицы из Excel в Markdown формат по `Shift` + `Alt` + `V`:

![Копирование из Excel в Markdown](img/excel-to-markdown-table.mp4)

Если что-то идет не так, либо не удобно работать с этим расширением, то рекомендую вот этот онлайн сервис по работе с таблицами в Markdown: <https://www.tablesgenerator.com/markdown_tables>.

### Markdown All in One

Для упрощения работы с данным типом файлов можно установить популярное расширение [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one). В нем можно создавать содержание файла, появляются подсказки по картинкам, формулам, спискам. Но лично я его не устанавливаю, так как это расширение плохо дружит с Punto Switcher.

TODO https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode

## Итоговый файл настроек

Привожу файл настроек settings.json, который получился у меня после всех настроек (в частично урезанном варианте):

```json
{
    "workbench.iconTheme": "material-icon-theme",
    "files.autoSave": "afterDelay",
    "editor.wordWrap": "on",
    "editor.rulers": [80, 88, 120],
    "editor.fontFamily": "'JetBrains Mono','Roboto Mono', 'Fira Code', 'Courier New', monospace",
    "explorer.confirmDelete": false,
    "files.associations": {
        "*.inc": "ini"
    },
    "files.trimTrailingWhitespace": true,
    "explorer.confirmDragAndDrop": false,
    "editor.mouseWheelZoom": true,
    "cSpell.language": "en,ru",
    "cSpell.enabled": true,
    "prettier.printWidth": 120,
    "[html]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[jsonc]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "gutterpreview.imagePreviewMaxHeight": 200,
    "colorize.languages": [
        "css",
        "scss",
        "sass",
        "javascript",
        "html",
        "markdown"
    ],
    "security.workspace.trust.untrustedFiles": "open",
    "[markdown]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "python.insidersChannel": "daily",
    "python.formatting.provider": "black",
    "todo-tree.general.tags": [
        "BUG",
        "HACK",
        "FIXME",
        "TODO",
        "XXX",
        "[ ]",
        "[x]"
    ],
    "todo-tree.regex.regex": "(//|#|<!--|;|/\\*|^|^\\s*(-|\\d+.))\\s*($TAGS)",
    "workbench.colorTheme": "FlatUI",
    "cSpell.customDictionaries": {
        "custom-dictionary-user": {
            "name": "custom-dictionary-user",
            "path": "~/.cspell/custom-dictionary-user.txt",
            "addWords": true,
            "scope": "user"
        }
    },
    "code-runner.runInTerminal": true,
}
```

TODO

## Синхронизация настроек в облаке

После всех манипуляций вы наконец получили версию VSCode, настроенную под себя. А теперь представьте, что вам нужно будет всё это повторить на другом компе? Опять всё повторять? Чтобы это не делать, можно синхронизировать настройки с облаком.

В разделе настроек есть кнопка включения синхронизации `Turn on Settings Sync`:

![Кнопка Turn on Settings Sync](img/settings-sync_01.png)

Вас попросят выбрать то, что хотите синхронизировать. Мы хоти всё:

![Выбор синхронизируемых параметров](img/settings-sync_02.png)

Выбираем стабильную или инсайдерскую версию VSCode. Так как всю статью работал с инсайдерской версией, то на скриншоте её и выбираю:

![Выбор версии VSCode](img/settings-sync_03.png)

Теперь нужно выбрать сервис, относительно которого будем авторизоваться для синхронизации. Так как предполагаю, что не у всех есть лицензионная версия Windows, то буду показывать на примере аккаунта GitHub:

![Выбор аккаунта для авторизации](img/settings-sync_04.png)

Потом вас перекинет в браузер, где нужно будет войти в учетку GitHub, а потом подтвердить связь аккаунта GitHub с VSCode:

![Авторизация на GitGub](img/settings-sync_05.png)

![Подтверждение авторизации](img/settings-sync_06.png)

После этого в Chrome предложат открыть VSCode для продолжения работы:

![Переход из Chrome в VSCode](img/settings-sync_07.png)

VScode спросит стоит ли открывать всякие ссылки из Chrome:

![Открытие ссылки из Chrome в VSCode](img/settings-sync_08.png)

Всё. Теперь все настройки, список расширений, темы будут синхронизироваться с облаком. И если вы войдете на другом компе в VSCode и включите там синхронизацию настроек и войдете под своим аккаунтом, то VSCode всё синхронизирует, и вы получите такой же VSCode, что и у вас на первом компе:

![Синхронизация настроек на втором компьютере](img/settings-sync_09.png)

Но, помните, что всякие сторонние программы, которые используется для работы в VSCode (Python, Git и др.) надо будет устанавливать и настраивать отдельно.

И если вы включаете синхронизацию VSCode где-то на публичном компьютере (например, в компьютерной школьном классе), то не забывайте после работы выходить из него, так как вам могут в VSCode сбить настройки, которые будут синхронизированы с основным компьютером.

Чтобы выйти из аккаунта, перейдите в меню к команде `Settings Sync in On`:

![Команда Settings Sync in On](img/settings-sync_10.png)

И потом выберите команду `Settings Sync: Turn Off`:

![Выход из аккаунта](img/settings-sync_11.png)

TODO бэкап настроек https://code.visualstudio.com/docs/editor/settings-sync