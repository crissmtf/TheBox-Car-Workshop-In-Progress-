Aplicação OutSystems para gestão de oficinas — clientes, veículos, ordens de serviço, serviços, estados e fluxo completo desde a receção até à entrega.

*WHAT IS IT?*

  This is an OutSystems application designed to digitalize the operational workflow of an automotive workshop.
It includes customer management, vehicle registration, service orders, service execution, photos, status tracking, and dashboards to monitor all the tasks in progress.

This project was developed as part of my OutSystems training program (1100h – CESAE Digital), demonstrating practical skills in:

Data modeling
Full CRUD implementation
UI Patterns
Client and Server Actions
Integrations
Real-world business logic

< MAINFEATURES >
*Customers*
Create, edit, and view customers
Vehicle history per customer

*Vehicles*
Vehicle registration linked to customers
Technical data (license plate, brand, model, year, VIN)
Photos of the vehicle during reception

*Service Orders (SO)*
Create SO with customer + vehicle
Add services
Update SO status (Received → In Repair → Waiting for Parts → Completed → Delivered)


*Reception Dashboard*
List of open SOs
Status filters
Quick access to details

*Mechanic Dashboard*
Assigned SOs
Checklists
Progress tracking

-----------------___--------------------------

*Application Architecture*

-Entities-
Customer
Vehicle
ServiceOrder
ServiceOrderStatus
ServiceStatus
VehiclePhoto

-Main Screens-
Customer List / Detail / Edit

Vehicle List / Detail / Edit

Service Order List / Detail / Edit

Dashboard

Logic
Server Actions for CRUD

Client Actions for validations

Photo Plugin
