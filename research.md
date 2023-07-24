---
layout: page
permalink: /research/
title: Project Structure
tags: [code]
modified: 24-04-2017
comments: false
---
## Vision and Goals

The vision of QUADRATURE is the realization of million-qubit quantum computing architectures able to address real-world problems otherwise intractable with conventional computers. Such architectures would be based on a modular and scalable multi-Qcore approach enabled by a quantum-coherent and a classical wireless communication network within the cryogenic package. To realize this vision, QUADRATURE proposes an all-RF solution to the problem of building an integrated, scalable, and agile network spanning both quantum state and classical data transfers. See our [position paper](https://arxiv.org/abs/2303.14008) for more details.

<br/>

To this end, the project aims to achieve the following objectives:

+ **To experimentally prove** the first micro-integrated all-RF qubit state transfer link between different Qcores.
+ **To experimentally achieve** the transfer of classical data through wireless in-package links enabled by integrated antennas at deep-cryogenic temperatures co-integrated with cryo-RF transceivers.
+ **To build protocols** for a quantum-coherent integrated network enabling the exchange of qubit states through the coordination of the quantum-coherent data plane and the wireless control plane.
+ **To develop innovative scalable architectural methods** such as mapping, scheduling, and coordination approaches across multiple Qcores that leverage an underlying reconfigurable control plane.
+ **To demonstrate the scalability of the QUADRATURE approach** via transversal multi-scale design space optimization and for a set of quantum algorithm benchmarks.

## Project Structure
<img src="/images/Qpert_chart.png"/>
 
<br/>
<br/>

The QUADRATURE research project takes a full-stack approach and touches upon different aspects of design that go from the implementation of cryogenic quantum cavity channels and wireless communications within package up to the development of scalable architectural strategies and quantum algorithms. Research is divided into seven work packages, five of which are technical work packages. 

+ **WP1: Quantum Coherent Link:** WP1 is devoted to the integration of quantum communication links with quantum computational functions in the microwave and mm-wave frequency range, which is a key requirement for the scaling of quantum computing platforms. More precisely, in this WP, the quantum cavity channel and its monolithic integration into Qcore solutions will be modeled, fabricated and characterized. 

+ **WP2: Cryogenic Wireless Link:** WP2 develops the deep-cryogenic transceiver for inter-Qcore classical communication, tightly coupled with quantum coherent link, the wireless control plane and the quantum architecture. In detail, the aim is the experimental demonstration of deep-cryogenic (1-4K) short-range (~10cm) communication using the developed high-efficiency  transceiver co-integrated with on-chip mm-wave antennas. 

+ **WP3: Communications within Quantum Package:** WP3 develops the quantum communications plane operating within the quantum package, enabled by the tight interplay between the quantum coherent links and the associated wireless links at cryogenic temperatures, while bound to the requirements of the quantum architecture. To this purpose, we will characterize the wireless channels within the quantum package, develop full stack of protocols including scheduling and network orchestration and obtain performance and efficiency models to be integrated in the system architecture and algorithm analysis.

+ **WP4: Quantum System Architecture:** WP4 focuses on the definition of the multi-Qcore distributed architecture and development of corresponding optimised mapping solutions for a set of representative and relevant quantum applications. In detail, the main goals are to design a parameterizable and reconfigurable multi-Qcore platform, to develop mapping and scheduling methodologies and on-line inter-Qcore connectivity optimization and to define a complete collection of large-scale quantum algorithms. 

+ **WP5: Model-Based Cross-Layer Architecture Simulation and Benchmarking:** WP5 aims at designing, architecting and evaluating the wireless-enabled double full-stack quantum system by means of a model-based cross-layer system architecture simulation framework. In particular, we will derive optimal configurations of the double full-stack, dimensioning guidelines and scalability trends, perform an architecture-application co-design of the communication and computational stacks and assess and stress inter-Qcore communication overheads in large instances of the quantum system.














