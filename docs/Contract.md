# **Описание класса Contract**
***
Класс для работы с договорами страховой компании.
# Атрибуты
***
+ AmountOfInsurancePremium : Float - сумма страховой выплаты;
+ Beneficiary : List<[Client](https://github.com/prmxt/Insurance-company/blob/master/docs/Client.md)> - список бенефициаров;
+ BranchOffice : BranchOffice - филиал;
+ ClientBuyer : [Client](https://github.com/prmxt/Insurance-company/blob/master/docs/Client.md) - клиент покупатель;
+ ContractNumber : String - уникальный номер договора;
+ DateOfContract : DateTime - дата заключения договора;
+ Documentation : List<[Doc](https://github.com/prmxt/Insurance-company/blob/master/docs/Documentation.md)> - список прилагаемых документов;
+ EndContractDate : DateTime - дата окончания действия договора;
+ EndPrice : Float - конечная стоимость;
+ ID : Int - идентификатор договора;
+ Rate : [Rate](https://github.com/prmxt/Insurance-company/blob/master/docs/Rate.md) - тариф;
+ Worker : [Worker](https://github.com/prmxt/Insurance-company/blob/master/docs/Worker.md) - работник.
