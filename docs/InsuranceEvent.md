# **Описание класса InsuranceEvent**
***
Класс для работы со страховыми случаями.
# Атрибуты
***
- BeneficiaryAndPayment : Dictionary<Client,Float> - список бенефициаров и их выплат;
- Contract : Contract - договор;
- DecisionOnTheIE : Bool - решение по страховому случаю;
- Documentation : List<Document>Documents - список документов;
- EndDateOfTheIE : DateTime - дата окончания страхового случая;
- Event : String - событие;
- ID : Int - идентификатор страхового случая;
- StartDateOfTheIE : DateTime - дата начала действия страхового слуячая;
- StatusOfTheIE : String - статус страхового случая;
- SumOfPaymentForTheIE : Float - общая сумма выплаты по страховому случаю;
- Worker : Worker - работник.