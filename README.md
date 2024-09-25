This project contains the executable file and the instances used in F. Marinelli, A. Pizzuti, W. Wu and M. Yagiura, "One-dimensional bin packing with pattern-dependent processing time", under review, 2024.

This work deals with an integrated one-dimensional bin packing problem with scheduling: a due date is assigned to each item and the time required to process each bin depends on the pattern being used. The objective is to minimize a convex combination of the number of bins N and the maximum tardiness Tmax, both significant in many real-world contexts. The authors present a novel pattern-based mixed integer linear formulation [M2] and a refined formulation with bin-wise Tmax constraints [M2Ag] tackled by a branch-and-price algorithm, where the pricing of the column generation scheme is a quadratic problem solved by dynamic programming. The solution algorithm embeds a sequential value correction heuristic (SVC) used to feed with warm starting solutions the column generation which, in turn, feeds the SVC with optimal prices so as to compute refined feasible solutions during the enumeration.

In One-dimensional-bin-packing-with-pattern-dependent-processing-time/EXE the executable file 1BP_VPT.exe and the parameter file p.txt are given, along with README files explaining how to customize and run the algorithm.  

In One-dimensional-bin-packing-with-pattern-dependent-processing-time/INSTANCES the three sets of instances used in the paper are provided, along with a README file presenting the details of the instance generation procedure and the instance characteristics.

The program outputs the file "summary.csv" where the relevant stats and results are reported, one row per each solved instance.

For any inquiries, you can contact the author Andrea Pizzuti at andrea.pizzuti@bilkent.edu.tr.  
