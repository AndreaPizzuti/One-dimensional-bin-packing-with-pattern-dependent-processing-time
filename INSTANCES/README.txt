Instance sets used in F. Marinelli, A. Pizzuti, W. Wu, and M. Yagiura, "One-dimensional bin packing with pattern-dependent processing time", under review, 2024.

We indicate with n the number of the items and l the size of the bins in the one-dimensional bin packing (1BP) instance.
Instances for 1BP with variable pattern processing time (1BP-VPT) were obtained by adding integer due dates from the uniform distribution within the interval [s+t, B(s*NLB_c + t*n) ], where s = 1 is the bin setup time, t = 0.2 is the item processing time, NLB_c is the continuous lower bound on the 1BP instance. Finally, three values of B were considered, namely 0.6, 0.8, and 1.0, to generate three classes of instances A-, B-, and C- respectively.

non-IRUP_IH
Original instances not satisfying the Integer Round-Up Property for 1BP can be found at https://github.com/CaPaD-cutting-and-packing.
This set counts 159 instances with n ∈ [20, 200] and l = 1000, divided into classes A-, B-, and C- each one of 53 instances.

Random_IR
The set IR was obtained by adding due dates of type C to a subset of 360 random instances selected from
the BPPLIB library by M. Delorme, M. Iori, and S. Martello, "BPPLIB: A library for bin packing and cutting stock problems" Optimization Letters, 12(2) 235-250, 2018.
Instances, all with item sizes within [0.1l, 0.8l], are grouped in tens named BPP_<n>_<l>, with n ∈ {50, 100, 200} and l ∈
{50, 75, 100, 120, 125, 150, 200, 300, 400, 500, 750, 1000}.

Random_small_Ir
New set Ir of 120 small random instances BPP_20_<l>, with l ∈ {50, 75, 100, 120, 125, 150, 200, 300, 400, 500, 750, 1000} and due dates of type C, has been generated to test the branch-and-price.

Each instance is a .txt file formatted as follows:

l, n, dummy_value
for each item i(i=1,...,n):
  size (lj), demand (1), due date (dj)
