# DES modeling for the pyroprocessing system

## Overview

The current discrete event simulation (DES) model is developed for implementing strong safeguardability to a commercial-scale fuel fabrication facility. This README provides the precise guidance on how to run a 250-day operation one time or multiple times. In addition, several different sensitivity analyses can be performed by varying facility input parameters such as false alarm threshold, failure rate parameter, false alarm probability, heel amount, etc.

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

## Current status

The fuel fabrication process is modeled for two different designs. See the [fuel fabrication README](fuel-fabrication/README.md) for version updates. 

## Contributing

See the [CONTRIBUTING](CONTRIBUTING.md) file for more information. 

## Prerequisite

The current model only supports up to Python2.x. Spyder would be ideal to run the simulation and observe its process. It allows users to edit code and run files using IPython console.
