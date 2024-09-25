Parameter file format:

p Alpha1
weight of the number of bins N in the objective function, between [0,1] and Alpha1 + Alpha2 = 1

p Alpha2
weight of the maximum tardiness Tmax in the objective function, between [0,1] and Alpha1 + Alpha2 = 1

p Setup
setup time per bin

p ProcTime
processing time per item

p cplexHeuristic
0 (not used)

p maxRunningTime
time limit in seconds allowed for the execution

p maxColumns
maximum number of column in mathematical programs

p printLevel
enable print of detailed information (>= 0). Suggested 0

p aggregatedModel
0 = use model [M2] in section 3.2, 1 = use model [M2Ag] in section 4

p onlyRoot: 
1 = solve by CG the continuous relaxation at the root node, 0 = use branch-and-price

p allcolumns
1 (not used)

p earlyTermination
0 (not used)

p RoundingPostProcessing
1 (not used)

p RoundingChecking
0 (not used)

p roundingByFixing
1 (not used)

p incrPricing
0.001 (not used)

p cntIncrPricing
0 (not used)

p nodesAllColumns
1 (not used)

p alwaysrounding
1 (not used)
