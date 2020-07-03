# MangaWatcher

## Описание
Приложение предназначено для отслеживания выхода новых глав манги, которую добавил пользователь

## Как пользоваться
Первое что видит пользователь, при открытии приложения - это стартовая страница.
Стартовая страница представлена ниже.

![Стартовая страница](./img/tutorial/start_page.jpg)

Для начала необходимо добавить сайт, с которого приложение будет считывать информацию.
После нажатия "Добавить сайт", откроется список сайтов. Если вы впервый раз запустили приложение, то он будет пустым.

![Список сайтов](./img/tutorial/sites_list.jpg)

Нажав "Добавить сайт", откроется форма для ввода xpath к необходимой информации на сайте.

![Форма для добавления сайта](./img/tutorial/add_site_form.jpg)

Если вы не знаете, что такое XPath, то не беспокойтесь. Далее я объясню откуда их взять.
Для начала откройте сайт с мангой (Для примера я буду использовать сайт MangaLib)

![Сайт MangaLib](./img/tutorial/mangalib.jpg)

Выбрав сайт для добавления, введите его название (Название может быть любым)

![Название сайта](./img/tutorial/site_name.jpg)

Далее необходимо ввести XPath названия манги. Для этого нажмите ПКМ по названию манги в браузере и выберите "Посмотреть код элемента". После этого откроется окно с кодом сайта.

![Код сайта](./img/tutorial/site_code.jpg)

Наведя мышку на выделенный фрагмент кода, нажмите ПКМ, далее "Скопировать" -> "Скопировать XPath"

![XPath названия](./img/tutorial/title_xpath.jpg)

Далее необходимо вставить XPath в форму для добавления сайта

![Название манги](./img/tutorial/title_name.jpg)

Похожим образом получается XPath описания манги, картинки и последней главы

![Заполненые xpaths](./img/tutorial/filled_xpaths.jpg)

После заполнения всех XPath, вам необходимо ввести тестовую ссылку.
**Что такое тестовая ссылка?** 
Тестовая ссылка - это страница сайта, по которой будут оптимизироваться XPath.
**Для чего это надо?**
Некоторые сайты использую несколько шаблонов страниц для отображения манги. Это создает ситуации, когда с одного и того же сайта одна манга может считаться нормально, а другая - нет.

Вставьте в поле "Тестовая ссылка" ссылку на страницу, с которой копировали все XPath.
В результате так должна выглядеть форма для добавления сайта:

![Заполненая форма](./img/tutorial/full_site.jpg)

После нажатия "Добавить сайт", сайт появится в списке сайтов

![Сайт в списке](./img/tutorial/full_site_list.jpg)

Далее нажмите на кнопку "Добавить мангу" под пустым списком манги, выберите сайт, и введите ссылку.

![Добавление манги](./img/tutorial/add_manga.jpg)

Если все ссылки введены правильно, то в списке появится манга.
Когда выйдет новая глава, в правом нижнем углу высветиться уведомление, а манга в списке будет выделена зеленым цветом.

![Новая глава](./img/tutorial/new_manga.jpg)

При нажатии на мангу в списке, выведется информация о этой манге: название, описание и номер новой главы.

![Информация о манге](./img/tutorial/manga_info.jpg)

Приложение может работать в фоновом режиме. Для этого нужно его просто закрыть, тогда выведется уведомление о переходе приложения в фоновый режим.

## Пожелания
Удачного использования!
Я буду обновлять приложение по мере возможностей.