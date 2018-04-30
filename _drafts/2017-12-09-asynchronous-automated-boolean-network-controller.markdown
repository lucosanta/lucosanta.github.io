---
layout: post
title:  "Asynchronous Population Based Development of Boolean Network Controller"
date:   2017-12-10 17:03:21 +0100
categories: robotics
tags: ['robotics','complex-systems']
abstract: 'This is my abstract'
keywords: boolean network, asynchronous, genetic algorithms, complex systems
---


In this post, I will introduce and explain all the choices made during the project design and development.

## Boolean Networks

**Boolean Networks** (**BNs**) have been introduced by Stuart Kauffman [^fn1] [^fn2]  as a model for **genetic regulatory networks** (GRN) and as an abstraction of **complex systems** in order to study the mechanisms of *evolutionary processes in living beings*. The BN structure can be thought of as a directed graph composed by a number of nodes defined by `N`. The number of input arcs for each node is usually defined as `K`. Each node xi is associated to a Boolean variable and a Boolean function. The arguments of this function are the Boolean variables of the nodes whose outgoing arcs are connected to xi.
A simple example of BN is shown in Figure 1. The topologies of a BN can be various and they depend on the specic application eld. A fundamental concept for BN is the **state** which represent all Boolean variables value of all the nodes in a given instant of time `t`. Due to the binary space in which BNs are, the state space size is `2N`. The BN dynamic behaviour is characterized by a sequence of state updates (i.e., each node changes the value of its
Boolean variable according to the associated Boolean function). 


## References

[^fn1]:  S. Kauffman, "The Origins of Order: Self-Organization and Selection in Evolution". UK: Oxford University Press, 1993.

[^fn2]: S. Kauffman, "Metabolic stability and epigenesis in randomly constructed genetic nets," J. Theoret. Biol. 22, pp. 437--467, 1969.
