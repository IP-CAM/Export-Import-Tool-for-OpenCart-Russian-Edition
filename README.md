# Export/Import Tool for OpenCart (Russian Edition)

Инструмент импорта/экспорта позволяет пользователю с правами администратора выполнять массовый экспорт категорий, продукции, опций, атрибутов, фильтров и клиентов в файл электронной таблицы Excel.
Файл электронной таблицы можно редактировать в автономном режиме, а затем повторно импортировать в базу данных OpenCart.

Функции включают в себя:

- Импорт может быть инкрементным, то есть данные обновляются или добавляются на сервер OpenCart. 
- Или он может быть не инкрементным, что означает, что все старые данные сначала удаляются перед импортом.
- Экспорт может быть ограничен определенными диапазонами данных только для продуктов и категорий.
- Также поддерживаются несколько языков.

## Требования и ограничения

Требования к памяти могут быть довольно высокими.

* Не каждая общая учетная запись веб-хостинга поддерживает высокое использование памяти процессами.
* Поэтому, если Вы используете базовую учетную запись общего веб-хостинга, одновременно можно экспортировать или импортировать не более нескольких тысяч товаров.
* Используйте выделенную учетную запись веб-хостинга, если большее количество продуктов должны обрабатываться за один раз. Или экспортируйте и импортируйте несколько раз меньшими партиями.


## Установка

В панели администратора OpenCart выполните следующие действия:

1. Перейдите в `Расширения > Установщик расширений`.
2. Загрузите `export-import-tool-3x.ocmod.zip`.
3. Перейдите в `Расширения > Модификации`. Вы должны увидеть запись для этого Export/Import Tool.
4. Нажмите кнопку «Обновить» (вверху справа на странице).
5. Перейдите в `Система > Пользователи > Группа пользователей > Изменить администратора`.
6. Установите доступ и измените разрешения для `extension/export_import`.

Теперь Вы должны увидеть инструмент Export/Import в меню `Система > Инструменты> > Export/Import`.

### Дополнительная помощь и индивидуальные версии

Этот инструмент был успешно протестирован на стандартных версиях OpenCart 3.x.
Не используйте другие версии Opencart с этим модулем.

### Оригинальное расширение

Данное расширение основано на [Export/Import Tool](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=17). Официальный сайт автора [J.Neuhoff](https://www.mhccorp.com/)

## Лицензия
Авторские права на этот инструмент экспорта/импорта (c) 2020-2021 принадлежат ruOpenCart, и он предоставляется в соответствии с условиями [Стандартной общественной лицензии GNU версии 3](http://www.gnu.org/licenses/gpl.html).

## Поддержка
Получить поддержку можно на [форуме](https://forum.opencart.name/).