Функция ReplaceInColumn
Описание

Выполняет замену значений в указанном столбце таблицы на основе таблицы соответствий.
Синтаксис

ReplaceInColumn(inputTable as table, columnName as text, replacementTable as table) as table

Параметры
    inputTable: Исходная таблица, в которой требуется произвести замену значений
    columnName: Имя столбца, в котором будет производиться замена
    replacementTable: Таблица соответствий с двумя столбцами:
        Первый столбец: искомые значения
        Второй столбец: значения для замены

Примечания
    Функция сохраняет исходную структуру таблицы
    Если значение не найдено в таблице замен, оно остается без изменений
    Тип данных результирующего столбца: text

Полезно для:
    Стандартизации данных
    Замены кодов на описания
    Исправления ошибок в данных
    Перевода значений

