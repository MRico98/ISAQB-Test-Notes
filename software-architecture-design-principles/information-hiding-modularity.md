# information Hiding, SoC, and Modularity

## Information Hiding principle
* Encapsulating complecity in complments improves flexiblity, stability, testeability and understandiblity

Treat componets as black boex
* Hide internal details from clients
* No direct access to internal data and structures

Breaking encaptulation leads to unwanted dependencies

## SOC
Objective: manage different problems separtely

* Separate concerns
    * Domain, sub domanis, subtask
    * Persitence, logic, behavior, presentation

## Separations of Concerns - Other levels of abstractions
* Low level embedded systems
* Driverts in an Operating System
* Network in CLoud computing
* Container orchestration in Hybrid Cloud

## Modularity

SoC + Information Hidign -> Modularity
Modules
    * Encapsulate
    * Expose
    * Can be developed, maintaned and tested
Objectives
    * Ability to creare more complex modelues from smalles modules

## Summary
* information hidign principle
    * hides the internla details form clinetls
* Separation of concerns
    * Split complex syustems according to responsabilities
    * Reduce the complexity of each componetns
* Modularity = information hiding + SoC
    * We can build complex system from smaller modules


