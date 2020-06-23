# **Описание интерфейса IBranchOffice**
***
Интерфейс предназначен для работы с методами класса [BranchOffice](https://github.com/prmxt/Insurance-company/blob/master/docs/BranchOffice.md).
## Реализация интерфейса
***
+ **Add(BO : [BO](https://github.com/prmxt/Insurance-company/blob/master/docs/BranchOffice.md)) : ID_BO:int** - функция, добавляющая филиал в базу данных. Параметр «BO» — филиал, который необходимо добавить в БД, возвращает номер добавляемого филиала;
+ **Del(ID_BO : int) : bool** - функция, удаляющая филиал. Параметр «ID_BO» - идентификатор филиал, возвращает результат выполнения да или нет;
+ **FindBy(ID_BO : int) : [BO](https://github.com/prmxt/Insurance-company/blob/master/docs/BranchOffice.md)** - функция, которая ищет филиал. Параметр «ID_BO» - показывает идентификатор филиала, возвращает сам объект договор;
+ **GetAllBO(sorting : string, filtering : string, sortingA : string, count : int, page : int) : List <[BO]()>** - функция, позволяющая получить список всех филиалов, возвращает список всех филиалов;
+ **GetAllContractBO(ID_BO : int) : List<[BO](https://github.com/prmxt/Insurance-company/blob/master/docs/BranchOffice.md)>** - функция, позволяющая получить список всех договор конкретного филиала. Параметр "ID_BO" - идентификатор филиала, возвращает список всех договоров конкретного филиала;
+ **GetAllWorkerBO(ID_BO : int) : List <[Worker](https://github.com/prmxt/Insurance-company/blob/master/docs/Worker.md)>** - функция, позволяющая получить список всех работников конкретного филиала. Параметр "ID_BO" - идентификатор филиала, возвращает список всех работников конкретного филиала;
+ **Save(BO : [BO](https://github.com/prmxt/Insurance-company/blob/master/docs/BranchOffice.md)) : bool** - функция, сохраняет филиал в базу данных. Параметр «Contract» - филиал, который мы сохраняем, возвращает результат выполнения да или нет.
