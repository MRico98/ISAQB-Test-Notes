# Cross-Cutting Concerns and Concenpts

## What are cross cutting concerns
* Aspects of the architecture that affect multiple componentes of the system
* Are often a result of fulfilling quality requiriments
    CAnnot be easily separed into idnependt compents and may violate DRY/SOC

## Concerns

### persitance
* Persit data from volatile memory to permamtn storage

Eazch compnent need to retrieve data

One solution are the ORM that abstract the database interaction into highlevel operations

### Error Handling
Predictable and adequated responses depending on category adn severity, differentiate between logical and techincal errors
Minimize effects of erros

Create custom exceptions and attach it to the http verbs

### Security
* Authentication - sender itendidty
* Authorization - GRands based on identity
* Integrity
* COnfidientality
* Non repudaiton
* Availability

Security frameworks
    Spring security, django

Algorithm/libraries

### Internationalization
* Formatting
* Labels
* Timezones

### Communication and Messaging
* Communication
    * Synchronous
    * Asynchronous

Message queues and message brokers
Remote prodecute call standars
Api styles

### User interfaces and ergonomics
* User interface
    * Graphical
    * Can be adatpvide 
* Ergonomics
UI and Ergonoics
* Responsive
* Adapttive design
    * Different version/layour for every platform

## Busingess Rules and Process
* Domain specific: business rules and conditions
* Business rules and processes are often implemented directly fin code

Better: centralized

* business rules maangement systems
* Workflow engines

## Sumary
* Cross-cutting conerns
    * Aspects of the architecture that affect multiple componetns
