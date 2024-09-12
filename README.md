### (1) Empirical Validation and Testing of Blockchain Governance Mechanisms for Inter-Organizational Collaboration in Virtual Enterprises and Virtual Breeding Environments

This project refers to an analytical model based on statistics to evaluate construct reliability and perform hypothesis testing.

- Please check the code used to calculate Cronbach's alpha and inter-item correlations (Kendall tau) and to assess the sample's normality in [Reliability](Empirical_Analysis/Construct_Reliability).
- Please check the code used to test the research hypotheses using a one-tailed Wilcoxon signed-rank in [Hypotheses](Empirical_Analysis/Hypotheses_Testing).
- Please check the code used to evaluate the common method bias of the definitions added in the questionnaire used to survey academics and practitioners in [Sentiment Analysis](Empirical_Analysis/Sentiment_Analysis). 


### (2) Simulation Analysis of Blockchain Governance Mechanisms for Inter-Organizational Collaboration in Virtual Enterprises and Virtual Breeding Environments

This project refers to an analytical model based on a simulation of firms' participation to evaluate the long-term feasibility of blockchain governance mechanisms.

This repository contains the Python 3 programming language implementation and descriptions. 

- To support operational validity, a parameter variability-sensitivity analysis was performed varying the firms' participation probability (70%, 80%, 90%). Please check the code and visit [Validity_Analysis](Simulation_Model/Operational_Validity).
- To evaluate power imbalance between organizations, the difference between the maximum and minimum token holdings among organizations was calculated after each voting round, quantifying the inequality in voting power after each iteration. Please check the code and visit [Power_Imbalance](Simulation_Model/Power_Imbalance).
- To evaluate administrative efficiency, the number of voting iterations that reached the minimum quorum, i.e., the system's rate of valid decisions after 10,000 iterations, was calculated. Please check the code and visit [Administrative_Efficiency](Simulation_Model/Administrative_Efficiency).
- To evaluate token distribution, after each voting iteration that reached the minimum quorum, please check the code and visit [Administrative_Efficiency](Simulation_Model/Token_Distribution).



