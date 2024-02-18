# COPT 7.0

COPT (Cardinal Optimizer) is a mathematical optimization solver for large-scale optimization problems.
It includes high-performance solvers for LP, MIP, SDP, (MI)SOCP, convex (MI)QP and convex (MI)QCP.

The optimizer supports all major operating systems (64-bit), including Windows, Linux, and MacOS.
It provides interfaces to [Julia](https://github.com/COPT-Public/COPT.jl), Python, PuLP, Pyomo, Fortran, C, C++, C#, Java, AIMMS, AMPL, GAMS and CVXPY.

If you don't have a valid COPT 7.1 (or 7.0) license yet,
please apply for free personal license from [COPT application page](https://www.shanshu.ai/copt).
COPT 7.1 and COPT 7.0 licenses are compatible.

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
The latest COPT 7.1 patch release is COPT 7.1.0.
You can use it with any valid COPT 7.1 (or 7.0) license.

Download links for supported platforms are:

**Windows**<br>
  We recommend
  the [Installer](https://pub.shanshu.ai/download/copt/7.1.0/win64/CardinalOptimizer-7.1.0-win64-installer.zip),
  but you can use the [zip package](https://pub.shanshu.ai/download/copt/7.1.0/win64/CardinalOptimizer-7.1.0-win64.zip) too.

**MacOS**<br>
  We recommend
  the [Installer](https://pub.shanshu.ai/download/copt/7.1.0/osx64/CardinalOptimizer-7.1.0-universal_mac.dmg),
  but you can use the [tar.gz package](https://pub.shanshu.ai/download/copt/7.1.0/osx64/CardinalOptimizer-7.1.0-universal_mac.tar.gz) too.<br>
  **Please note that we replaced x86_64 and arm64 packages by the universal package for macOS.**

**Linux**<br>
  Please use the [tar.gz package](https://pub.shanshu.ai/download/copt/7.1.0/linux64/CardinalOptimizer-7.1.0-lnx64.tar.gz)

**Linux (ARM64)**<br>
  Please use the [tar.gz package](https://pub.shanshu.ai/download/copt/7.1.0/aarch64/CardinalOptimizer-7.1.0-aarch64_lnx.tar.gz)

## Release notes

```
COPT 7.1.0
==========
Main features of COPT 7.1:
COPT first-order LP solver with GPU support
COPT MIP solver performance improvements
COPT Python modelling performance improvements

Major components introduced in previous releases
Parallelized optimization solvers:
COPT MIP solver
COPT LP barrier solver
COPT LP simplex solver
COPT (MI)SOCP solver
COPT convex (MI)QP solver
COPT convex (MI)QCP solver
COPT SDP solver
Utilities:
COPT callback functionality
COPT IIS for infeasible problems
COPT Feas-Relax utility
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
