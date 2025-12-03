# Loose Coupling

## Types of Coupling
Degree or measure of how closely two componets are connects
* Components do interact with each other

1. CAll
Method or application calling another entity

If bulding block a calls building block B then a is depends on B

2. MESSAGE
Sender send a meesage and receivver receive the message

3. CREATION
An object create another object through another class
The creator class depends on the other class that is creating becouse is a reference

4. DATA STRUCTURE
Classes shaing a data structure like a map or a list
Or the same computer sharing a file of memory

5. TIME
The successful execuition of a task by one component depends on the time of execution

* Sequencial dependency: one process mut be completed before another can start
* Scheduling dependency: tasks must be executed at specific times or interval
* Real time contraints: process mmust respond to events within stric time constraints

6. EXECUTION LOCATION
When componetns depends on the fisical enviroment

Coupling = Acoplamiento

7. INHERITENCE
When the child class extends to the parent class.
This is the strongest type of coupling that we can have


## Loose Coupling
* Aim for loose coupling
    * Keep the number of dependencies low
    * Keep dependencies simple

Goal: Few, well-defined, well-structures

* Loosly coupled components
    * Can interact, but need to know very little about each other.

* Degree of dependency for involver components is a low as possible


