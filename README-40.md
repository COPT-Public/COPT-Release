# COPT 4.0

COPT (Cardinal Optimizer) is a mathematical optimization solver for large-scale optimization problems.
It includes high-performance solvers for LP, MIP, SOCP, convex QP and convex QCP.

The optimizer supports all major operating systems (64-bit), including Windows, Linux, and MacOS.
It provides interfaces to [Julia](https://github.com/COPT-Public/COPT.jl), Python, PuLP, Pyomo, Fortran, C, C++, C#, Java, AMPL, GAMS and CVXPY.

If you don't have a valid COPT 4.0 license yet,
please apply for free personal license from [COPT application page](https://www.shanshu.ai/copt).

Full COPT documentation is available [here](https://guide.coap.online/copt/en-doc/index.html).

## Download links

The latest COPT 4.0 patch release is COPT 4.0.7.
You can use it with any valid COPT 4.0 license.

Download links for supported platforms are:

**Windows**<br>
  We recommend
  the [Installer](https://pub.shanshu.ai/download/copt/4.0.7/win64/CardinalOptimizer-4.0.7-win64-installer.zip),
  but you can use the [zip package](https://pub.shanshu.ai/download/copt/4.0.7/win64/CardinalOptimizer-4.0.7-win64.zip) too.

**MacOS (Intel)**<br>
  We recommend
  the [Installer](https://pub.shanshu.ai/download/copt/4.0.7/osx64/CardinalOptimizer-4.0.7-osx64.dmg),
  but you can use the [tar.gz package](https://pub.shanshu.ai/download/copt/4.0.7/osx64/CardinalOptimizer-4.0.7-osx64.tar.gz) too.

**MacOS (Apple M1)**<br>
  We recommend
  the [Installer](https://pub.shanshu.ai/download/copt/4.0.7/aarch64/CardinalOptimizer-4.0.7-aarch64_mac.dmg),
  but you can use the [tar.gz package](https://pub.shanshu.ai/download/copt/4.0.7/aarch64/CardinalOptimizer-4.0.7-aarch64_mac.tar.gz) too.

**Linux**<br>
  Please use the [tar.gz package](https://pub.shanshu.ai/download/copt/4.0.7/linux64/CardinalOptimizer-4.0.7-lnx64.tar.gz)

**Linux (ARM64)**<br>
  Please use the [tar.gz package](https://pub.shanshu.ai/download/copt/4.0.7/aarch64/CardinalOptimizer-4.0.7-aarch64_lnx.tar.gz)

## Release notes

```
COPT 4.0.7
==========
Added COPT Julia interface: https://github.com/COPT-Public/COPT.jl
Fixed issues identified during COPT Julia interface development
Fixed an issue regarding Chinese path name on Windows

COPT 4.0.6
==========
Added Fortran API support
Fixed a MIP performance issue
Fixed an issue regarding MIP clique handling
Fixed an issue regarding compute cluster
Fixed an issue regarding conic solver logging
Revised documentation for COPT installation and setup

COPT 4.0.5
==========
When no license file is found, COPT will start with size limitations for non-commercial use
   - for LP problems, the size is limited to 10000 variables and 10000 constraints
   - for other problems, the size is limited to 2000 variables and 2000 constraints
Introduced new API return code COPT_RETCODE_NONCONVEX for non-convex problem
Introduced new public parameter BarOrder, setting which to 0 selects the AMD ordering
Fixed an issue regarding MIP presolver
Fixed a rare performance issue in barrier solver
Fixed a redundant license warning message for floating client

COPT 4.0.4
==========
Improved handling of indicators when NumericFocus is enabled
Fixed an issue regarding appending tuplelist using Python API
Fixed an issue regarding MIP bounds tightening
Fixed a performance issue of QCP solver
Fixed a performance issue of LP presolver
Fixed a rare issue regarding unbounded LP problems
Reduced memory usage in LP presolver
Updated setup.py for MacOS
Fixed issues regarding Java and C# documentations

COPT 4.0.3
==========
Fixed an issue regarding OEM licensing

COPT 4.0.2
==========
Fixed issues regarding QP, QCP and SOCP solvers
Fixed interface issues
Revised documentations

COPT 4.0.1
==========
Improved LP presolver
Increased MPS output precision
Fixed a rare numerical issue in barrier solver
Fixed QP and QCP API issues
Revised COPT documentations
Removed GAMS/COPT link as COPT is now officially supported by GAMS
Added <home>/copt to COPT license file checking path
Added more examples

COPT 4.0.0
==========
Major components introduced in COPT 4.0
COPT IIS solver for infeasible LP and MIP problems
COPT convex QP solver
COPT convex QCP solver

Major components introduced in previous releases
Parallelized optimization solvers:
COPT MIP solver
COPT LP barrier solver
COPT LP simplex solver
COPT SOCP solver

Modeling interfaces:
Object-oriented: Python, C++, C#, Java
Third-party    : AMPL, GAMS, PuLP, Pyomo, CVXPY
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
