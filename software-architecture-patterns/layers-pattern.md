# Layers pattern

In this pattern the sistem is a stack of differend layers

Each layer encaspulates details

Dependenices can depens on a layers below it and cannot depend on layers above it

Usage directed from upper ot lower layer

COmmunication can be directe in both ways

## Example

ISO Open Systems Interconteccion  model

Multi-Layered/N-Layered Architecture

## Multi-tier/N-Tier Architecture

* Presetnation tier
* Application Tier
* Data Tier

## Closed/Struct layer architecture
CLosed/stricty layer architectuyer
* Advantes: modularity, simplifies debuggin and testing
* Disadvantages: potential performance overhead

## Open Layuer arhcitecture
Advantages Can bypoass layers
Disvantasd harder to understan/maintain
Risks of bugs

## Pros and cons of layuers pattern
PRO
* Layers are independent
    * Helpfull for development
    * Ind production
    * Implementation are interchagable
* Unidirectional dependencies

CONS
Layers are overhead when they only poass ionforamtion
Loose layering
* Allows for skinppuing layers
* But increases dependency

## Summary
* Layers pattern for software architecture
    * Componetns are orgnaized as stacked layers of sevices

