# Rapid-aversive-and-memory-trace-learning_Current_Biol_2020
Data for Rapid aversive and memory trace learning  during route navigation in desert ants. Current_Biol_2020


%------------- Melophorus data, Group track, figure 1--------------------

Melophorus_Group_Data_Paths.csv: raw X,Y coordinate of the Paths of ants according to each condition as presented in figure 1.
Melophorus_Group_Data_fell_bridge_detour.csv: Indicate whether the ant fell into the trap (0), hit directly the bridge (1), or successfully detoured the trap (2) according to each condition as presented in figure 1.

%------------- Cataglyphis data, Group track, figure 1--------------------
Cataglyphis_Group_Data_Paths.csv: raw X,Y coordinate of the Paths of ants according to each condition as presented in figure 1.

Cataglyphis_fell_avoid_table.csv: Indicate whether the ant fell into the trap (0) or successfully detoured the trap (2).


%------------- Melophorus data, ontogeny of individuals, figure 2--------------------
Melophorus_Individual_Data_Scan_position.csv: raw X,Y coordinate of the Scans observed for all the ants. Trial = 0 indicate the ant was recorded before the trap was set. Then trial 1->n indicate the trial number for each individual since the trap is in place. 

Melophorus_Individual_Data_Paths.csv: raw X,Y coordinate of the Paths of ants. Trial = 0 indicate the ant was recorded before the trap was set. Then trial 1->n indicate the trial number for each individual since the trap is in place. 

Melophorus_Individual_Data_computed.csv: meander and number of scans observed before and after the trap (1st part of the route and second part of the route) for each ant. Trial = 0 indicate the ant was recorded before the trap was set. Then trial 1->n indicate the trial number for each individual since the trap is in place. The fell_bridge_detour variable, indicate whether the ant fell into the trap (0), hit directly the bridge (1), or successfully detoured the trap (2).
Melophorus_Individual_Data_all.mat: Matfile compiling all the above into one structure for Matlab. 

Melophorus_Scan_data.csv: Number of scan displayed before and after the trap for each ant, as presented in figure 2. We discarded here (as in the analysis) all the ants that did not fell into the trap because they happened to hit the bridge. 

