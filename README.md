# Influencer_Optimal_Selection
This project aims to compare and analyze results from different optimization methods—MILP using branch and bound, MILP using branch and cut, and Genetic Algorithm—to identify the best approach for selecting influencers based on engagement and cost for a marketing campaign.

The dataset used in this analysis is sourced from a Kaggle collection, specifically curated to include top Instagram influencers. This dataset provides a rich set of attributes detailing various aspects of influencer presence and activity on the platform. It spans ten key features, arranged based on the rank determined by the number of followers.

For this analysis, three distinct methodologies were employed to optimize the selection of influencers for marketing campaigns:

#### MILP Branch and Bound: 
This method solves the influencer selection problem as a Mixed Integer Linear Program (ILP) using Gurobi, exploring feasible solutions and evaluating each combination to find the optimal selection with adherence to budget and time constraints.

#### MILP Branch and Cut: 
An enhanced version of Branch and Bound with additional cutting planes, speeding up convergence and handling larger datasets while maintaining solution accuracy.

#### Genetic Algorithm: 
Utilizes a population-based approach with selection, crossover, and mutation to explore complex, non-linear relationships between influencers and target variables like engagement, cost, and time.
