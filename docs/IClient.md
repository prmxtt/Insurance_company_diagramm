# **Описание интерфейса IClient**
***
Интерфейс предназначен для работы с методами класса [Client](https://github.com/prmxt/Insurance-company/blob/master/docs/Client.md).
## Реализация интерфейса
***
+ **Add(Client :  [Client](https://github.com/prmxt/Insurance-company/blob/master/docs/Client.md)) : ID_Client : int** - функция, добавляющая клиента в базу данных. Параметр «Client» — клиент, который необходимо добавить в БД, возвращает номер добавляемого клиента;
+ **AddPayment(ID_Client : int, ID_Payment : int) : ID_Payment** - функция, добавляющая оплату в базу данных. Параметры «ID_Client, ID_Payment» — идентификаторы клиента и оплаты, который необходимо добавить в БД, возвращает номер добавляемой оплаты;
+ **Del(ID_Client) : bool** - функция, удаляющая клиента. Параметр «ID_Client» - идентификатор колиента, возвращает результат выполнения да или нет;
+ **DelPayment(ID_Client : int, ID_Payment : int) : bool** - функция, удаляющая оплату у клиента. Параметр «ID_Client, ID_Payment» - идентификаторы клиента и оплаты, возвращает результат выполнения да или нет;
+ **FindByID(ID_Client : int) :  [Client](https://github.com/prmxt/Insurance-company/blob/master/docs/Client.md)** - функция, которая ищет клиента. Параметр «ID_Client» - показывает идентификатор клиента, возвращает сам объект клиент;
+ **GetAllClient(sorting : string, filtering : string, sortingA : string, count : int, page : int) : List <[Client]()>** - функция, позволяющая получить список всех клиентов, возвращает список всех клиентов;
+ **GetAllContractClient(ID_Client) : List <[Contract](https://github.com/prmxt/Insurance-company/blob/master/docs/Contract.md)>** - функция, позволяющая получить список всех договоров клиента, возвращает список договоров клиента;
+ **GetAllIE(ID_Client : int) : List<[IE](https://github.com/prmxt/Insurance-company/blob/master/docs/InsuranceEvent.md)>** - функция, позволющая получить список страховых случаев клиента, возвращает список страховых случаев клиента;
+ **GetAllPaymentClient(ID_Client) : List<[Payment](https://github.com/prmxt/Insurance-company/blob/master/docs/IPayment.md)>** - функция, позволющая получить список оплат клиента, возвращает список соплат клиента;
+ **Save(Client : [Client](https://github.com/prmxt/Insurance-company/blob/master/docs/Client.md)) : bool** -функция, сохраняет клиентва в базу данных. Параметр «Client» - клиент, которого мы сохраняем, возвращает результат выполнения да или нет.
