

[![Telegram](https://img.shields.io/badge/Telegram-t.me%2Ftheonlywiilldii-brightgreen)](https://t.me/theonlywiilldii) [![VK](https://img.shields.io/badge/VK-vk.com%2Ftheonlymark-red)](https://vk.com/theonlymark)

![](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=bredberry&theme=solarized_dark)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&width=435&lines=%D0%AF+%D0%B7%D0%B0%D0%B5%23%D0%B0%D0%BB%D1%81%D1%8F+%D1%8D%D1%82%D0%BE+%D0%B4%D0%B5%D0%BB%D0%B0%D1%82%D1%8C)](https://git.io/typing-svg)

# Основы HTML/CSS

- [X] **Язык `HTML`**
  >Язык `HTML` - это основа web сайтов, с его помощью создается каркас страницы, которую вы видите в браузере.
Заголовки, абзацы и другие блоки можно выделить и на странице сайта. Это делается с помощью `HTML` тегов.

- [X] **Что такое `HTML` теги?**
  >`HTML теги` - это специальные команды для браузера. Они говорят ему, что, к примеру, следует считать заголовком страницы, а что абзацем <details><summary> Подробнее </summary>• Теги строятся по такому принципу: уголок <, потом имя тега, а потом уголок >, вот так: <имя тега>. Имя тега может состоять из английских букв и цифр. Примеры тегов: `<h1>`, `<p>`, `<b>`.<br>
• Теги обычно пишутся парами - открывающий тег и соответствующий ему закрывающий. Разница между открывающим и закрывающим тегами в том, что в закрывающем теге после уголка < стоит слеш /.<br>
• К примеру, `<p>` - так я открыл тег p, а так - `</p>` - я его закрыл. Все, что попадает между открывающим и закрывающим тегами, подпадает под воздействие нашего тега.<br>
• Бывают теги, которые не нужно закрывать, например, `<br>` или `<img>`.
</details>

- [X] **Атрибуты**
  > В тегах также могут размещаться атрибуты - специальные команды, которые расширяют действие тега.<details><summary> Подробнее </summary>• Атрибуты размещаются внутри открывающего тега в таком формате:<br> <тег атрибут1="значение" атрибут2="значение">.<br>• Кавычки могут быть любыми - одинарными или двойными, допустимо их вообще их не ставить, если значение атрибута состоит из одного слова (но это не желательно). </details>

- [X] **Язык `CSS`**
  > Язык `CSS` расширяет возможности языка `HTML`. Он позволяет менять цвета, шрифты, фон, в общем заниматься красотой сайта. А `HTML`, соответственно, отвечает за структуру сайта.
<br>

## Структура `HTML` документа
> Ниже дан пример оборачивания основных, самостоятельных `HTML`-элементов, которые сами по себе не очень полезны. Давайте посмотрим, как самостоятельные элементы объединяются для формирования всей `HTML` страницы:
```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Тестовая страница</title>
  </head>
  <body>
    <p>Это — моя страница</p>
  </body>
</html>
```
- `<!DOCTYPE html>` Показывает браузеру тип документа, сообщает его версию и язык.
- `<html></html>` Содержит в себе всё содержимое на всей странице.
- `<head></head>` Данный элемент выступает в качестве контейнера для всего содержимого, которое вы хотите включить в HTML документ, но не хотите показывать посетителям вашей страницы.
- `<meta charset="utf-8">` Этот элемент устанавливает в качестве символьной кодировки для вашего документа `utf-8` , который включает большинство символов из всех известных человечеству языков.
- `<title></title>` Устанавливает заголовок вашей страницы, который появляется во вкладке браузера
- `<body></body>` Он содержит весь контент, который вы хотите показывать посетителям вашей страницы, — текст, изображения, видео, игры, проигрываемые аудио дорожки или что-то ещё.

## **Базовые теги**

| ТЕГ | Описание |
|:-----:|:----------:|
| `<!--...-->` | тег для добавления комментариев в документ<br>Помещённые внутри него теги не интерпретируются браузером. |
| `<!DOCTYPE>` | показывает браузеру тип документа, сообщает его версию и язык. |
| `<html></html>` | корневой тег, который сообщает браузеру, что это HTML-документ. Все остальные элементы помещаются внутри него. |
| `<head></head>` | контейнер, в который помещаются метаданные документа, не видимые пользователям, но считываемые поисковыми роботами:<br> например, `<title>` или `<style>`. |
| `<meta>` | тег для оформления метаданных документа, используемых браузером для обработки страницы, а поисковиками — для индексации. |
| `<body></body>` | тег, обрамляющий видимую пользователям часть документа. Всё, что вы укажите внутри этого контейнера, отобразится на странице. Тег `<body>` имеет несколько атрибутов, позволяющих управлять **цветами**. |
| `<body bgcolor=?>` | цвет фона документа в формате RGB. |
| `<body text=?>` | цвет текста. |
| `<body link=?>` | цвет гиперссылок. |
| `<body vlink=?>` | цвет гиперссылок, по которым уже переходили. |
| `<body alink=?>` | цвет гиперссылок при нажатии. |
| `<title></title>` | метатег, который задаёт название страницы, отображаемое на вкладке браузера. |
| `<header></header>` | определяет содержимое блока с вводной информацией сайта или группой ссылок. |

## **Форматирование текста**

| ТЕГ | Описание |
|:-----:|:----------:|
| `<h1></h1>......<h6></h6>.` | теги заголовков, от самого большого к самому маленькому. |
| `<b></b>` | жирный текст без придания важности выделенному фрагменту. |
| `<strong></strong>` | расставление акцентов в тексте путём выделения его фрагментов полужирным начертанием. |
| `<i></i>` | выделение текста курсивом без придания важности. |
| `<del></del>` | зачёркивает текст, помечая его удалённым. |
| `<s></s>` | отображает перечёркнутый текст. |
| `<ins></ins>` | подчёркивает текст, визуально выделяя внесённые изменения. |
| `<u>` | подчёркивание без дополнительного акцентирования внимания. |
| `<em></em>` | расставление акцентов путём выделения фрагментов текста курсивом. |
| `<mark></mark>` | выделение частей текста жёлтым маркером. |
| `<tt></tt>` | имитация текста, набранного на печатной машинке. |
| `<small></small>` | отображение фрагмента с меньшим кеглем шрифта, чем у остального текста. |
| `<sub></sub>` | подстрочное начертание символов. |
| `<sup></sup>` | надстрочное начертание символов. |
| `<cite></cite>` | оформление цитат. |
| `<address>` | добавление контактов или подписи автора. При открытии в вею-браузере выделяется курсивом. |
| `<pre></pre>` | вывод неформатированного текста с сохранением пробелов и особенностей переносов. |
| `<p></p>` | контейнер для абзаца. |
| `<br>` | переносит текст на другую строку без создания абзаца. |
| `<blockquote> </blockquote>` | отступы с обеих сторон для оформления цитаты или врезки. |
| `<q></q>` | краткое цитирование. |
| `<dl></dl>` | контейнер для размещения термина и его определения. |
| `<dt>` | добавление термина. |
| `<dd>` | добавление определения понятия |
| `<dfn>` | выделение термина курсивом. Последующий текст должен раскрывать понятие. |
| `<abbr> ` | указывает, что текст является аббревиатурой или акронимом. Для добавления пояснения используется атрибут `title`. |
| `<ol></ol>` | список с цифрами. |
| `<ul></ul>` | список со значками. |
| `<li>` | отметка каждого элемента перечня (цифра или значок в зависимости от типа списка). |
| `<a></a>` | добавление гиперссылки в текст. Имеет обязательный атрибут href, в котором указывается ссылка или якорь. Внутри контейнера помещается текст, при нажатии на который происходит переход на другую страницу или другое место на этой же странице. |
| `<code></code>` | выделение фрагмента кода с помощью шрифта monospace.  |


## **Встраивание элементов**

| ТЕГ | Описание |
|:-----:|:----------:|
| `<img></img>` | вставка изображения. Имеет атрибут src, который указывает на адрес нужного файла. Есть и другие атрибуты: |
| `<img src="name" align=?>` | выравнивание к одной из сторон документа. Например, значение right переместит рисунок в правый край, а left — в левый. |
| `<img src="name" border=?>` | позволяет настроить в пикселях толщину рамки вокруг изображения. |
| `<hr>` | размещает на странице горизонтальную линию. Имеет несколько атрибутов. |
| `<hr size=?>` | устанавливает высоту линии. |
| `<hr width=?>` | устанавливает ширину линии. |
| `<hr noshade>` | убирает тень у линии. |
| `<hr color=?>` | задаёт цвет линии. |

## **Работа с таблицами**

| ТЕГ | Описание |
|:-----:|:----------:|
| `<table></table>` | размещает таблицу. Все остальные теги для форматирования таблиц должны находиться внутри это контейнера. |
| `<thead></thead>` | определяет заголовок. |
| `<tbody></tbody>` | отмечает тело таблицы. |
| `<td></td>` | создаёт одну ячейку. |
| `<th></th>` | указывает на заголовок ячейки. |
| `<tr>` | создание одной строки.   |
| `<tfoot></tfoot>` | показывает нижний колонтитул. |
| `<caption></caption>` | определяет название (заголовок) таблицы. |
| `<col>` | позволяет указать ширину и другие параметры одной или нескольких колонок. |

# Горячие клавиши в VS Code

| Название ГК | Клавиши |  |
|----------------|:---------:|----------------|
| Вызвать поиск | <kbd>Ctrl</kbd>+<kbd>F</kbd> | <details><summary> Подробнее </summary>Нажмите Ctrl + F (Windows) или ⌘Cmd + F (macOS). <br> Введите искомое — высветятся все найденные места. Остаётся перемещаться по ним (стрелочками в форме поиска).</details> |
| Закомментировать код | <kbd>Ctrl</kbd>+<kbd>/</kbd> | <details><summary> Подробнее </summary>Выделите нужный участок и нажмите Ctrl + / (Windows) или ⌘Cmd + / (macOS). Если выделения нет, то закомментируется строка, в которой стоит курсор (раскомментировать её можно так же).</details> |
| Перейти к строке под номером | <kbd>Ctrl</kbd>+<kbd>G</kbd> | <details><summary> Подробнее </summary>Нажмите Ctrl + G (Windows) или ⌃Ctrl + G (macOS), введите номер строки — и вам не придётся листать вручную.</details> |
| Поменять строку местами с соседней | <KBD>Alt</kbd> + <KBD>↑</kbd> / <KBD>↓</kbd> | <details><summary> Подробнее </summary> Поставьте курсор на нужную строку и нажмите Alt + ↑ / ↓ (Windows) или ⌥Option + ↑ / ↓ (macOS). |
| Дублировать строку | <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<KBD>↑</kbd> / <KBD>↓</kbd>| <details><summary> Подробнее </summary> Поставьте курсор на нужную строку и нажмите Shift+Alt + ↓ / ↑ (Windows) или ⇧Shift + ⌥Option + ↓ / ↑ (macOS). |
| Отформатировать листинг | <KBD>Shift</kbd> + <KBD>Alt</kbd> + <KBD>F</kbd> | <details><summary> Подробнее </summary> Жмите Shift + Alt + F (Windows) или ⇧Shift + ⌥Option + F (macOS). |
| Множественный ввод | <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<KBD>↑</kbd> | <details><summary> Подробнее </summary> > Зажмите Alt (в Windows) или ⌥Option (в macOS) и кликайте левой кнопкой мышки там, куда нужно добавить курсор. <BR> > Выделите несколько строк, зажав среднюю кнопку мыши. В каждой из выделенных строк появится по курсору. <BR> > Если лень кликать мышкой, то дублировать курсор можно так: Ctrl + Alt + ↑ / ↓ (Windows) или ⌥Option + ⌘Cmd + ↑ / ↓ (macOS). |
| Множественное редактирование | <kbd>Ctrl</kbd>+<kbd>D</kbd> | <details><summary> Подробнее </summary>Выделите мышью символы и нажмите Ctrl + D (Windows) или ⌘Cmd + D (macOS). Если нажать больше одного раза, то к выделению добавится ещё одно вхождение того же куска далее по тексту. Затем можно редактировать все выделенные области сразу (подсвечиваются синим).</details> |
| Сокращения для тегов и свойств | <details><summary> Подробнее </summary>![GitHub](https://skillbox.ru/upload/setka_images/16494502022021_950616b1b3098f817fe7027e1dfa02169666ef55.gif) </details>| <details><summary> Подробнее </summary>Вы набираете один-два символа, а автоподстановка предлагает название тега (в паре с закрывающим) для HTML или название свойства для CSS. Дождитесь, пока редактор подсветит предлагаемый вариант (когда их несколько — выберите нужный), и нажмите Tab или Enter. </details> |
| Сокращения для многострочных конструкций | <details><summary> Подробнее </summary>![GitHub](https://skillbox.ru/upload/setka_images/16494702022021_b0db57166028d10b861a6ceedc3e58d5dd8b10d0.gif) </details> | <details><summary> Подробнее </summary>Достаточно набрать `ul>li*4>a.link`, дождаться подсветки этого варианта (он в выпадашке один) и нажать Tab или Enter, а редактор сам вставит развёрнутую конструкцию. Это очень ускоряет работу, хотя поначалу и похоже на волшебство. </details> |
| Вызываем терминал | <kbd>Ctrl</kbd>+<kbd>&#96;</kbd> | <details><summary> Подробнее </summary>Нажать Ctrl + &#96; для Windows или ⌃Ctrl + &#96; для macOS. </details> |


# Система контроля версий Git
![GitHub](https://miro.medium.com/max/4800/1*cTPHRuyn46e4Su4QJ7S5NQ.gif)


- [X] **Первоначальная настройка Git** :blue_heart:

> Первое, что вам следует сделать после установки Git — указать ваше имя и адрес электронной почты.
  ```
    git config --global user.name ""
    git config --global user.email ""
  ```

> Создать локально новый репозиторий
  ```
    git init
  ```

- [X] **Просмотр конфигураций удаленных репозиториев** :green_heart:

> Список ваших удаленных подключений к другим репозиториям.
  ```
    git remote
  ```

> Аналогично команде выше, но включает URL-адрес каждого подключения.
  ```
    git remote -v
  ```

> Создание нового подключения к удаленному репозиторию.
  ```
    git remote add <name> <url>
  ```

> Удаление подключения к удаленному репозиторию с именем.
  ```
    git remote rm <name>
  ```

- [X] **Работа с удалёнными репозиториями** :purple_heart:
  
> Клонировать существующий репозиторий
  ```
    git clone <url>
  ```

- [X] **Загрузка репозитория на сайт/локальный сервер** :heart:
  
+ Локальный
  
> Добавить все измененные файлы в индекс репозитория.
  ```
    git add .
  ```

> Запись индексированных изменений в репозиторий Git.
  ```
    git commit -m "Первый коммит"
  ```

> Переимновать индексированные изменения

  ```
    git commit --amend -m "Новый коммит"
  ```
- Сайт

>Отправка изменений
  ```
  git push -u origin main
  ```

> Извлечь из указанного удаленного репозитория копию текущей ветки и немедленно слить ее с локальной копией. 

  ```
  git pull
  ```

- [X] Работа с ветками в Git :heartpulse:
> Команда git branch — главный инструмент для работы с ветвлением. С ее помощью можно добавлять новые ветки, перечислять и переименовывать существующие и удалять их.
>> Список всех существующих веток
  ```
    git branch -av
  ```

> Переключение в ветки
  ```
    git checkout <ветка>
  ```

> Создать новую ветку
  ```
    git branch <новая-ветка>
  ```

> Создать новую ветку и сразу переключится в нее
  ```
    git checkout -b <новая-ветка>
  ```

> Удалить локальную ветку
  ```
    git branch -d <ветка>
  ```

- [X] **Локальные изменения** :yellow_heart:
  
> Файлы в рабочей директории были изменены
  ```
    git status
  ```

> Изменения в отслеживаемых файлах
  ```
    git diff
    git diff <commit1> <commit2>
  ```

- [X] **История коммитов** :alien:

> Показать всю историю коммитов начиная с последних
  ```
    git log
  ```
> Показать историю изменений определенного файла
  ```
    git log -p <файл>
  ```
> Кто, какие и когда изменения вносил в <файл>
  ```
    git blame <файл>
  ```

- [x] **Отмена** :hankey:

> Удалить все локальные изменения в рабочем каталоге
>> Это самый прямой, ОПАСНЫЙ и часто используемый вариант. При использовании аргумента `--hard` указатели в истории коммитов обновляются на указанный коммит. Затем происходит сброс раздела проиндексированных файлов и рабочего каталога до указанного коммита. Все предыдущие ожидающие изменения в разделе проиндексированных файлов и рабочем каталоге сбрасываются в соответствии с состоянием дерева коммитов. Это значит, что любая работа, находившаяся в состоянии ожидания в разделе проиндексированных файлов и рабочем каталоге, будет потеряна.
  ```
  git reset --hard <хэшcommit>
  ```

> Это режим работы по умолчанию. Указатели ссылок обновляются. Раздел проиндексированных файлов сбрасывается до состояния указанного коммита. Любые изменения, которые были отменены в разделе проиндексированных файлов, перемещаются в рабочий каталог.

  ```
  git reset --mixed <хэшcommit>
  ```

> При передаче аргумента `--soft` выполняется обновление указателей, и на этом операция сброса останавливается. Раздел проиндексированных файлов и рабочий каталог остаются неизменными. Четко продемонстрировать такое поведение довольно сложно. 

  ```
  git reset --soft <хэшcommit>
  ```

> Сбрасывает раздел проиндексированных файлов и рабочий каталог до состояния последнего коммита. Флаг `--hard` говорит Git, что нужно не только отменить изменения в разделе проиндексированных файлов, но и перезаписать все изменения в рабочем каталоге. Другими словами, эта команда уничтожит все неотправленные изменения, поэтому перед ее использованием убедитесь, что вы действительно хотите удалить ваши локальные наработки.

```
  git reset --hard
```

> Вернуть файл из стейджинга, но оставить изменения в нем неприкосновенными.

```
  git restore --staged myFile.txt
```

> Отменить локальные изменения в конкретном файле

```
  git restore myFile.txt
```

![END](https://psv4.userapi.com/c237331/u559371293/docs/d12/1a3a199c5170/1640455153605.gif?extra=ko8YyRMV1ojxhMeXxim_YI92ExA_QehLoVxSrw0Zsd68JICv9rbMOXM4EcDAq6X7zgHdtgsXeldrC-kbgnO0_DOKipA3YdUItvr_P9pVA_DjASJSnjU1YmOfFFj2sxtZUNRAOe2VpWRGkYYmFv2xvSVqVWg)![END](https://psv4.userapi.com/c237331/u559371293/docs/d12/1a3a199c5170/1640455153605.gif?extra=ko8YyRMV1ojxhMeXxim_YI92ExA_QehLoVxSrw0Zsd68JICv9rbMOXM4EcDAq6X7zgHdtgsXeldrC-kbgnO0_DOKipA3YdUItvr_P9pVA_DjASJSnjU1YmOfFFj2sxtZUNRAOe2VpWRGkYYmFv2xvSVqVWg)![END](https://psv4.userapi.com/c237331/u559371293/docs/d12/1a3a199c5170/1640455153605.gif?extra=ko8YyRMV1ojxhMeXxim_YI92ExA_QehLoVxSrw0Zsd68JICv9rbMOXM4EcDAq6X7zgHdtgsXeldrC-kbgnO0_DOKipA3YdUItvr_P9pVA_DjASJSnjU1YmOfFFj2sxtZUNRAOe2VpWRGkYYmFv2xvSVqVWg)