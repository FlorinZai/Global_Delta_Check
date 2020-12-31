% These codes check and reproduce some of the findings in Nienhuis et al. 2020 Nature paper

Prereq:
GlobalDeltaData.mat                  %Get the original database from https://osf.io/s28qb/

Files:
Besset_Deltas.csv                    %Delta changes from Besset et al. 2019 ESR paper
EE_44polys_change.csv                %Aqua change retrieved in EE
EE_108randomdeltas_ordered.csv       %User table with 108 random river mouths
Geometry_randomdelta_poly.csv        %44 polygons geometries and BasinId's used in EE
Global_deltas_area.csv               %Delta area retreived from original Nienhuis et al. 2020 script

Matlab files:
Randomdeltas_vs_Original_Stats.m     %Gets 108 random features/deltas, checks statistics
Data_check_Fig3_Table1_AquavsGSW.mlx %Checks Fig3, Table1 data and Aqua vs GSW comparrison.
Besset_Delta_Check.mlx               %Checks original change rates against Besset et al. 2019 data


EE script location for 44 deltas: https://code.earthengine.google.com/1c074d96779371d7bf20922916ca22f9
Generates EE_44polys_change.csv that is used in Randomdeltas_vs_Original_Stats.m script
