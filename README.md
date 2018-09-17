# SpiridonovaKS.GitHub.IO
# Отчет а лабораторных работах
# студент группы ИДБ-15-14 Спиридонова К.С.
# Лабораторная 1
http://127.0.0.1:52344/idef0/index.html?id=3

* UML:
### @startuml
### skinparam class {
### BackgroundColor White
### ArrowColor Black
### BorderColor Black
### }
 ### class "Хозяйка" as H {
 ### Духовка
 ### Накормить гостей Эклеры (Необходимый набор продуктов, Приезд гостей)
###  }
###  hide circle
### @enduml

* UML PERSON:
### @startuml
### skinparam actor {
	### BackgroundColor White
	### ArrowColor Black
	### BorderColor Black
### }
### skinparam usecase {
	### BackgroundColor White
	### ArrowColor Black
	### BorderColor Black
### }
### left to right direction
### actor H0 as "Человек"
### actor D0 as "Бытовая техника"
### actor H as "Хозяйка"
### actor D as "Духовка"
### usecase E as "Эклеры"
### H -- (E)
### (E) -- D
### H0 <|-- H
### D --|> D0
### @enduml
