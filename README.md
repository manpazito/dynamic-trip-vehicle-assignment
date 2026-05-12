# Dynamic Trip-Vehicle Assignment Reimplementation

An independent decomposition and reconstruction of the real-time high-capacity ride-sharing framework introduced by Javier Alonso-Mora et al. This project investigates scalable online ride-pooling through dynamic routing, trip-vehicle assignment, constrained optimization, and demand-aware fleet management.

The repository is intended as a research and educational effort to study, reproduce, and extend the algorithmic foundations behind large-scale shared mobility systems.

## Overview

Modern ride-sharing systems require fast and scalable assignment of:

* passenger trip requests,
* available vehicles,
* dynamically changing traffic and demand conditions.

This project rebuilds the core framework described in the original paper, focusing on:

* dynamic trip-vehicle assignment,
* multi-passenger ride pooling,
* online optimization,
* fleet rebalancing,
* scalable routing heuristics,
* operational tradeoff analysis.

The system incrementally assigns requests to vehicles using a greedy initialization followed by constrained optimization to improve assignment quality over time.

## Features

* Real-time trip-vehicle assignment
* High-capacity ride pooling
* Dynamic route generation
* Online demand handling
* Fleet rebalancing for idle vehicles
* Support for low- and medium-capacity fleets
* Experimental scalability analysis
* Modular architecture for testing alternative heuristics and solvers

## Research Context

This repository is inspired by:

> Javier Alonso-Mora, Samitha Samaranayake, Alex Wallar, Emilio Frazzoli, and Daniela Rus
> *On-demand high-capacity ride-sharing via dynamic trip-vehicle assignment*
> Proceedings of the National Academy of Sciences (PNAS), 2017
> DOI: [https://doi.org/10.1073/pnas.1611675114](https://doi.org/10.1073/pnas.1611675114)

This repository is an independent reimplementation and decomposition of the methods described in the paper and is not affiliated with the original authors.

## Objectives

The project aims to:

* understand the structure of large-scale ride-sharing optimization systems,
* reproduce key behaviors from the original framework,
* experiment with assignment and routing strategies,
* analyze tradeoffs between:

  * fleet size,
  * vehicle capacity,
  * wait time,
  * travel delay,
  * operational efficiency.
 

## Dataset

Experiments are intended to use publicly available NYC taxicab trip datasets and synthetic demand generation scenarios for testing scalability and routing behavior.

## License
This project is licensed under the BSD 2-Clause License. See the [`LICENSE`](LICENSE) file for details.
