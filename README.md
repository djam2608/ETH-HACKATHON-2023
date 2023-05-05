# ETH-HACKATHON-2023
# An Expedition to Kilimanjaro.

Welcome to an exciting quantum computing challenge that will take you on an adventure to the summit of Kilimanjaro!

As you journey up the mountain, you'll encounter a series of camps where you can rest and recharge. Your ultimate goal is to reach Kibo, the highest peak of Kilimanjaro, by finding the shortest possible path that visits each camp along the way.

But there's a catch: This problem is known to be an NP-Hard problem, so to solve it efficiently, you'll need to use the power of quantum computing! Throughout this challenge you'll have the chance to explore the full stack of quantum computation, from the hardware level to the more abstract quantum algorithms and software development.

So pack your bags and get ready for an exciting journey up Kilimanjaro!


## Challenge Description

This challenge will consist of three different parts of different thematics and difficulties that will explore all the stack of technologies in quantum computing. 

The first challenge is an **introductory tutorial problem**, in which you'll tackle the famous Traveling Salesman Problem (TSP) for a graph of 3 nodes. To solve this problem we will use both Quantum Alternating Operator Ansatz (QAOA) and Adiabatic Quantum Optimization (AQO). This challenge serves as a preparation to solve a more difficult instance of the TSP. 

After this first introduction, we will be ready to solve real **software** challenges that we face when developing a quantum algorithm for current NISQ devices. 

In this challenge we will increase the number of nodes to 5 nodes by adding a starting and ending nodes to the salesman travels. However, we are restricted to solve this problem on a quantum computer that only has 6 qubits. In this challenge you will learn a lot about how to optimize your cost function and data representation in order to account for the limitations of currect quantum computers. 

Now that we are familiar with the algorithm we are ready to run it in real **hardware**!! During the **third challenge** will explore the exciting world of flux qubits and the hardware side of the annealing process. But beware!! This is a challenging open ended problem. The simulation of a quantum superconducting circuit may takes hours or even days so you must be extremelly careful with time management in this part of the challente. This last part is the perfect time to unleash your imagination as a researcher and to propose novel solutions to a problem of high interest. 

In the <u>first part</u>, you will be asked to design a custom quantum annealing circuit by adding the necessary qubits and couplers, and then optimize this design to achieve the best performance. You are free to choose the type of qubits and its layouts. The more realistic the best. Will you be able to run a test simulation of your circuit?   

In the <u>second part</u>, you will apply the insights gained from the first part to improve the fidelity of the solution for the TSP Hamiltonian in the introductory problem, by finding a better annealing schedule. For that matter, we will ask you to device techniques to find the minimum energy gap of the problem Hamiltonian. To device a Ising schedule to achieve the best performance. At last, you will design techniques to find the corresponding flux schedule. Are you able to do a simulation of this part? 


## Team delivery

Each team will be asked to create a fork from this repo where they will be developing their code. Then, when they are done they will have to create a pull request with all of the code, short report, and any supporting material they would like to attach. 

The report should contain a justification to all the design choices made throughout the competition. This report has to be less than 5 pages long. 
