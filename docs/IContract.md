# **Описание интерфейса IContract**
***
Интерфейс предназначен для работы с методами класса [Contract](https://github.com/prmxt/Insurance-company/blob/master/docs/Contract.md).
## Реализация интерфейса
***
+ **Add(Contract :  [Contract](https://github.com/prmxt/Insurance-company/blob/master/docs/Contract.md)) : ID_Cotract : int** - функция, добавляющая контракт в базу данных. Параметр «Contract» — контракт, который необходимо добавить в БД, возвращает номер добавляемого договора;
+ **AddBnf(ID_Contract, ID_Client) : List<[Client](https://github.com/prmxt/Insurance-company/blob/master/docs/Client.md)>** - функция, добавляющая бенефициара в таблицу бенефициаров. Параметр «Client» - клиент, который будет бенефициаром, возвращает список бенефициаров;
+ **AddDoc(ID_Contract, ID_Doc) : [Doc](https://github.com/prmxt/Insurance-company/blob/master/docs/Documentation.md)** – функция, добавляющая документ в таблицу документов. Параметры  «ID_Contract», «ID_Doc» - показывают идентификатор договора и идентификатор документа соответсвенно, возвращает сам объект документ;
+ **AddIE(ID_Contract, ID_IE) : [IE](https://github.com/prmxt/Insurance-company/blob/master/docs/InsuranceEvent.md)** – функция, добавляющая страховой случай в базу данных. Параметры «ID_Contract», «ID_IE» - показывают идентификатор договора и идентификатор страхового случая, возвращает сам объект страхового случая;
+ **AddPayment(ID_Client, ID_Payment) : bool** – функция, добавляющая оплату в договор. Параметры «ID_Client», «ID_Payment» - показывают идентификатор клиента и идентификатор оплаты соответсвенно, возвращает результат выполнения да или нет;
+ **Del(ID_Contract : int) : bool** – функция, удаляющая договор. Параметр «ID_Contract» - идентификатор договора, возвращает результат выполнения да или нет;
+ **DelBnf(ID_Contract, ID_Client) : bool** – функция, удаляет бенефициара из базы данных. Параметры «ID_Contract», «ID_Client» - показывает идентификатор договора и иденификатор клиента, возвращает результат выполнения да или нет;
+ **DelDoc(ID_Contract, ID_Doc) : bool** - функция, удаляет документ из базы данных. Параметры «ID_Contract», «ID_Doc» - показывает идентификатор договора и идентификатор документа, возвращает результат выполнения да или нет;
+ **DelIE(ID_Contract, ID_IE) : bool** - функция, удаляет страховой случай из базы данных. Параметры «ID_Contract», «ID_IE» - показывает идентификатор договора и идентификатор страхового случая, возвращает результат выполнения да или нет;
+ **DelPayment(ID_Client) : bool** -  функция, удаляет оплату из базы данных. Параметр «ID_Client»- показывает идентификатор договора, возвращает результат выполнения да или нет;
+ **FindByID(ID_Contract : int) :  [Contract](https://github.com/prmxt/Insurance-company/blob/master/docs/Contract.md)** – функция, которая ищет договор. Параметр «ID_Contract» - показывает идентификатор договора, возвращает сам объект договор;
+ **GetAllContract(sorting : string, filtering : string, sortingA : string, count : int, page : int) : List < [Contract]()>** - функция, позволяющая получить список всех договоров, возвращает список всех договоров;
+ **GetAllIE(ID_Contract) : List <[IE](https://github.com/prmxt/Insurance-company/blob/master/docs/InsuranceEvent.md)>** - функция, позволяющая получить список всех страховых случаев, возвращает список всех страховых случаев;
+ **GetAllPayment(ID_Contract) : List<[Payment](https://github.com/prmxt/Insurance-company/blob/master/docs/Payment.md)>** - функция, позволяющая получить список всех оплат, возвращает список всех оплат;
+ **Save(Contract :  [Contract](https://github.com/prmxt/Insurance-company/blob/master/docs/Contract.md)) : bool** – функция, сохраняет договор в базу данных. Параметр «Contract» - договор, который мы сохраняем, возвращает результат выполнения да или нет.
