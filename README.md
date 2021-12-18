<h1 align = "center">Queueing Theory Project</h1>

**Sharing of resources and waiting in queues is a common phenomenon that occurs in every facet of our lives.<br>
The understanding and prediction of the stochastic behavior of these queues will provide a theoretical insight into the dynamics of these shared resources and how they can be designed to provide better utilization.<br>**

> **Queueing Theory** is the study of queues comes under a discipline of *Operations Research*, and is a primary methodological framework for evaluating resource performance besides simulation.

## Queueing System Components
- ### The Input Process:
  1. **The size of arriving population (infinite and finite).**
  2. **Arriving patterns:**
     * Customers may arrive at a queueing system either in some regular pattern **(Deterministic QS)** or in a totally random fashion **(Stochastic QS)**.
     * If customers arrive according to some random mode, then we need to fit a probability distribution to the arriving pattern in order to render the queueing analysis mathematically feasible.
     * The parameter that we commonly use to describe the arrival process is the *inter-arrival time* between two customers.
  3. **Behavior of arriving customers:**
     * **Blocking system:** If an arriving customer finds the system is full and leaves forever without entering the system.
     * **Store and Forward System:** For example, if calls are placed in queues, it is referred to as “lost-calls-delayed” discipline.
- ### The System Structure:
  1. **Physical number and layout of servers.**
  2. **The system capacity.**
- ### The Output Process:
  1. **Queueing discipline or serving discipline:** The way in which customers in the waiting queue are selected for service.
     * First-Come-First-Served (FCFS). 
     * Last-Come-First-Served (LCFS).
     * Priority.
     * Processor Sharing.
     * Random.
  2. **Service-time distribution:** Similar to arriving patterns.
## Kendall Notation
**David G. Kendall devised a shorthand notation to describe a queueing system containing a single waiting queue.**
<h3 align = "center">A / B / X / Y / Z</h3>

- **A:** Customer Arriving Pattern (*Inter-arrival-time* distribution).
- **B:** Service Pattern (*Service-time* distribution).
- **X:** Number of Parallel Servers.
- **Y:** *System Capacity*.
- **Z:** Queueing Discipline.
## Queueing Models
### Deterministic QS:
**In this model the arriving patterns and the service time distributions are constants.<br>
Any deterministic queue has the following parameters:**
- **Constant arrival rate (λ):** ( the constant time between successive arrivals in which the *inter-arrival time* = 1/λ ).
- **Constant rate of service (μ):** ( number of service completions per unit time when the server is busy; constant *service-time* = 1/μ ).
- **A single server:** ( i.e. one service channel ).
- **The system capacity (K – 1):** ( if a customer would increase the total number in the system to **K**, he will be refused to enter ).
- **FIFO (or FCFS) discipline.**

**So The queueing model is called _D / D / 1 / (K - 1) / FCFS_.**

**if λ > μ:**
- The number of customers in the system will continue to increase indefinitely (i.e. unstable system).
- The queueing system can be made stable by assuming that the **system capacity** is constant.
- When the number of customers in the system reaches the **system capacity**, recent arriving customers will not be allowed to enter and they will never return (balking).
- So the number of customers in the system will continue to increase until **ti** (where **ti** represents the time of occurrence of the first balk).

**Otherwise (λ ≤ μ):**
- Here, we have a very simple situation since there is never more than one customer in the system.
- It is only interesting to study this situation if we start the queueing process with initial customers M in the system.
- The transient characteristics of this process will be studied here until it reaches its steady state.
### Stochastic QS:
**Any stochastic queue has the following parameters:**
- **Arrival rate (λ).**
- **Service rate (μ).**
- **One server or more (_c_ servers).**
- **The system capacity:** ( infinite **(∞)** or finite **(K)** system capacity ).
- **FIFO discipline.**
## About This Project
### Overview:
**The modeling and analysis of waiting queues/networks is the main implemented subject in this project.**
