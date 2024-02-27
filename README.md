# ARCHER2_application_2024

![ASPECT Scaling Graph](https://github.com/Lukel13/ARCHER2_application_2024/assets/95885918/d2056432-75b7-4b43-9340-3ee380b19493)

Graph showing scaling for ASPECT using NIAGARA (dotted lines) and ARCHER2 (solid lines). The largest (25.7e7 DoF), medium (53.3e6 DoF), and smallest (2.4e6 DoF) models were ran on ARCHER2 to determine the optimum number of nodes to use for each model. It was found that large jobs run optimally on 15 nodes (using 128 cores per node), our medium jobs on 6 nodes, and our small jobs on 2 nodes. The optimum number of cores for each model on ARCHER2 is highlighted with a black outline.

The parameter files used for testing on ARCHER2 are uploaded here.
