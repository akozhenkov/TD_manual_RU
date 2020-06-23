# TopoDroid manual RU

[![Join the chat at https://gitter.im/akozhenkov/TD_manual_RU](https://badges.gitter.im/akozhenkov/TD_manual_RU.svg)](https://gitter.im/akozhenkov/TD_manual_RU?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Translation of the Topodroid man pages into Russian.

Перевод официального руководства программы Topodroid на Руссий язык.
Для просмотра руководства откройте файл manual00.htm в интернет браузере.
Текущая версия руководства отражена в файле manifest. 
Topodroid сверяет эту информацию с "текущей" версией руководства в topodroid/res/values/user_man.xml и обновляет при необходимости.

TopoDroid RELEASE NOTES

5.0.4e Beta 2020-06-16
* Экспорт в SVG с разбивкой по слоям и группам.

5.0.4a 2020-06-11
* Исправления ошибок, обновление переводов.

5.0.3g-h 2020-05-21
* Переделана система инсталяции под Android 10. Для предыдущих версий ОС изменений нет.

5.0.3c Beta 2020-05-11
* Исправления: отсутсвие указания локали в экспортированных файлах.

5.0.3a-b Beta 2020-05-04
* Текущий инструмент рисования выделен цветом.
* Новая настройка:  обновление данных съёмки на абрисе при каждой передаче данных.
* Исправления: магнитное склонение вkml, экспорт xvi в th2 файл, xvi экспорт для поперечных сечений, a few strings.
* Обновления руководства и переводов.

5.0.2g 2020-04-20
* Новая настройка: Создать конфигурационный файл Therion.
* Отслеживание версий перевода руководства пользователя.
* Исправления csurvey xml, падение при прокрутке списка.

5.0.2a 2020-04-08
* Менеджер проектов пещер встроен в TopoDroid
* Базовая папка TopoDroid в директории Documents (Android-11 и выше)
* Перерписан функционал отображения 3D модели рельефа.
* Новая настройка: едиинцы измерения измерителя расстояний.
* Исправления экспорта полигонов
* Обновления руководства и переводов.

5.0.1g-i 2020-03-28
* Реорганизация кода
* Базовая папка TopoDroid в директории Documents (Android-11 и выше)

5.0.1d Beta 2020-03-09
* Исправления экспорта полигонов

5.0.1a/b - 2020-03-08
* Исправления для Android 10
* Удален старый формат экспорта в cSurvey.
* Отображение серых областей по краям в случае если включено перетаскивание за край абриса.
* Ревизия кода.
* Обновления руководства и переводов.

5.0.0d - Beta 2020-02-14
* Тройная панель инструментов рисования.

5.0.0b - Beta 2020-02-13
* Разделение съёмок и перенос замеров в другую съёмку.
* Мелкие исправления: прилипание к точке; длинное нажатие на кнопку инструментов рисования.
* Обновления руководства и переводов.

5.0.0a - 2020-02-04
* Минимальная версия ОС Android 4.3 (api-18).
* Нижняя панель инструментов рисования [рекомендуется опробовать перед съёмкой].
* Режим съёмки двумя DistoX.
* Новый формат экспорта cSurvey.
* TdManager, опционально для соединеия съёмок.


4.2.4f-g - 2020-01-03/07
* Обновления условных обозначений ( R. Severo)
* Исправления ошибок.

4.2.4a - 2019-12-23
* V. 5.0.0 Будущий релиз
* Геомагнитная модель WMM-2020
* Ревизия обработки обратных замеров DistoX.
* Поддержка абрисов состоящих из нескольких скрапов (кусков).
* Новые настройки экспорта cSurvey - выбор формата данных cSurvey. (cSurvey v. 1.20 или новее)
* Новый формат экспорта абрисов: Tunnel XML
* Экспорт абриса в Shp: привязанный к координатам план.
* Экспорт абриса в SVG: опциональный формат roundtrip.
* Диалог настройки импорта Compass и VisualTopo.
* Исправления: диалог перезагрузки абриса, службный сегмент файла .th2, поиск замеров "без развертки" дейсвие по долгому нажатию, классы сплеев, Диалог редактирования свойств измерений,
Групирование калибровочных измерений, фильтр выбора объектов на абрисе, проверка прошивки дисто, контуры поперечных сечений, ЛПВН на пикете,
Экспорт в DXF, страницы помощи в диалогах, импорт VisualTopo, Разделение абрисов и другие мелкие исправления.
* Обновления руководства и переводов.

4.2.3b-c - beta 2019-12-17
* Исправления: диалог перезагрузки абрса, диалог экспорта th2 xtherion, поиск по длинному нажатию.
* Переделано присвоение классов сплеев.
* Новые настройки экспорта cSurvey - выбор формата данных cSurvey. (cSurvey v. 1.20 или новее)
* Обновления руководства и переводов.

4.2.3a - Beta 2019-12-11
* Обновлены коэффициенты WMM.

4.2.2d-e - Beta 2019-12-09
* Исправления в диалоге редактирования свойств замера.
* Политика группирования может быть выбрана в диалоге (тестовый уроввень) - По умолчанию выбирается в настройках.
* Передача ожидаемого типа данных в коммуникационный слой distox - пока используется только в журнале.

4.2.2c - Beta 2019-12-03
* Исправления: фильтр выбора объектов, проверка прошивки, контуры сечений, ЛПВН на пикете.
* Классы сплеев: ревизия интерфейса.
* Обновления руководства и переводов.

4.2.2a - Beta 2019-11-25
* Ревизия аудио и фото классов.
* Новый формат экспорта абрисов: Tunnel XML

4.2.1e - Beta 2019-11-18
* Исправления: экспорт мульти-скарп абрисов.
* Исправления: экспорт сплайн линий в Dxf.

4.2.1d - Beta 2011-11-15
* DistoX A3 очистка памяти.
* Обновления руководства и переводов.
* Исправления- экспорт мульти скрап абрисов в формат Therion.

4.2.1b - Beta 2011-11-11
* Поддержка абрисов состоящих из нескольких скрапов (кусков).
* Длинное нажатие на кнопки в диалогах открывает страницу руководства.
* Руководсво открыввается при нажатии кнопки громкости в диалогах.
* Сохранение флага обратных замеров DistoX в базе данных замеров.
* Выделение обратных замеров DistoX желтым цветом.
* Переосмыслено значение настройки "DistoX обратный замер": если включен обратный замер DistoX азимут и угол будут разворачиваться.
* Поиск замеров без направления развертки только среди замеров между пикетами.
* Настройки импорта данных Compass and VisualTopo.
* Экспорт абриса в Shp: привязанный к координатам план. 
* Экспорт абриса в SVG: опциональный формат roundtrip.
* Автоматический экспорт поперечных сечений в Therion.
* Исправления:
- Импорт VisualTopo
- версия программы в zip архивах
- проверка null символов
- экспорт в dxf
- переместить замер в следующий сегмент
- разделение абриса
* Обновления руководства и переводов.

5.0.0 Next

* При экспорте абрисов в формат Therion абристы сечений экспортируются автоматически.
* Обновления руководства и переводов.

ТОЛЬКО ДЛЯ ТЕСТОВ - нет на Google Play
4.1.4S
* Исправления: разделение абриса на части.
4.1.4P
* 5.0.0 pre-alpha для тестирования.


4.1.4D-E 2019-10-22
* Исправлен экспорт магнитного склонения в формат Survex.
* Дополнительные условные обозначения в zip архиве.
* Ревизия условных обозначаний:
* Новые условные обозначения "спелео" UIS - "плюс", "минус" and "плюс-минус".
* Новые условные обозначения "антропогенез" и другие (by R. Severo).
* Ссылки в приложении.
* Исправления: текущий пикет, экспорт точек в SVG для Inkscape, сообщенте при создании zip, другие мелкие ошибки.
* Обновления руководства и переводов.

4.1.4B Beta 2019-10-16
* Новые условные обозначения "антропогенез" и друние (by R. Severo).
* Новые условные обозначения "спелео" UIS - "плюс", "минус" and "плюс-минус".
* Группы условных обозначений.
* Ссылки в приложении.
* Исправления: текущий пикет и др баги.
* Обновления руководства и переводов.

4.1.4.wa 2019-10-16
* Исправления ошибок

4.1.4z Beta 2019-10-10
* Переделана логика резервного копирования абрисов.
* Переделана загрузка абрисов из бекапа, появилось превью.
* Исправления: импорт формата compass, другие баги.
* Обновления руководства и переводов.

4.1.4y Beta 2019-10-08
* Комбинированные действия для линий/областей.
* Вставка доп. точек в линии и границы областей.
* Заливка фона областей
* Обновления руководства и переводов.

4.1.4x Beta 2019-10-07
* Кнопка "руководство" в окне описания.
* Ширина всплывающих текстовых полей.

4.1.4w - 2019-10-04
* Исправления: диалог первичной настройки, ориентация экрана, валидация калибровки, легенда и альтитуда, файлы условных обозначений, импорт VisualTopo, прилипание границ области, экспорт shapefile.
* Проблема с наименованием пикетев: добавлено в журнал событий (выключено по умолчанию).
* Новые настройки: экспорт в VisualTopo, ориентация экрана.
* Выделение текущего пикета зеленым цветом на экране абрисов.
* Обновления руководства и переводов.

4.1.4u - Beta 2019-10-02
* Возможность выбтрать ориентацию экрана: портрет, альбом, авто.
* Ревизия алгоритма наименования пикетов.

4.1.4t - Beta 2019-10-01
* Мелкие исправления.
* Ревизия и улучшения кода
* Ориентация экрана, новая настройка.
* Проблема с наименованием пикетов: добавлено журналирование.
* Обновления руководства и переводов.
* Номер текущей версии в автоматически созданном руководстве в формате PDF.

4.1.4r - Beta 2019-09-24
* Исправлено: проверка калибровки, а также легенда калибровки.
* Обновления переводов.
* Ревизия кода.
* Ревизия имен файлов условных обозначений.
* Вернул локальную палитру чтобы избежать потери усл обощначений при открытии на другом телефоне.

4.1.4p - Beta 2019-09-20
* Настройки экспорта в VisualTopo.
* Ревизия кода.
* Обновления руководства и переводов.

4.1.4n -Beta 2019-09-15
* Пробное исправление: инкремент номеров пикетов.

4.1.4g-k - Beta 2019-09-09
* Исправлен импорт файлов VisualTopo.
* Выделение текущего пикета зеленым цветом на экране абрисов.
* Исправления: прилипание границ области к линии; экспрот в shapefile.
* Обновления руководства и переводов.

4.1.4f - 2019-08-21
* Ревизия системы отображения сплеев пунктиром.
* Калибровка: расчет оригинальной "дельты" для групп замеров.
* Экспорт текущих настроек в файл
* Исправления ошибок.
* Обновления руководства и переводов.
* Отключен перевод на украинский язык.

4.1.4d Beta 2019-08-19
* Ревизия кода отвечающего за отображение сплеев пунктиром.
* Обновления руководства и переводов.

4.1.4c- 2019-08-01
* Калибровка: расчет оригинальной "дельты" для групп замеров.
* Экспорт текущих настроек в файл
* Отключен перевод на украинский язык.
* Обновления руководства и переводов.
* Исправления ошибок.

4.1.3y Beta 2019-07-05
* Небольшие исправления.
* Обновления переводов.

4.1.3x Beta 2019-06-26
* Ревизия протокола комуникации BLE.
* Оповещения о событиях: три одинаковых замера, запрос на соединение. Оповещения звуком или вибрацией.
* Рефакторинг кода авоматического именования пикетов.
* Исправления: экспорт в DAT (номера пикетов для сплеев), экспорт в XVI (сетка всегда включена).
* Обновления руководства и переводов.

4.1.3w Beta 2019-06-06
* Извлечен код для вычисления покрытия калиброванных данных.
* Добавлено предупреждение перед загрузкой калибровки в DistoX если ошибка превышает 0.5.
* Обновления руководства и переводов.
* Связь с устройством, ревизия кода протокола.
* Возможность установить опорный азимут для развертки на плане в графическом режиме.
* Включенные версии прошивки 2.4c, 2.5c (PMLS), и 2.51 (двойной бип каждые четыре калибровочных замера).

4.1.3u 2019-05-24
* Переписан функционал поиска: 
* Добавлена возможность поиска замеров с НЕзаданым направлением развертки.
* Подсветка результатов поиска желтым цветом.
* Обновления руководства.

4.1.3t 2019-05-19
* Исправления: 3d DXF export and other minor problems.
* Исправления портретная ориентация окна настроек.
* Слои абриса.

4.1.3p/q Beta 2019-05-16
* Исправления: проверка разрешений, просмотр фото.
* Обновления руководства и переводов.

4.1.3n/o Beta 2019-05-13
* Слои для абрисов
* Цветовой фон сообщений: голубой=информация, желтый=уведомление, оранжевый=предупреждение
* Исправления мелких ошибок и обновления руководства и переводов.

4.1.3j/l 2019-04-30
* Сообщения об ошибках на фиолетовом фоне.
* Исправления мелких ошибок и обновления руководства и переводов.

4.1.3e/f/h  Beta 2019-04-09
* Диалог поиска: поиск поверхностных и не присоединенных замеров.
* Исправления в статистике абриса - список неприсоединенных к нитке замеров
* Исправлена настройка класса текста
* Диалог изменения свойсв пикета в абриса с полем для ввода примечания и кнопкой диалога сохраненных пикетов.
* Перевод на китайский, спасибо H.J. Luo
* Обновления руководства и переводов.

4.1.3b/c 2019-04-01/02
* Возможность распределения элементов абриса по слоям.
* Исправления экспорта в форматы SVG и Therion.
* Исправления мелких ошибок.
* Обновления руководства и переводов.

4.1.3 2019-03-26
* Предварительный релиз

4.1.2s-w beta 2019-03-24
* Журнал пакетов комуникации с DistoX.
* Исправлена проблема с вылетом программы при отображении статистики съёмки.

4.1.2r Beta 2019-03-11
* Экспорт сырых данных измерений в CSV 
* Обновления руководства и переводов.

4.1.2q 2019-03-05
* Данные калибровки не попадающие в группы подсвечены зеленым. 
* Обновления руководства и переводов.

4.1.2p Beta 2019-03-02
* Исправлена ошибка при экспорте "спец" точек в svg/dxf/xvi.
* Исправлена проблема с буквенной нумерацией сплеев при экспорте.
* Новая настройка: единицы линий, цвета для сохраненных пикетов.
* Ориентировка точки может быть задана в момент ее создания.
* Обновления переводов.

4.1.2n/o Beta 2019-02-22/26
* Упрощение интерфейса программы.
* Новый стиль рисованя линий "упрощенный".

4.1.2m 2019-02-15
* Полностью удален код для внутренней работы с абрисами в формате therion.
* Исправления ошибок и обновления руководства и переводов.

4.1.2k Beta 2019-02-11
* Новая настройка: xvi_image в th2.
* Экспорт xvi (и th2) из окна бозора.
* Обновления руководства и переводов.

4.1.2h Beta 2019-02-07
* Переработка интерфейса.
* Инструменты рисования: особые настройки для точки "сечение"
* Исправления ошибок: импорт данных и абрисов PocketTopo

4.1.2f/g 2019-02-05
* Обновление мировой магнитной модели WMM
* Удален перевод на Китайский
* Обновления руководства и переводов.

4.1.2e 2019-02-04
* База данных: запись mac адреса distox для каждого замера.
* Экспорт данных в ESRI shape в единый zip архив (shz).
* Исправления zip включает xvi и shz
* Исправления ошибок.
* Удален функционал по 3D моделировнию (был давно уже выключен): что уменьшило размер apk на 1MB

4.1.2c Beta 2019-01-28
* Удален перевод на Китайский
* Экспорт нескольких абрисов из окна обзора: th2, svg, dxf, shp
* Связывающий сегмент между точкой сечения и линией сечения или пикетом с поперечным сечением.
* Обновления руководства и переводов.

4.1.2 Релиз 2019-01-23
* Возможность соединять линии одного типа.
* Магнитное склонение может иметь значение "не задано".
* Экспорт данных и абрисов в ESRI shape и xtherion xvi.
* Импорт данных в формате Survex.
* Одновременный выбор нескольких линий (действия: удалить, проредить, соединить)
* Калибровочные замеры с ошибкой больше 1 градуса выделены красным.
* Звуковой сигнал при полученни 3х одинаковых измерений между пикетами.
* Исправления ошибок.
* Обновления руководства и переводов.

4.1.1D Beta 2019-01-22
* Экспорт абрисов в формат xtherion xvi 
* Звуковой сигнал при полученни 3х одинаковых измерений между пикетами.
* Новые условные обозначения для рисрвания
* Обновления руководства и переводов.

4.1.1A-B Бета 2019-01-15
* Исправления ошибок: экспорт в Dxf v-12.
* Иморт формата Survex [1й тест]
* Обновления руководства и переводов.

4.1.1z Бета 2019-01-06
* Исправления: Использование "calibrate" при импорте формата Therion

4.1.1y Бета 2018-12-21
* Больше настроек перенесено в раздел "спец настройки".
* Добавлена подпись прошивки 2.4c для её идентификации.
* Проверка контрольной суммы прошивки DistoX.

4.1.1x Бета 2018-12-20
* Новые настройки: привязать линию/область, сгладить/спрямить сегмент, выбор нескольких линий.
* Переработвно меню настроек: некоторые продвинутые опции перемещены в секцию "спец настройки".
* Обновления руководства и переводов.

4.1.1w Бета 2018-12-14
* Экспорт абрисов в ESRI shape
* Новая настройка: фиксированная точка отсчета для всех абрисов

4.1.1v Бета 2018-12-11
* Выбор нескольких линий с опциями: удалить, проредить, соединить.
* Ревизия кода.
* Двух уровневое прореживание точек линии/области.
* Калибровочные замеры с ошибкой больше 1 градуса выделены красным.
* Исправления: меню данных калибровки, экспорт проекции на азимут в svg/dxf.
* Обновления руководства и переводов.

4.1.1u Бета 2018-11-28
* Экспорт данных съёмки в ESRI shape.
* Исправления: Настройки цветов при импорте PocketTopo
* Обновления руководства и переводов.

4.1.1s Бета 2018-11-21 
* Возможность ввода координат привязки пикета из буфера обмена (например GPS-Impetus)
* Новая кнопка "обновить" (окно списка пикетов).
* Обновления руководства и переводов.
* Новый перевод: Польский (Krzysztof Borgiel). 
* Исправления: подсветка недавних измерений.
* Исправления: частичная развертка. Новые настройки для частичной развертки нитки хода.

4.1.1p Бета 2018-11-14
* Исправления: экспорт магнитного склонения (спасибо ojwb) [therion, visualtopo, survex].
* Магнитного склонения может быть "не задано".
* Возможность сшивать линии одинакового типа.

4.1.1i - 2018-11-06
* Убран функционал для совместной съёмки на нескольуо приборов.

4.1.1h -2018-10-30
* Одновременная перенумерация нескольких боковых замеров.
* Исправления: экспорт в dxf (только для в v.6)

4.1.1a - 2018-10-10
* Обновление интерфейса настроек.
* Ревизия кода.
* Обновления руководства и переводов.
* Режим ввода данных подводной съёмки. (эксперементальный)
* Переписан класс database helper.
* Скрытие боковых замеров не попадающих на плоскость поперечного сечения.
* Исправления: ошибки закрытия колец, переименования пикетов, сторонней клавиатуры и переименования съёмки.

4.1.0C - Beta 2018-10-04
* Сплеи разбиты на категории: Гор./Верт. для более коректного отображения на плане и разрезе.
* Можно менять категории сплеев выбирая несколько строк в таблице пикетов.
* Исправления ошибок в меню настроек.

4.1.0q/u - Beta 2018-09-05
* Обновление окна настроек
* Ревизия кода
* Журнал: опция для дописывания в существующий файл журнала
* Обновления руководства и переводов.
* Режим ввода данных подводной съёмки.
* Переписан класс database helper.
* Исправления: ошибки закрытия колец, переименования пикетов.
* Обновления руководства и переводов.

4.1.0n - Beta 2018-08-21
* Скрытие боковых замеров не попадающих на плоскость поперечного сечения.
* Исправления: ошибки закрытия колец, переименования пикетов.
* Обновления руководства.

4.1.0k - Beta 2018-08-11
* Минимальный API-26
* Исправления: значение развертку замера при импорте/экспорте в zip

4.1.0e/h - Beta 2018-08-03
* Асинхронный доступ к данным и экспорт абрисов.
* Ревизия кода
* Исправления: экспорт в csurvey .
* Обновления руководства и переводов.

ВАЖНОЕ ОБЪЯВЛЕНИЕ (25 Июля 2018)
В версии 4.1 исправлена ощибка асинхронного ввода-вывода абрисов.
Эта ошибка влияет на съемки с большим количеством абрисов и проявляется в сохранении открытого абриса  вместо его закрытья.
Приложение собранное под Android-2.2 и выше доступно в [разделе версии 4.1](https://sites.google.com/site/speleoapps/home/topodroid/topodroid-old-download/topodroid-4-1).

4.1.0/a - 2018-07-24
* Исправления:  ошибка в чтении большого кол-ва абрисов.
* Исправления: настройка размера текста (максимальное значение)
* Просмотр фото без использования внещних приложений (to avoid compat-support due to Android N)
* Экспорт данных в формат GeoJSON. (экспериментальная функция)
* Частичная развертка.

4.0.1r - Beta 2018-07-19
* Экспорт данных в формат GeoJSON. (экспериментальная функция)
* Extend stretch.
* Исправления: phantom area points.
* Обновления руководства.

4.0.1q - 2018-07-11
* Минимальный API 16 (Android 4.1) собрано с android-26 (built 27).
* Диалог базовой настройки при "чистой" установке.
* Изменения в экспорте данных съёмки в Therion: (# extend auto).
* Изменения в экспорте DXF (спасибо vremebg).
* Изменения в экспорте: увеличено максимальное разрешение PNG до 100.
* Обратные замеры: в случае использования прямых и обратных замеров, обратные помечаются как "дубликат"
* Абрисы: выбраный способ продолжения линии не сбрасывается при рисованни следующего объекта, изменения в показе/скрытии сплеев.
* Изменена карта распределения данных калибровки.
* DistoX удаленное управление.
* Съемка с компенсацией магнитной аномалии теперь присутсвует в меню политик автонумерации пикетов.
* Перевод на Словенский отключен. Добавлен Румынский. Обновления руководства и переводов на другие языки.

4.0.1m/p - Beta 2018-07-05
* Обратные замеры выделены цветом.
* Исправления: рахзмеры значков в основной палитке, кол-во знаков после запятой для координат.
* placeholder buttons.
* Обновления переводов. 


4.0.1i/k - Beta 2018-06-28
* Опция отцентровать абрис на пикете.
* Съемка с компенсацией магнитной аномалии теперь присутсвует в меню политик автонумерации пикетов.
* Новые диаграмы распределения калибровочных данных G/M.
* Перевод на Румынский (by A. Pologea)
* Исправления: автонумерация пикетов

4.0.1h - Beta 2018-06-20
* Рефакторинг кода.
* Абрис разрез-развертка: обновлен способ "развертки" нитки хода.
* Абрис: добавлены кнопки скачать/bluetooth в окно поперечного сеченеия.
* Абрис: более заметный штрих указывающий направление 
* Bluetooth удаленное упрвление Дисто: данные скачиывются в соответствии с настройками подключения.
* Абрис: увеличено максимальное разрешение PNG до 100.
* Обратные замеры: в случае использования прямых и обратных замеров, обратные помечаются как "дубликат"
* Абрис разрез-развертка: исправлена ошибка в меню областей.
* Новые настройки: способ продолжения рисования линий.
* Режим отображения данных: новая опция: последние сплеи.
* Обновления переводов.

4.0.1g - Beta 2018-06-12
* Выбраный способ продолжения линии не сбрасывается при рисованни следующего объекта.
* Изменения в экспокте данных съёмки в Therion: "extend auto" используется по умолчанию для боковых замеров.
* TopoDroid новый диалог начальной базовой настройки. Нужно сделать "clear app data" чтобы снова инициировать этот диалог.
* Обновления переводов.
* Therion "export auto" в процессе обсуждения.
* Мелкие улучшения в коде.

4.0.1d/e - Beta 2018-06-01
* Минимальный API 16 (Android 4.1) собрано с android-26
* Изменена карта распределения данных калибровки.
* Перевод на Словенский будет отключен.
* Обновления руководства и переводов.
* Улучшение синтаксиса кода.

4.0.1c - Бета  2018.05.26
* Обновления руководства и переводов.
* Новая функция показа/скрытия боковых замеров на абрисе.

4.0.1a - 2018-05-17
* Исправления: экспорт сплеев в KML, компенсация магнитной аномалии.

4.0.0q/r - 2018-05-14
* Закончен перевод на Словацкий (M. Jurecka).
* Обновления руководства и переводов.
* Исправления: нумерация пикетов при съёмке обратным ходом.

4.0.0l-n - Beta 2018-05-03-08
* Ошибка (точность) определения GPS координат (DOP)
* Проверка калибровки по трем пикетам (замерам между тремя точками)
* Перевод на Словацкий (M. Jurecka)
* Обновления руководства и переводов.
* Исправления: диалог оглавления руководства, диалог привязки точки к координатам.

4.0.0i - Beta 2018-04-24
* Руководства на других языках устанавливаются автоматически через TopoDroid
* Возможность задавать пользовательские цвета сплеев
* Исправления мелких ошибок
* Обновления руководства и переводов

4.0.0f-h 2018-04-17
* Вернули старые иконки кнопок.

4.0.0c 2018-04-14
* Словенский перевод убран из-за неполноты перевода
* Исправления: точка поперечного сечения на замере (между пикетами), прокручиваемая панель кнопок, инкримент автонумерации пикетов
* Обновления руководства и переводов


4.0.0 - Beta 2018-03-29
* Перевод интерфейса в material design.
* Диалоги линий и обласией: новая кнопка «прореживание точек» в линии.
* Диалог линии: новые кнопки спрямление, прореживание точек и заострение углов, взаимно исключающие опции.
* Окно обзора: новая кнопка отмены при измерениях полилинией.
* Статистика съемки: добавлена Длина в горизонтальной плоскости.
* Выбор нескольких замеров: выделение и кнопки простирание/падение.
* Всплывающие сообщения в нижней части экрана (нажмите, чтобы немедленно закрыть).
* Улучшения экспорта CSurvey.
* Исправлена проблема с поворотной кнопкой "Азимут".
* Пуководство на Французском ( Д. Рос).
* Переводы и обновления руководства пользователя.
