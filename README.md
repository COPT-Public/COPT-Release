# COPT 8.0

COPT (Cardinal Optimizer) is a mathematical optimization solver for large-scale optimization problems.
It includes high-performance solvers for LP, MIP, SDP, (MI)SOCP, convex/nonconvex (MI)QP, convex/nonconvex (MI)QCP and exponential cone programming.

The optimizer supports all major operating systems (64-bit), including Windows, Linux, and MacOS.
It provides interfaces to [Julia](https://github.com/COPT-Public/COPT.jl), Python, PuLP, Pyomo, Fortran, C, C++, C#, Java, AIMMS, AMPL, GAMS and CVXPY.

If you don't have a valid COPT 8.0 license yet,
please apply for free personal license from [COPT application page](https://www.shanshu.ai/copt).

Full COPT documentation is available [here](https://guide.coap.online/copt/en-doc/index.html).

## Reference
If you used COPT in your research work, please mention us in your publication. For example:
  - We used COPT [1] in our project.
  - To solve the integer problem, we used Cardinal Optimizer [1].

with the following entry in the Reference section:<br>
[1] D. Ge, Q. Huangfu, Z. Wang, J. Wu. and Y. Ye. Cardinal Optimizer (COPT) user guide. https://guide.coap.online/copt/en-doc, 2022.

The corresponding BiBTeX citation is:
```
@misc{copt,
  author={Dongdong Ge and Qi Huangfu and Zizhuo Wang and Jian Wu and Yinyu Ye},
  title={Cardinal {O}ptimizer {(COPT)} user guide},
  howpublished={https://guide.coap.online/copt/en-doc},
  year=2022
}
```
## Download links
The latest COPT 8.0 patch release is COPT 8.0.1.

Download links for supported platforms are:

**Windows**<br>
  We recommend
  the [Installer](https://pub.shanshu.ai/download/copt/8.0.1/win64/CardinalOptimizer-8.0.1-win64-installer.zip),
  but you can use the [zip package](https://pub.shanshu.ai/download/copt/8.0.1/win64/CardinalOptimizer-8.0.1-win64.zip) too.

**macOS (Universal)**<br>
  We recommend
  the [Installer](https://pub.shanshu.ai/download/copt/8.0.1/osx64/CardinalOptimizer-8.0.1-universal_mac.dmg),
  but you can use the [tar.gz package](https://pub.shanshu.ai/download/copt/8.0.1/osx64/CardinalOptimizer-8.0.1-universal_mac.tar.gz) too.<br>

**Linux**<br>
  Please use the [tar.gz package](https://pub.shanshu.ai/download/copt/8.0.1/linux64/CardinalOptimizer-8.0.1-lnx64.tar.gz)

**Linux (ARM64)**<br>
  Please use the [tar.gz package](https://pub.shanshu.ai/download/copt/8.0.1/aarch64/CardinalOptimizer-8.0.1-aarch64_lnx.tar.gz)

## Release notes

```
COPT 8.0.1
==========
Added integer parameter PreRootHeurLevel for setting level of pre-root heuristics.
Improved performance of first-order solver.
Improved performance of SOCP solver.
Fixed bugs and issues.
Updated documentation.

COPT 8.0.0
==========
Introduced global nonconvex (MI)QCQP solver.
Added integer parameter LogLevel for configuring solver logs.
Changed the Python matrix modeling API to own implementation.

Improved performance and fixed numerous bugs.
Updated documentation and added public C++ example of facility problem.

Support for Python 2.7 and 3.6 is officially discontinued.


Major components introduced in previous releases:
Parallelized optimization solvers:
COPT MIP solver
COPT LP barrier solver
COPT LP simplex solver
COPT ExpCone solver
COPT SDP solver
COPT (MI)SOCP solver
COPT convex (MI)QP solver
COPT convex (MI)QCP solver
COPT LP/ExpCone/SDP/SOCP/QP/QCP solver with GPU-acceleration

Utilities:
COPT callback functionality
COPT multi-objective functionality
COPT IIS for infeasible problems
COPT Feas-Relax utility
COPT Sensitivity analysis
COPT Tuner

Modeling interfaces:
Object-oriented: Python, C++, C#, Java
Third-party    : Julia, AIMMS, AMPL, GAMS, PuLP, Pyomo, CVXPY
C interfaces which work with matrices and vectors

Licensing and remote services:
COPT personal license
COPT server license
COPT floating token server
COPT cluster server
COPT web license service

Supported platforms and OS:
Windows: x86
Linux  : x86 and arm64
MacOSX : x86 and arm64

```
