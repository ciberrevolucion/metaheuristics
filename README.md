# metaheuristics
Python scripts developed to model and solve a linear optimization problem using BRKGA and GRASP metaheuristics.

The problem statement is:

Given
1. O offices and C data centers,
2. a fixed cost fc per data center,
3. an additional segmented cost with P segments,
4. the available data centers to each office u[c,o],
5. that at least two centers must contain the data of each office o,
6. that each office contains d[o] Peta-Bytes,
7. that each center can store k[c] Peta-Bytes,
we want to know
1. which data centers should each office use, and
2. how much data each office has to store at each data center.
