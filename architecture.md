# Joy's cyber design architecture
![Computer communications in a cyber](model.png)

## Browsing session controller
This is a standalone frontend system written in java that will post customers browsing session start and stop to the database backend.
The customer session manager will also have an option for calling for help from the administrator.
### Features
1. controling a browsing session(unlocking start/end browsing session,view time spent,view amount billed)
2. Seek assistance from the administrator
3. Make payment
 

## cashier 
This is a frontend system written in java that will get list of customers and their charges to the database backend.
### Features
1. login/logout and change password
2. Billing manager(view list of customers,calculate charges,collect money)


## Administrator 
This is a frontend system written in java that will list computers in use,add/update the computers,add/edit and disable users of the system to the database backend.
The administrator will also have an option for View/acknowledge requests for help from customers
### Features
1. login/logout and change password
2. Computer management(Add/update the computers)
3. User management(Add/edit and disable users of the system)
4. Help desk (View/acknowledge requests for help from customers
)


## Management
This is a frontend system runned in PHP webpage that will get number of customers,usage duration and daily cash collected in the cyber to the database backend.
The owner/manager will also have an option for assigning internet in the system.
### Features
1. login/logout and change password
2. view managerial reports(number of customers,customers usage duration and daily cash collected)
3. Assign internet


## Database 
This is a backend system written in MYSQL that will get all the tracked information of computers from the frontends.
The database will serve as the centre of information in the system.
### Features
1. Information storage centre
2. Central communication point





