# **Описание интерфейса IWorker**
***
Интерфейс предназначен для работы с методами класса [Worker](https://github.com/prmxt/Insurance-company/blob/master/docs/Worker.md
).
## Реализация интерфейса
***
+ **Add(Worker : [Worker](https://github.com/prmxt/Insurance-company/blob/master/docs/Worker.md
)): ID_Worker** - функция, добавляющая работника в базу данных. Параметр «Worker» — работник, которого необходимо добавить в БД, возвращает номер добавляемого работника;
+ **Del(ID_Worker: int) : bool** - функция, удаляющая работника. Параметр «ID_Worker» - идентификатор работника, возвращает результат выполнения да или нет;
+ **FindByID(ID_Worker : int) : [Worker](https://github.com/prmxt/Insurance-company/blob/master/docs/Worker.md
)** - функция, которая ищет работника. Параметр «ID_Worker» - показывает идентификатор работника, возвращает сам объект работник;
+ **GetAllContractWorker(ID_Worker : int) : List<[Contract](https://github.com/prmxt/Insurance-company/blob/master/docs/Contract.md)>** - функция, позволяющая получить список всех договоров работника, возвращает список договоров работника;
+ **GetAllIEWorker(ID_Worker : int) : List<[IE](https://github.com/prmxt/Insurance-company/blob/master/docs/InsuranceEvent.md)>** - функция, позволющая получить список страховых случаев работника, возвращает список страховых случаев работника;
+ **GetAllWorker(sorting : string, filtering : string, sortingA : string, count : int, page : int) : List <[Worker]()>** - функция, позволяющая получить список всех работников, возвращает список всех работников;
+ **Save(Worker : [Worker](https://github.com/prmxt/Insurance-company/blob/master/docs/Worker.md
)) : bool** - работника, которого мы сохраняем, возвращает результат выполнения да или нет.
