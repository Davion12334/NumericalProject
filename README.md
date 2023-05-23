# NumericalProject

The code defines a square domain bounded by (a, b) and (c, d).It specifies the number of grid nodes (Ns) for discretization of the domain.It generates the necessary table and variables for monitoring errors and ratios.The code then initiates a loop that traverses the different grid sizes (N) supplied in Ns.It calculates the step size (h) and constructs a linspace grid for each grid size.The boundary conditions and exact solution of the Poisson equation are specified.The code initializes the solution matrix (u) and generates a copy (U) for future modifications.The Poisson equation is solved using an iterative approach (Gauss-Seidel algorithm). It modifies the solution matrix by incorporating values from neighboring grid points.Repeat the iteration process until the solution converges (the greatest difference between successive solutions is less than a tolerance).The algorithm calculates the difference (U) between numerical and exact solutions.It calculates the utmost error and error ratios based on previous grid sizes.The results are presented in tabular format.The cycle is repeated for varying grid sizes, and the procedure is executed multiple times.Finally, the algorithm displays the answer and error using a 3D surface plot.
