# **Описание интерфейса IDocumentation**
***
Интерфейс предназначен для работы с методами класса [Documentation](https://github.com/prmxt/Insurance-company/blob/master/docs/Documentation.md).
## Реализация интерфейса
***
+ **Add(Doc : [Doc](https://github.com/prmxt/Insurance-company/blob/master/docs/Documentation.md)) : ID_Doc : int** - функция, добавляющая документ в базу данных. Параметр «Doc» — документ, который необходимо добавить в БД, возвращает номер добавляемого документ;
+ **Del(ID_Doc : int) : bool** - функция, удаляющая документ. Параметр «ID_Doc» - идентификатор документа, возвращает результат выполнения да или нет;
+ **FindByID(ID_Doc : int) : [Doc](https://github.com/prmxt/Insurance-company/blob/master/docs/Documentation.md)** - функция, которая ищет документ. Параметр «ID_Doc» - показывает идентификатор документа, возвращает сам объект документ;
+ **Save(Doc : [Doc](https://github.com/prmxt/Insurance-company/blob/master/docs/Documentation.md)) : bool** - функция, сохраняет документ в базу данных. Параметр «Contract» - документ, который мы сохраняем, возвращает результат выполнения да или нет.
