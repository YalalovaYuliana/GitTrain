
# Оглавление

1. [Введение](#введение)
2. [Основная часть](#основная-часть)
3. [Заключение](#заключение)

## Введение

Это введение. Вы можете вернуться к [оглавлению](#оглавление).

## Основная часть

Это основная часть документа. Подробнее смотрите в [заключении](#заключение).


# Пользовательская инструкция по использованию графического редактора Paint

![Главное окно](main_window.png)

1. Заглавие изображения. В этой строке отображается название изображения.
2. [Панель меню.](#меню) 
3. Панель инструментов.
4. Рабочая область. В этой области отображается изображение, с которым в текущее время происходит работа. Здесь происходят все действия по рисованию, выделению и другому редактированию изображения.
5. Полоса прокрутки. Изменяет размер кисти и ластика.
6. Строка состояния.
7. Настройки. В данном разделе можно изменить тему приложения на Светлая / Тёмная / Параметр системы. А также узнать версию и информацию о разработчике.

## Панель меню

![Панель меню](panel_menu.png)

1. Файл. Предоставляет доступ к командам: 

	![Файл](file.png)

	* Создать. Создание файла
	* Открыть. Открытие файла из проводника
	* Импортировать на холст. Добавления изображения на холст.

		![Импорт](import.png)

		- Из файла 
		- Со сканера или камеры
	* Последние. Просмотр последних файлов, открытых в Paint
	* Сохранить. При клике откроется проводник для сохранения файла.
	* Сохранить как. Сохранение в формате PNG / JPEG / BMP / GIF / Другой формат

		![Сохранение](save.png)

	* Печать

		![Печать](print.png)

	 	- Печать
	 	- Параметры страницы
	 	- Предварительный просмотр
	* Поделиться
	* Сделать фоном рабочего стола

		![Фон](background.png)

		- Заливка
		- Плитка
		- По центру

	* Свойства изображения. При клике открывается панель со свойствами. В панели можно отредактировать размер изображения. Панель содержит следующие свойства изображения:

		![Свойства изображения](properties.png)

		- Атрибуты  файла
			+ Последнее сохранение
			+ Размер на диске
			+ Разрешение. В точках на дюйм.
		- Единицы измерения:
			+ Дюймы
			+ Сантиметры
			+ Пиксели
		- Размер изображения. Высота и ширина изображения. По умолчанию в дюймах. В "Единицы измерения" выше можно изменить на пиксели или сантиметры. Размер изображения будет пересчитан автоматически. В полях ввода ширины и высоты можно установить собственные значения, после нажатия кнопки "ОК" на панели свойств, они будут применены к текущему файлу. При нажатии на кнопку "Отмена" на панели свойств, изменения применены не будут.
	* Выйти. При клике, если текущий файл не сохранён откроется панель сохранения работы со следующими кнопками:

		![Сохранение](save.png)


		- Сохранить. При клике откроется проводник для сохранения файла.
		- Не сохранять. Программа закроется без сохранения текущих изменений.
		- Отмена. Закрытие панели сохранения.
2. Изменить. Предоставляет доступ к командам:

	![Изменение](edit.png)

	* Вырезать
	* Копировать
	* Вставить
3. Вид. Предоставляет доступ к командам:

	![Вид](view.png)

	* Масштаб
		- 100%
		- Увеличить
		- Уменьшить
		- По размеру окна
	* Линейки. Включает, при повторном клике отключает линейки вокруг холста.
	* Линии сетки. Включает / выключает линии сетки на холсте.
	* Строка состояния. Включает / выключает строку состояния. 
4. Кнопка "Сохранить"

	![Кнопка сохранения](save_button.png)

5. Кнопка "Поделиться". Открывает панель отправки изображения.

	![Кнопка поделиться](share_button.png)

6. Кнопка "Отменить". Отменяет предыдущее действие пользователя на холсте. Кнопка "Повторить". Возвращает отменённое действие.

	![кнопки отменить / повторить](undo_redo_buttons.png)


## Панель инструментов

![панель инструментов](panel_tools.png)

Панель инструментов состоит из следующих разделов:

1. Выделение. Используется для выделения определенной области на холсте. Состоит из следующих элементов:

	![раздел выделение](stick.png)

	* Прямоугольник. Выделение области в форме прямоугольника. Достаточно растянуть прямоугольник на холсте, зажав левую клавишу мыши.
	* Произвольная форма. Необходимо обвести нужную область, зажав левую клавишу мыши.
	* Выбрать всё. Выделение всего холста.
	* Обратить выделение. Выделение области за всей до этого выделенной области.
	* Прозрачное выделение. Выделение области без фона.
	* Удалить. Удаление выделенной области.

2. Изображение. Используется для изменения изображения:

	![раздел изображение](picture.png)

	* Обрезать. Удаление всего вне выделенной области.

	![обрезать](cut.png)

	* Удалить фон. Автоматически удаляет фон приложения.

	![удалить фон](delete_background.png)

	* Повернуть. Поворот изображение по / против часовой стрелки.

	![Повернуть](rotate.png)

	* Перевернуть. Отражение изображения по вертикали / горизонтали.

	![Перевернуть](reflect.png)
	
	* Изменить размер и наклонить. Открывает панель изменения размера и наклона изображения.

	![Изменить размер и наклонить](change_size.png)

	В данной панели можно изменить размер изображения в пикселях или процентах. Также установить наклон изображения в градусах.

	![Изменить размер и наклонить панель](change_size_panel.png)


2. Инструменты. Предоставляет доступ к базовым инструментам для работы с приложением.

	![Инструменты](tools.png)

	* Карандаш. Используется для рисования на изображении.
	* Ластик. Используется для стирания нарисованного.
	* Заливка. Используется для заполнения цветом выделенной области или всего изображения.
	* Пипетка. Используется для опрееления и взятия цвета с изображения. Необходимо навести пипетку на необходимый цвет на изображении и нажать левую клавишу мыши.
	* Текст. Используется для создания области для набора текста на изображении. Открывает панель с настройками текста. Необходимо кликнуть на нужное место на изображении для добавления текста.

	![Панель с настройками текста](panel_text.png)

	* Экранная лупа. Используется для приближения той области изображения, на которую было совершено нажатие лупы.

3. Кисти. Выбор стиля кисти.

![Кисти](brushes.png)

4. Фигуры. Добавление фигур на изображение. Содержит следующие элементы:

	![Фигуры](shapes.png)

	* Область с выбором фигуры.
	* Контур фигуры. Стиль контура фигуры. Необходимо сначала добавить фигуры на изображение для получения доступа к данной настройке.

	 ![Контур](kontur.png)

	* Заливка фигуры. Заполнение фигуры цветом.

	![Заливка фигуры](zalivka.png)

	* Размер. Толщина контура фигуры.

	![Толщина контура фигуры](thick.png)

4. Цвета. Состоит из следующих элементов:

	![Цвета](colors.png)

	* Область со стандартным набором цветов.
	* Изменить цвет. Открывает панель с цветовым квадратом. На панели можно указать числовые значения цвета, добавить пользовательски цвета.

	![Панель цветов](panel_colors.png)

5. Copilot. Содеожит следующие элементы:

	![Copilot](copilot.png)

	* Генеративное удаление. Удаление фона и заполнение на основе ближайших элементов.
	* Удаление фона изображения.

6. Слои. Открывают панель слои в рабочей области.

	![Слои](layers.png)


	![Панель слои](panel_layers.png)

	1. Создать слой. Добавление нового слоя на панель.
	2. Область со всеми слоями. Необходимо кликнуть на нужный слой, чтобы переключиться на него.
	3. Кнопка сокрытия / открытия слоя.
	4. Цвет фона. При клике открывает панель с выбором цвета фона. При нажатии на кнопку сокрытия слоя, делает фон прозрачным.

## Строка состояния

![строка состояния](stripe.png)

Панель необходима для работы с изображения по слоям. Состоит из следующих элементов: 

Включает следующие элементы: 
1. Координаты курсора на холсте
2. Размер выделенной области
3. Размер холста в пикселях
4. Кнопка для масштабировния холста по рамеру окна
5. выпадающий список для масштабирования холста в процентах
6. Полоса прокрутки для масштабирования холста


## Заключение

Это заключение. Вернуться к [введению](#введение).




