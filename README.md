# COPT 7.2

COPT (Cardinal Optimizer) is a mathematical optimization solver for large-scale optimization problems.
It includes high-performance solvers for LP, MIP, SDP, (MI)SOCP, convex (MI)QP, convex (MI)QCP and exponential cone programming.

The optimizer supports all major operating systems (64-bit), including Windows, Linux, and MacOS.
It provides interfaces to [Julia](https://github.com/COPT-Public/COPT.jl), Python, PuLP, Pyomo, Fortran, C, C++, C#, Java, AIMMS, AMPL, GAMS and CVXPY.

If you don't have a valid COPT 7.2 license yet,
please apply for free personal license from [COPT application page](https://www.shanshu.ai/copt).
COPT 7.0 and COPT 7.1 licenses are compatible COPT 7.2.

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
The latest COPT 7.2 patch release is COPT 7.2.3.

Download links for supported platforms are:

**Windows**<br>
  We recommend
  the [Installer](https://pub.shanshu.ai/download/copt/7.2.3/win64/CardinalOptimizer-7.2.3-win64-installer.zip),
  but you can use the [zip package](https://pub.shanshu.ai/download/copt/7.2.3/win64/CardinalOptimizer-7.2.3-win64.zip) too.

**macOS (Universal)**<br>
  We recommend
  the [Installer](https://pub.shanshu.ai/download/copt/7.2.3/osx64/CardinalOptimizer-7.2.3-universal_mac.dmg),
  but you can use the [tar.gz package](https://pub.shanshu.ai/download/copt/7.2.3/osx64/CardinalOptimizer-7.2.3-universal_mac.tar.gz) too.<br>

**Linux**<br>
  Please use the [tar.gz package](https://pub.shanshu.ai/download/copt/7.2.3/linux64/CardinalOptimizer-7.2.3-lnx64.tar.gz)

**Linux (ARM64)**<br>
  Please use the [tar.gz package](https://pub.shanshu.ai/download/copt/7.2.3/aarch64/CardinalOptimizer-7.2.3-aarch64_lnx.tar.gz)

## Release notes

```
COPT 7.2.3
==========
Added a feature in MIP presolver.
Added a floating license support for COPT cluster deployment.

COPT 7.2.2
==========
Fixed an issue regarding MIP cuts performance.
Fixed an issue regarding QCQP without linear constraints.
Fixed an issue regarding using Feas-Relax in Python.
Removed Python API VC++ runtime dependency on Windows.

COPT 7.2.1
==========
Improved MIP presolver.
Fixed an issue in MISOCP presolver.
Fixed an issue regarding MIP solution pool count.
Fixed an issue regarding QCQP folding.
Fixed an issue regarding instruction set.
Fixed an issue in LP example.
Revised COPT C++ API error message.

COPT 7.2.0
==========
Main features of COPT 7.2:
COPT exponential cone solver
COPT MIP solver performance improvements
COPT SOCP and QCQP solvers performance improvements
COPT matrix modeling with Python and C++

Major components introduced in previous releases
Parallelized optimization solvers:
COPT MIP solver
COPT LP first-order solver with GPU-acceleration
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
