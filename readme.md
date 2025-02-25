<h1 align="center">Robust STL Planning Through Interpolating Splines</h1>

[<img src="/images/header.png" width="100%">](https://www.overleaf.com/read/rgdvrxpxgdvm
)
## Abstract

In autonomous systems, robust spatio-temporal planning is essential for navigating complex environments, where precise spatial trajectories and temporal constraints coordination is critical. Signal Temporal Logic (STL) provides a powerful formalism for defining these constraints, with quantitative semantics offering robustness measures vital for safety-critical and disturbance-resilient applications. However, STL-based planning is computationally intensive, posing challenges for real-time applications, particularly in long-horizon missions.

This thesis works towards addressing this limitation by developing a smooth, spline-based STL encoding for an STL fragment that excludes the until operator and supports single-level recursion, including the eventually-always and always-eventually operators, enabling more efficient trajectory planning. The encoding, designed for a Crazyflie 2.1 quadrotor, leverages rest-to-rest and Catmull-Rom splines, decoupling optimization variable count from STL horizon length to enhance computational efficiency in extended missions. Evaluated across benchmarks, the encoding improved performance over previous STL planning methods, with solve times scaling more efficiently with horizon length. For further validation, we applied the encoding in a numerical simulation of a Crazyflie 2.1 performing a complex reach-avoid task, achieving robust trajectory tracking with improved solve times, though still limited for stringent real-time applications.
