![Диаграмма с Google Drive](https://drive.google.com/uc?id=1-9u8NoN4SCRjM_B_hURZ2EEkscluGkVr)
```plantuml
@startuml
!include https://raw.githubusercontent.com/vasilokb/plantUML/refs/heads/main/C4.puml


Person(front_office, "Фронт-офис", "Проверяет заявки, создаёт депозит")
Person(back_office_deposits, "Бэк-офис (депозиты)", "Обрабатывает заявки, рассчитывает ставки")
Person(back_office_credits, "Бэк-офис (кредиты)", "Анализирует кредитный риск")
Person(call_center, "Кол-центр банка", "Регистрирует обращения клиентов")

System(partner_call_center, "Внешняя система партнёрского кол-центра", "Регистрирует обращения") #lightgray
Boundary(system, "Банк Стандарт - Системы") {
System(abs, "АБС", "Автоматизированная банковская система, хранит данные и обрабатывает депозиты", "Delphi, Oracle") #lightblue
System(call_center_system, "Система кол-центра", "Регистрирует обращения и передаёт заявки", "React.js, Java Spring Boot, PostgreSQL") #lightgreen
System(sms_gateway, "СМС-шлюз", "Отправляет уведомления клиентам") #lightgray
System(internet_bank, "Интернет-банк", "Интегрирован с АБС, пока не используется для депозитов", "ASP.NET MVC, MS SQL") #green

}


Rel(call_center, call_center_system, "Регистрирует обращение")
Rel(partner_call_center, call_center_system, "Регистрирует обращение")
Rel(call_center_system, abs, "Передаёт заявку")
Rel(front_office, abs, "Проверяет заявку, создаёт депозит")
Rel(front_office, back_office_deposits, "Запрашивает ставку email/excel")
Rel(back_office_deposits, abs, "Обрабатывает заявку")
Rel(back_office_credits, abs, "Обрабатывает данные")
Rel(internet_bank, abs, "Интегрирован через БД")
Rel(abs, sms_gateway, "Отправляет СМС")
@enduml
```