1BP-VPT.exe was coded in C++ and compiled in Visual Studio 2017 with numerical precision set to 10⁻⁶. All the formulations are solved by using IBM CPLEX 22.1.1.0 with the settings CPX PARAM CLOCKTYPE = 1 and CPX PARAM THREADS = 1.   

To run the execution, use the command from windows shell:
1BP-VPT <instance_file> <parameter_file>

An example of command follows:
1BP-VPT BPP_50_50_0.1_0.8_0.A.txt p.txt

