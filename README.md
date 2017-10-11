# DES modeling for the pyroprocessing system

## Discrete event simulation description

- In DES, each 'event' is a 'vertex.'
- There are state changes and/or parameters associated with a vertex.
- State changes are assigning values to a variable or solving an equation.
- Parameters are variables needed to make the state change.
- DES steps discretely in time through each vertex via an 'edge.'
- At each vertex, the equations are run and the state variables change.
- The edges are dynamic and provide logical relationships between events.
- DES should readily lend itself to the modeling of batch systems like pyroprocessing.
- Python is a natural fit for DES due to its modularity.
