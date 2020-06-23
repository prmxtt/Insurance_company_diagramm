# **Описание интерфейса IRate**
***
Интерфейс предназначен для работы с методами класса [Rate](https://github.com/prmxt/Insurance-company/blob/master/docs/Rate.md).
## Реализация интерфейса
***
+ **Add(Rate : [Rate](https://github.com/prmxt/Insurance-company/blob/master/docs/Rate.md)) : ID_Rate: int** - функция, добавляющая тариф в базу данных. Параметр «Contract» — тариф, который необходимо добавить в БД, возвращает номер добавляемого тарифа;
+ **Del(ID_Rate : int) : bool*** – функция, удаляющая тариф. Параметр «ID_Contract» - идентификатор тариф, возвращает результат выполнения да или нет;
+ **FindByID(ID_Rate : int) : [Rate](https://github.com/prmxt/Insurance-company/blob/master/docs/Rate.md)** – функция, которая ищет тариф. Параметр «ID_Contract» - показывает идентификатор тарифа, возвращает сам объект тариф;
+ **GetAllContractRate(ID_Rate) : List <[Contract](https://github.com/prmxt/Insurance-company/blob/master/docs/Contract.md)>** - функция, которая получает список всех договоров по конкретному тарифу. Параметр "ID_Rate" - идентиификатор тарифа, возвращает список договоров по конкретному тарифу.
+ **GetAllPaymentRate(ID_Rate) : List<[Payment](https://github.com/prmxt/Insurance-company/blob/master/docs/Payment.md)>** - функция, которая получает список всех оплат по конкретному тарифу. Параметр "ID_Rate" - идентиификатор тарифа, возвращает список оплат по конкретному тарифу.
+ **GetAllRate(sorting : string, filtering : string, sortingA : string, count : int, page : int) : List <[Rate](https://github.com/prmxt/Insurance-company/blob/master/docs/Rate.md)>** - функция, позволяющая получить список всех тарифов, возвращает список всех тарифов;
+ **Save(Rate : [Rate](https://github.com/prmxt/Insurance-company/blob/master/docs/Rate.md)) : bool** - тариф, который мы сохраняем, возвращает результат выполнения да или нет.
