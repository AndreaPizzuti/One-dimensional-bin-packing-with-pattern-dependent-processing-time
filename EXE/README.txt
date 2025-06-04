1BP-VPT.exe was coded in C++ and compiled in Visual Studio 2017 with numerical precision set to 10⁻⁶. All the formulations are solved by using IBM CPLEX 22.1.1.0 with the settings CPX PARAM CLOCKTYPE = 1 and CPX PARAM THREADS = 1. 
It is required to have IBM CPLEX 22.1.1.0 installed on the machine with a valid license.    

To run the execution, use the command from windows shell:
1BP-VPT <instance_file> <parameter_file> run_CG

run_CG: 1 to run the column generation procedure; 0 to run only the primal heuristic

An example of command follows:
1BP-VPT BPP_50_50_0.1_0.8_0.A.txt p.txt 1

Parameter file format:

p Alpha1
weight of the number of bins N in the objective function, between [0,1] and Alpha1 + Alpha2 = 1

p Alpha2
weight of the maximum tardiness Tmax in the objective function, between [0,1] and Alpha1 + Alpha2 = 1

p Setup
setup time per bin

p ProcTime
processing time per item

p maxRunningTime
time limit in seconds allowed for the execution

p maxColumns
maximum number of column in mathematical programs
