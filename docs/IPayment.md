# **Описание интерфейса IPayment**
***
Интерфейс предназначен для работы с методами класса [Payment](https://github.com/prmxt/Insurance-company/blob/master/docs/Payment.md).
## Реализация интерфейса
***
+ **Add(Payment : [Payment](https://github.com/prmxt/Insurance-company/blob/master/docs/Payment.md)) : ID_Payment : int** - функция, добавляющая оплату в базу данных. Параметр «Payment» — оплата, который необходимо добавить в БД, возвращает номер добавляемого оплаты;
+ **Del(ID_Payment : int) : bool** - функция, удаляющая оплату. Параметр «ID_Contract» - идентификатор оплаты, возвращает результат выполнения да или нет;
+ **FindByID(ID_Payment : int) : [Payment](https://github.com/prmxt/Insurance-company/blob/master/docs/Payment.md)** – функция, которая ищет оплату. Параметр «ID_Payment» - показывает идентификатор оплаты, возвращает сам объект оплату;
+ **GetAllPayment(sorting : string, filtering : string, sortingA : string, count : int, page : int) : List <[Payment](https://github.com/prmxt/Insurance-company/blob/master/docs/Payment.md)>** - функция, позволяющая получить список всех оплат, возвращает список всех оплат;
+ **Save(Payment : [Payment](https://github.com/prmxt/Insurance-company/blob/master/docs/Payment.md)) : bool** - оплата, который мы сохраняем, возвращает результат выполнения да или нет.
