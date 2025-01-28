# US-air-traffic-network
Air traffic networks are critical for the mobility of people, which makes them an interesting and important research field. This repository contains the study and the respective code obtained during the analysis of a longitudinal U.S air traffic network. The network was obtained from the Bureau of Transportation Statistics and contains yearly snapshots of flights among all commercial airports in the United States, ranging from 1990 to 2020. In this context, nodes correspond to airports and edges represent flight routes, containing a total of 2002 nodes and nearly 75 thousand edges.
In this study, the network is represented as a mono-layer directed graph network and the number of passengers was used  as the weight.

The present study has analyzed the structure and main metrics of the network and has performed a resilience and temporal analysis. More interestingly, it has been studied the impact of certain critical historical events on the network performance. For a quicker and easier dive on the study, you can check out my medium article :

If you are interested in a deeper and more technical presentation of the methodology, results and conclusions, please feel free to read the attached report. 

### Data source
You can download the network at: https://networks.skewed.de/net/us_air_traffic
In this project, the nodes.csv and edges.csv are the files that have been used. 

### Software
The analysis has been performed in Python using google collab. The main library used for network analysis was networkx.

### Acknowledgements
I would like to thank my collegues, Patryk Szpetnar and Linton Jones, who have contributed to the development of this project.
