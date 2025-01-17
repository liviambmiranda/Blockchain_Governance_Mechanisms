# Overview
This repository contains a Python code to analyze **operational validity**, i.e., a parameter variability-sensitivity analysis for the simulation-based model based on varying the firms' participation probability. The simulation introduces concepts like quorum requirements and token-based incentives (voting power) for participation. The results are visualized as power imbalances over time, enabling analysis of the effects of different quorum and reward structures.

---

## Table of Contents :memo:

1. [Requirements](#requirements)  
2. [Key Features](#key-features)  
3. [Simulation Details](#simulation-details)  
4. [How to Run](#how-to-run)  
5. . [Notes](#notes)  

---

## Requirements :wrench:

- **Python 3.7+**  
- **Matplotlib** (for visualization)  

Install the required package via:

    pip install matplotlib

## Key Features :star:

1.  **Voting Simulation**:
    -   Firms in a network vote (shared decision-making) across multiple rounds.
    -   Voting probabilities are configurable, representing participation.
    
2.  **Quorum Requirements**:
    
    -   Different quorum thresholds (e.g., 50%, 70%, 80%, 90%) are simulated to analyze their impact on power imbalance.
    
3.  **Token Incentives**:
    
    -   Members earn tokens as rewards for voting.
    -  Tokens represent firms' voting power, i.e. the weight of each vote.
    -   Configurable token reward amounts (e.g., 1, 2, 3 tokens).
    
4.  **Power Imbalance Analysis**:
    
    -   Tracks the disparity in token distribution between the most and least rewarded members across voting rounds.
    -   Visualized as a graph for each quorum scenario.

----------

## Simulation Details :bulb:

1.  **Network Setup**:
    
    -   A network of members (`Membro`) is initialized. Each member:
        -   Has a unique ID.
        -   Votes probabilistically in each round.
        -   Earns tokens based on its participation and quorum fulfillment.
        
2.  **Voting Rounds**:
    
    -   Simulates multiple voting rounds.
    -   Checks if the number of voters meets the quorum requirement.
    -   Updates token counts for members who participated.
    
3.  **Power Imbalance**:
    
    -   The difference between the maximum and minimum token counts among members is calculated after each round.
    -   Results are stored for visualization.
    
4.  **Visualization**:
    
    -   Graphs show power imbalance over voting rounds for each quorum scenario.
    -   Multiple graphs are generated to compare token rewards (`1`, `2`, `3`).

----------

## How to Run :checkered_flag:

1.  **Clone or Download** this repository.
2.  **Set Up Parameters**:
    -   Quorum levels are set in the `quoruns` list (e.g., `[0.5, 0.7, 0.8, 0.9]`).
    -   Token rewards are defined in `tokens_added_values` (e.g., `[1, 2, 3]`).
3.  **Run the Script**:
    -   Execute the script in any Python environment.
    -   Ensure `matplotlib` is installed to generate visualizations.
4.  **View Results**:
    -   Graphs will be saved as `amplitude_quorum_<quorum>.pdf` for each quorum scenario.
    -   Each graph plots power imbalance across rounds, with separate lines for different token rewards.

----------

## Notes :bulb:

-   **Customization**:
    -   Adjust `quantidade_membros` in the `Rede` class to simulate networks of different sizes.
    -   Modify voting probabilities in the `gerar_voto` method of the `Membro` class to simulate varying participation rates.

