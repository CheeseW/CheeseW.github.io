---
title: Extending Projective Dynamics for Practical and Efficient Simulation
summary: Dissertation
date: 2025-05-11
_build:
  render: always
  list: never
---
This dissertation presents a series of extensions to the Projective Dynamics (PD)
framework for simulating elastic soft bodies. PD is widely used for its speed and
robustness, enabled by a constant system matrix that allows fast direct solves
and parallel local steps. However, this strength also imposes limitations when
simulating more complex behaviors that require changing system matrices.
We investigate how to retain the efficiency and robustness of PD while enabling
support for

1. collision handling
2. nonlinear tissue behavior
3. self actuation simulation
4. differentiable simulation for integration with deep learning frameworks

For collision, we exploit the locality of contact forces and use a Schur Complement-
based decomposition to preserve most of the factorized system. For simulating skin
and tissue, we introduce a strain-limiting material model that fits within the PD
paradigm. For self-actuation, we adopt Shape Targeting and show how it can be
simulated efficiently with only minor changes to the PD local step. For differentiable
simulation, we propose an iterative correction scheme that reuses the PD global
matrix and avoids full Hessian solves in the backward pass.
These techniques are integrated into a high-performance simulator that supports
interactive rates even with hundreds of thousands of tetrahedral elements. We
demonstrate applications including a facial flap surgery simulator with self-contact
and surgical constraints, and a differentiable physics layer embedded in a neural
network for learning muscle actuation. Together, these results extend the range of
physical behaviors that can be simulated within the PD framework, while preserving
its original advantages.