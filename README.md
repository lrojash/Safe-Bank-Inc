# Safe-Bank-Inc
## Inspiration
As a former personal banker and teller I was alwasy curious of how the system we used worked and synchronized all the actions a customer would take. Althought it may be a trivial answer, I alwasy wanted to replicate the software and make modifications that either made the systme better or things that irritated me about the software that was being used. In this project I will first be creating a simple prototype, where the system behaves as bank system. Second phase will implement all the modifications that I would have made to their system if I were one of their software engineers and with the experience of knowing the bugs that their system had.  
***
# Description
The software is intended to simulate the environment that a typical bank employee uses throughout their workday.
***
# Technologies
![](images/pern.png)
***
## User Hierarchy
I wanted to show a reference as to how the emloyee heirarchy was during my time as an employee at the bank. It serves as a visual of all the employee roles and responsibilites and how they interact with each other. For example a teller would not be allowed to make a withdraw/deposit over a certain amount without review of a higher up, to ensure accuracry. Here I have chose an arbitrary amount.  
![](images/BMS.png)
***
# User Stories
In most settings an employee gets access to works system via ticket to their IT team. Here we are avoiding IT all together and having the Branch Manage(BM) or Teller Manager(TM) create the users for their employees, bankers and tellers respectively. 
1. Banker
* Create New Customer Accounts
* Override Teller Transactions under 100k
2. Teller
* Deposit/Withdraw/Transfer from customer accounts
* Allow transactions under 50k
* Balance their teller drawer
3. BM/TM
* Create Users
* TM override transactions under 150k
* BM override transactions of all amounts
# ERD
![](images/BMS-ERD.png)
