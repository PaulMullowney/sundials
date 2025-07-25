# IDAS
### Version 6.4.0 (Jun 2025)

**Radu Serban, Cosmin Petra, Alan C. Hindmarsh, Cody J. Balos, David J. Gardner,
  and Carol S. Woodward, Center for Applied Scientific Computing, LLNL**

**Daniel R. Reynolds, Department of Mathematics, Southern Methodist University**


IDAS is a package for the solution of differential-algebraic equation (DAE)
systems
```
F(t,y,y',p) = 0, y(t0) = y0(p), y'(t0) = y0'(p)
```
with sensitivity analysis capabilities (both forward and adjoint modes). The
integration methods used in IDAS are variable-order, variable-coefficient BDF
(Backward Differentiation Formula) methods in fixed-leading-coefficient form.

IDAS is part of the SUNDIALS Suite of Nonlinear and Differential/Algebraic
equation Solvers which consists of ARKode, CVODE, CVODES, IDA, IDAS and KINSOL.
It is written in ANSI standard C and can be used in a variety of computing
environments including serial, shared memory, distributed memory, and
accelerator-based (e.g., GPU) systems. This flexibility is obtained from a
modular design that leverages the shared vector, matrix, linear solver, and
nonlinear solver APIs used across SUNDIALS packages.

## Documentation

See the IDAS documentation at [Read the Docs](https://sundials.readthedocs.io/en/latest/idas)
for more information about IDAS usage.

## Installation

For installation instructions see the
[SUNDIALS Installation Guide](https://sundials.readthedocs.io/en/latest/Install_link.html).

## Release History

Information on recent changes to IDAS can be found in the "Introduction"
chapter of the IDAS User Guide and a complete release history is available in
the "SUNDIALS Release History" appendix of the IDAS User Guide.

## References

* R. Serban, C. Petra, A. C. Hindmarsh, C. J. Balos, D. J. Gardner,
  D. R. Reynolds and C. S. Woodward, "User Documentation for IDAS v6.4.0,"
  LLNL technical report UCRL-SM-234051, Jun 2025.

* R. Serban and A.C. Hindmarsh, "Example Programs for IDAS v6.4.0,"
  LLNL technical report LLNL-TR-437091, Jun 2025.

* A. C. Hindmarsh, P. N. Brown, K. E. Grant, S. L. Lee, R. Serban,
  D. E. Shumaker, and C. S. Woodward, "SUNDIALS, Suite of Nonlinear and
  Differential/Algebraic Equation Solvers," ACM Trans. Math. Softw.,
  31(3), pp. 363-396, 2005.
