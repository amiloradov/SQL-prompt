# Оператор SQL DROP TABLE

Оператор DROP TABLE используется для удаления существующей таблицы в базе данных.

Оператор TRUNCATE TABLE используется для удаления данных внутри таблицы, но не самой таблицы.

## Синтаксис DROP TABLE

``` SQL
DROP TABLE table_name;
```

## Пример

Удалить существующую таблицу «Shippers»:
``` SQL
DROP TABLE Shippers;
```

> Будьте осторожны, прежде чем удалять таблицу. Удаление таблицы приведет к потере полной информации, хранящейся в таблице!

## SQL TRUNCATE TABLE

Оператор TRUNCATE TABLE используется для удаления данных внутри таблицы, но не самой таблицы.

## Синтаксис

``` SQL
TRUNCATE TABLE table_name;
```

---

[НАЗАД](/SQL_DATABASE/SQL_CREATE_TABLE.md)  | [ВПЕРЁД](/SQL_DATABASE/SQL_ALTER_TABLE.md)

