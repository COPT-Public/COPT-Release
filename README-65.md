# COPT 6.5

COPT (Cardinal Optimizer) is a mathematical optimization solver for large-scale optimization problems.
It includes high-performance solvers for LP, MIP, SDP, (MI)SOCP, convex (MI)QP and convex (MI)QCP.

The optimizer supports all major operating systems (64-bit), including Windows, Linux, and MacOS.
It provides interfaces to [Julia](https://github.com/COPT-Public/COPT.jl), Python, PuLP, Pyomo, Fortran, C, C++, C#, Java, AIMMS, AMPL, GAMS and CVXPY.

If you don't have a valid COPT 6.5 license yet,
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

The latest COPT 6.5 patch release is COPT 6.5.12.
You can use it with any valid COPT 6.5 license.

Download links for supported platforms are:

**Windows**<br>
  We recommend
  the [Installer](https://pub.shanshu.ai/download/copt/6.5.12/win64/CardinalOptimizer-6.5.12-win64-installer.zip),
  but you can use the [zip package](https://pub.shanshu.ai/download/copt/6.5.12/win64/CardinalOptimizer-6.5.12-win64.zip) too.

**MacOS**<br>
  We recommend
  the [Installer](https://pub.shanshu.ai/download/copt/6.5.12/osx64/CardinalOptimizer-6.5.12-universal_mac.dmg),
  but you can use the [tar.gz package](https://pub.shanshu.ai/download/copt/6.5.12/osx64/CardinalOptimizer-6.5.12-universal_mac.tar.gz) too.

  **Please note that we replaced x86_64 and arm64 packages by the universal package for macOS as of 6.5.12.**

**Linux**<br>
  Please use the [tar.gz package](https://pub.shanshu.ai/download/copt/6.5.12/linux64/CardinalOptimizer-6.5.12-lnx64.tar.gz)

**Linux (ARM64)**<br>
  Please use the [tar.gz package](https://pub.shanshu.ai/download/copt/6.5.12/aarch64/CardinalOptimizer-6.5.12-aarch64_lnx.tar.gz)

## Release notes

```
COPT 6.5.12
===========
Replaced x86_64 and arm64 packages by a universal package for macOS.
Updated documentations accordingly.
Fixed a compatible issue in LP reader.
Fixed other issues and bugs.

COPT 6.5.11
===========
Fixed an issue regarding web-license SSL certificate.

COPT 6.5.10
===========
Added web-license support for cloud and container deployment.
- Please visit copt.shanshu.ai/license for web-license application and trial.
Added support for LoongArch64 architecture.
Reintroduced support for Python 3.6.
Fixed an issue regarding long term license on Windows.
Fixed other issues and bugs.

COPT 6.5.9
==========
Enabled callback for MISOCP and MIQCP.
Fixed a memory issue in MISOCP solver.

COPT 6.5.8
==========
Added preview of web-license support for cloud and container deployment.
Fixed a potential issue in SOCP solver.
Fixed an issue in CBF writer.
Fixed an issue in callback functionality.

COPT 6.5.7
==========
Fixed an issue in MIQP solver.
Fixed a performance issue in MIP presolver.

COPT 6.5.6
==========
Fixed an issue in MIP presolver.
Fixed an issue in Python matrix modeling.
Fixed an issue in Python API regarding FeasRelax.
Fixed issues in cone solvers.
Fixed a potential memory issue.

COPT 6.5.5
==========
Fixed an issue regarding model fingerprint, and the output may be different from previous releases.
Fixed an issue regarding python modeling.
Fixed an issue regarding LP file error handling.

COPT 6.5.4
==========
Improved performance of the Primal-Dual SDP solver.
Added direct Linear Matrix Inequalities (LMI) support for SDP.
Added dualization support for conic problem.
Fixed an issue regarding having empty constraint matrix.
Fixed performance and numerical issues in MIP presolver.
Fixed an LP post-solve issue.
Fixed other issues and bugs.
Revised documentations and examples.

COPT 6.5.3
==========
Fixed an issue regarding QP presolver.
Fixed a minor issue in MIP solver.

COPT 6.5.2
==========
Fixed an issue regarding lazy constraints.
Fixed an issue regarding SOC dual.
Fixed an issue in python interface.
Fixed a non-deterministic behavior.
Fixed other bugs and issues.
Unified Python examples programming styles.
Revised Chinese and English documentations.

COPT 6.5.1
==========
Added general constraints support in COPT Python API, including:
  MAX, MIN, ABS, AND, OR and PWL.
Added callback examples.
Fixed memory issues in C# and Java interfaces.
Fixed bugs in MIP presolver.
Fixed other bugs and issues.
Revised Chinese and English documentations.

COPT 6.5.0
==========
Major components introduced in COPT 6.5
COPT callback functionality for lazy constraints and user cuts
Enhanced indicator and SOS support

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

Supported platforms and OS:
Windows: x86
Linux  : x86 and arm64
MacOSX : x86 and arm64
```
