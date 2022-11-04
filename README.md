# COPT 6.0

COPT (Cardinal Optimizer) is a mathematical optimization solver for large-scale optimization problems.
It includes high-performance solvers for LP, MIP, SDP, (MI)SOCP, convex (MI)QP and convex (MI)QCP.

The optimizer supports all major operating systems (64-bit), including Windows, Linux, and MacOS.
It provides interfaces to [Julia](https://github.com/COPT-Public/COPT.jl), Python, PuLP, Pyomo, Fortran, C, C++, C#, Java, AMPL, GAMS and CVXPY.

If you don't have a valid COPT 6.0 license yet,
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

The latest COPT 6.0 patch release is COPT 6.0.1.
You can use it with any valid COPT 6.0 license.

Download links for supported platforms are:

**Windows**<br>
  We recommend
  the [Installer](https://pub.shanshu.ai/download/copt/6.0.1/win64/CardinalOptimizer-6.0.1-win64-installer.zip),
  but you can use the [zip package](https://pub.shanshu.ai/download/copt/6.0.1/win64/CardinalOptimizer-6.0.1-win64.zip) too.

**MacOS (Intel)**<br>
  We recommend
  the [Installer](https://pub.shanshu.ai/download/copt/6.0.1/osx64/CardinalOptimizer-6.0.1-osx64.dmg),
  but you can use the [tar.gz package](https://pub.shanshu.ai/download/copt/6.0.1/osx64/CardinalOptimizer-6.0.1-osx64.tar.gz) too.

**MacOS (Apple M1)**<br>
  We recommend
  the [Installer](https://pub.shanshu.ai/download/copt/6.0.1/aarch64/CardinalOptimizer-6.0.1-aarch64_mac.dmg),
  but you can use the [tar.gz package](https://pub.shanshu.ai/download/copt/6.0.1/aarch64/CardinalOptimizer-6.0.1-aarch64_mac.tar.gz) too.

**Linux**<br>
  Please use the [tar.gz package](https://pub.shanshu.ai/download/copt/6.0.1/linux64/CardinalOptimizer-6.0.1-lnx64.tar.gz)

**Linux (ARM64)**<br>
  Please use the [tar.gz package](https://pub.shanshu.ai/download/copt/6.0.1/aarch64/CardinalOptimizer-6.0.1-aarch64_lnx.tar.gz)

## Release notes

```
COPT 6.0.1
==========
Improved performance of MISOCP solver
Improved performance of SDP solver
Improved accuracy of QP solver
Added support to cluster logging files and callbacks
Added support to user parameters in bin file formats
Added CROSSOVER=-1 which runs crossover to cleanup LP solutions
Fixed a compatible issue regarding old Linux arm64 system
Fixed other issues in MIP solvers
Revised COPT documentations

COPT 6.0.0
==========
Major components introduced in COPT 6.0
COPT MISOCP solver
COPT convex MIQP solver
COPT convex MIQCP solver

Major components introduced in previous releases
Parallelized optimization solvers:
COPT MIP solver
COPT LP barrier solver
COPT LP simplex solver
COPT SOCP solver
COPT convex QP solver
COPT convex QCP solver
COPT SDP solver
Utilities:
COPT IIS for infeasible problems
COPT Feas-Relax utility
COPT Tuner

Modeling interfaces:
Object-oriented: Python, C++, C#, Java
Third-party    : Julia, AMPL, GAMS, PuLP, Pyomo, CVXPY
C interfaces which work with matrices and vectors

Licensing and remote services:
COPT personal license
COPT server license
COPT floating token server
COPT cluster server

Supported platforms and OS:
Windows: x86
Linux  : x86 and arm64
MacOSX : x86 and arm64
```
