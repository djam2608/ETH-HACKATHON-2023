# ETH-HACKATHON-2023
# An Expedition to Kilimanjaro.

Welcome to an exciting quantum computing challenge that will take you on an adventure to the summit of Kilimanjaro!

As you journey up the mountain, you'll encounter a series of camps where you can rest and recharge. Your ultimate goal is to reach Kibo, the highest peak of Kilimanjaro, by finding the shortest possible path that visits each camp along the way.

But there's a catch: This problem is known to be an NP-Hard problem, so to solve it efficiently, you'll need to use the power of quantum computing! Throughout this challenge you'll have the chance to explore the full stack of quantum computation, from the hardware level to the more abstract quantum algorithms and software development.

So pack your bags and get ready for an exciting journey up Kilimanjaro!


## Challenge Description

This challenge will consist of three different parts that will explore the different aspects of quantum computation. 

The first Part is an **introductory problem**. This problem aims to introduce all the participants to the main problem we would like to tackle within this challenge which is  the Traveling Salesman Problem (TSP). This is a very interesting NP-hard optimization problem. In the first part of this challenge we would like you to solve this problem for a graph of 3 nodes using both Quantum Alternating Operator Ansatz (QAOA) and Adiabatic Quantum Optimization (AQO).

The first Part is an **introductory problem**, in which you'll tackle the famous Traveling Salesman Problem (TSP) for a graph of 3 nodes. To solve this problem we will use both Quantum Alternating Operator Ansatz (QAOA) and Adiabatic Quantum Optimization (AQO). This part aims to introduce you to the main problem we'll tackle in this challenge.

Next, the challenge splits into two complementary tracks (software and hardware) and you can choose to complete one or both:

The **software track** dives deeper into the challenges you might face when developing a quantum algorithm for current NISQ devices.

The <u>first part</u> of this challenge we will increase the number of nodes to 5 nodes by adding a starting and ending nodes to the salesman travels. However, we are restricted to solve this problem on a quantum computer that has a maximum of 9 qubits. This problem asks you to find ways to add these extra nodes without increasing the number of qubits. 

Then for <u>second part</u> we will change the graph back to only having 3 nodes for simplicity. However, this time without restricting the starting or ending points of the travels. Nevertheless, this time we only have access to a quantum computer with 6 qubits. This problem asks you to try and investigate ways to reduce the number of qubits to 6 or less. 

The **hardware track** will explore the exciting world of flux qubits and the hardware side of the annealing process.

In the <u>first part</u> of this track, you will be challenged to design a custom quantum annealing circuit by adding the necessary qubits and couplers, and then optimize this design to achieve the best performance. 

In the <u>second part</u>, you will apply the insights gained from the first part to improve the fidelity of the solution for the TSP Hamiltonian in the introductory problem, by finding a better annealing schedule.


## Team delivery

Each team will be asked to create a fork from this repo where they will be developing their code. Then, when they are done they will have to create a pull request with all of the code, short report, and any supporting material they would like to attach. 

The report should contain a justification to all the design choices made throughout the competition. This report has to be less than 4 pages long (Unless you did both tracks and have a lot of information to add). 

