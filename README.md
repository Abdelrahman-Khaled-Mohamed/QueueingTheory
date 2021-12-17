<h1 align = "center">Queueing Theory</h1>

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
     * First-come-first-served (FCFS). 
     * Last-come-first-served (LCFS).
     * Priority.
     * Processor sharing.
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
