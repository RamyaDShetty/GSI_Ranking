# GSI_Ranking
This repository contains the code for our work "GSI: An Influential Node Detection Approach in Heterogeneous Network using Covid-19 as Use Case".

This work mainly focuses on the influential node detection approach in real-world complex network analysis. This approach combines local and global parameters to obtain the influence of each node in the network. Effect of GSI is evaluated by using complex network and epidemiological data. The GSI approach is illustrated with the toy example, and the effect of GSI on the epidemiological data is also provided.

toynetwork_influence.py will have the implementation of the  GSI algorithm (toy data is used).

Graph creation (identifying pair-wise distance between the geo-coordinates) is present in haversine.py.

proximity distance is less than 1 will be computed from distance_calculation.py 

global_and_local_influence.py will have the implentation of GSI algorithm (Haslemere.csv)
