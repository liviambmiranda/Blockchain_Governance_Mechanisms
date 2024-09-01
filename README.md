### Simulation Analysis of Blockchain Governance Mechanisms for Inter-Organizational Collaboration in Virtual Enterprises and Virtual Breeding Environments

This project refers to an analytical model based on a simulation of firms' participation to evaluate the long-term feasibility of blockchain governance mechanisms.

This repository contains the Python 3 programming language implementation and descriptions. 

- To support operational validity, a parameter variability-sensitivity analysis was performed varying the firms' participation probability (70%, 80%, 90%). Please check the code and visit [Validity_Analysis](Simulation_Model/Operational_Validity).
- To evaluate power imbalance between organizations, the difference between the maximum and minimum token holdings among organizations was calculated after each voting round, quantifying the inequality in voting power after each iteration. Please check the code and visit [Power_Imbalance](Simulation_Model/Power_Imbalance).
- To evaluate administrative efficiency, the number of voting iterations that reached the minimum quorum, i.e., the system's rate of valid decisions after 10,000 iterations, was calculated. Please check the code and visit [Administrative_Efficiency](Simulation_Model/Administrative_Efficiency).



