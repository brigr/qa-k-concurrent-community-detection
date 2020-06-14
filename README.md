# qa-k-concurrent-community-detection
This repository will provide a custom implementation of the k-concurrent community detection mathematical model that is proposed in the paper titled "Detecting multiple communities using quantum annealing on the D-Wave system" by Negre, et al. The model defines a QUBO instance which we prepare in Python for graphs of any directionality, be them weighted or unweighted ones. For any such input graph, a user can compute vertex-community assignments by defining an edgelist text-file argument and a parameter $k$ which defines the number of communities that should be found.

A user who will be using this script should be able to use one of the classic QUBO solvers (such as dimod or QBSolv), or directly use the D-Wave Ocean API to submit the locally computed parameters of the QUBO problem to the DW-2000Q.

The reason for the creation of this repository is research study on quantum community detection performed by student Sotiris Karavarsamis (Interfaculty graduate study program on Complex Systems and Networks, Aristotle University of Thessaloniki, Greece). This repository, in part, aims at reproducing the experiments reported in Negre et al.

Code will be published very soon!

Need to make contact? Please e-mail me at sotikara@econ.auth.gr.
