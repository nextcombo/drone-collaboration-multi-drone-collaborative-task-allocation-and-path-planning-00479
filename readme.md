# [Drone Collaboration] Multi-Drone Collaborative Task Allocation and Path Planning [with MATLAB Code]

This chapter proposes a hierarchical framework for multi-UAV path planning and task allocation in dynamic environments. For the scenario of multiple agents in dynamic settings, candidate algorithms must be capable of replanning new paths to ensure they do not collide with obstacles or other agents when executing given tasks. The proposed path planning algorithm is based on the principles of visibility and shortest path in Euclidean space, utilizing A* search algorithm to find feasible paths in a "best-first" manner, avoiding the need to scan all nodes as traditional visibility graph methods do. To address dead-end situations that may arise in complex environments, additional processing procedures are introduced to avoid local minima and eliminate redundant nodes, while also integrating a potential field-based trajectory planner to handle the needs of other agents or sudden obstacles. Task allocation is achieved through a negotiation-based algorithm, where each agent initially selects the task with the lowest cost, and upon conflict, compare costs to determine the assignment of tasks. The algorithm is implemented in MATLAB/Simulink, allowing it to communicate with simulation vehicle models or actual UAV operations via a communication network. Simulation validation demonstrates the perfect performance of the algorithm in both task allocation and path planning, while flight tests further indicate that even in scenarios with real factors such as lost communication or tracking errors, the algorithm can enable UAVs to complete all tasks without collisions.
Introduction: Research Background and Significance - Drones (UAVs) are widely used in scenarios where human involvement is either unnecessary or dangerous. As tasks become more complex, the collaborative mode of "divided responsibility" among multiple UAVs has been proposed. This requires solving the question of "who performs which task in what order" and ensuring safe and efficient path planning for multiple UAVs within a specified area, especially during dynamic environments where paths need to be dynamically replanned to avoid obstacles. Task allocation and path planning are closely related; task allocation determines the sequence of tasks for each UAV, while path planning requires adjusting paths when known or unforeseen obstacles exist, ensuring that UAVs avoid ground objects or buildings.
II. Regarding the allocation of related work tasks, Mixed Integer Linear Programming (MILP) is powerful but its complexity rapidly increases with the increase in variables and requires centralized systems, which perform poorly in communication failures. Path planning must meet requirements such as completeness and optimality, and dynamic environments with unknown or sudden obstacles make the problem more complex. Existing research includes methods like MILP and Model Predictive Control (MPC), but finding a conflict-free path in real time under dynamic conditions remains challenging.
III. Research Content and Framework This chapter proposes a tiered framework: task allocation adopts an algorithm based on negotiation, with each agent initially selecting the lowest-cost task, and conflicts are resolved by comparing costs. Path planning is based on the Euclidean space shortest path principle, combined with A * algorithm search, introduces additional process optimization paths such as dead-end filtering, recursive filtering and Fibonacci filtering. Collision avoidance uses a potential field-based algorithm to handle sudden obstacles or conflicts between intelligent agents. The framework has been validated through simulation and flight tests, applicable to partially known or completely unknown environments.
Article illustrations
Conclusion This chapter proposes a hierarchical framework for multi-drone collaborative task allocation and path planning. Task allocation is based on a negotiation algorithm, while path planning integrates the A* algorithm with additional optimization processes, and collision avoidance employs the potential field method. Simulations and real flight tests demonstrate that this framework enables drones to complete tasks without collisions in scenarios with known / unknown obstacles and sudden threats, applicable to real multi-drone scenarios, providing a feasible solution for collaborative control in dynamic environments.
End

## Images

![[Drone Collaboration] Multi-drone Collaborative Task Allocation and Path Planning [with MATLAB Code]](01.jpg)
![[Drone Collaboration] Multi-drone Collaborative Task Allocation and Path Planning [with MATLAB Code]](02.jpg)
![[Drone Collaboration] Multi-drone Collaborative Task Allocation and Path Planning [with MATLAB Code]](03.jpg)
![[Drone Collaboration] Multi-drone Collaborative Task Allocation and Path Planning [with MATLAB Code]](04.jpg)
![[Drone Collaboration] Multi-drone Collaborative Task Allocation and Path Planning [with MATLAB Code]](05.jpg)
![[Drone Collaboration] Multi-drone Collaborative Task Allocation and Path Planning [with MATLAB Code]](06.jpg)
![[Drone Collaboration] Multi-drone Collaborative Task Allocation and Path Planning [with MATLAB Code]](07.jpg)
![[Drone Collaboration] Multi-drone Collaborative Task Allocation and Path Planning [with MATLAB Code]](08.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
