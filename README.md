The problem has been taken from AI A-Z Q-learning from **Super Data Science** by Hadelin De Ponteves and Kirill Eremenko.

The problem consists of a warehouse with 12 different locations. 
As the orders are placed by the customers online, an Autonomous Warehouse Robot
is moving around the warehouse to collect the products for future deliveries.
The 12 locations are all connected to a computer system, which is ranking in 
real time the priorities of product collection for these 12 locations.

Our Autonomous Warehouse Robot must move to the top priority location by the shortest
route depending on where it is.
This problem is solves in the 1st version of our code.

In the 2nd version we have implemented an option for our Autonomous Warehouse Robot to
go by some intermediary location before reaching its final top priority location.

We have used Q-Learning model in both the versions. (2nd version is an upgradation to 1st version)
