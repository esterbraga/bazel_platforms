# Build ATHENA Bazel Platforms

This repository provides a central place for defining Bazel constraints, constraint_values, and platforms.
It ensures compatibility across different modules in the B-ATHENA organization and guarantees reproducibility.

By using a single source for base definitions, extending Bazel platforms becomes transparent, consistent, and reusable across modules.

## Repository Structure

- main branch

  - Empty by design.
  - Used by trainees in their own forks to implement solutions.

- solution branch
  - Contains all official Bazel recipes and definitions.
  - Serves as the reference for code releases.

## Training Instructions

1. Fork this repository to your own GitHub account.
2. Work on your solution in the main branch of your fork.
3. Do not push your solution to the original repository.
4. Refer to the solution branch only when you need to check the official reference implementation.

## Purpose

This setup allows trainees to practice with Bazel platforms while keeping the official solutions separate and reproducible.
