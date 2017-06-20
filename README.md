# Ice Cream Store Simulation
It is the simulation of an ice cream store, and this simulation is done in [AnyLogic](https://www.anylogic.com/downloads/) simulation tool. There are two cases as indicated in
the system description below. Folder named as 'Ice Cream Store 2' represents the second case.

## System Description
In this store, there are two cashiers, and a
person who prepares ice cream. Second cashier will be working if the queue for the first cashier
has more than 4 customers. After customers make the payment, they enter another line to
get their ice cream. Then, if there is an empty table, customers choose to stay in the store to eat their ice
cream. If there aren’t any empty tables, then they just leave the store.

In the second version of the system, there is only one person who works in the store,
and this person is responsible for both getting the payments, and preparing the ice cream. After he/she
gets the payment from the customer, he/she starts preparing the ice cream order of that customer. If
there are any empty tables, then customer stays in the store to eat the ice cream. However, if
there aren’t any empty places in the store, then he/she leaves the store immediately.

For both cases, the system is analyzed by simulating the arrival and service of 200
customers, and the following values are used in both cases. Arrival time of each customer is
uniformly distributed between 1 to 5 minutes, and the time that it takes for making the payments to the cashier
is normally distributed with a mean of 2. Preparing each ice cream takes some time which
is uniformly distributed from 1 to 3 minutes. There are 5 tables and each one of them is for 1
person only. Each person who eats his/her ice cream in the store spends some time which is
uniformly distributed between 5 and 8 minutes to eat it.

For both systems, the average time spent in the desk queue, the average
time that people who eat their ice cream outside spend in the system, the average time that it
takes to prepare an ice cream, and the total number of people who eat their ice cream at the
store, and the average time that each person who eats his/her ice cream in the store spends in
the system are measured.

## How to use it?
* Clone the repo.
* Open the model with AnyLogic simulation tool.
* Customize it as you like and then run your simulation.
