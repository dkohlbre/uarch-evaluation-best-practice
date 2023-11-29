# Goals

This is intended to be a community-run set of guidelines for:
 - Evaluation of microarchitectural attacks
 - Evaluation of microarchitectural defenses
 - Guidelines for ensuring reproducability of the above

Our process is inspired by the excellent [SIGPLAN](https://raw.githubusercontent.com/SIGPLAN/empirical-evaluation/master/checklist/checklist.pdf) guidelines, which we intend to extend with microarchitecture-specific guidelines.

If you are a paper author or reviewer, this can be treated as a
starting point for a rubric. Depending on the mechanism, more details
may be required (e.g. the specific configuration of DIMMs or the GPU
model and driver version.)

Please submit PRs to improve guidelines!

# General guidelines

_These guidelines are meant to **support** judgement, not **supplant** it._

All works should report the following:

## Platform reporting

 - CPU SKU (Exact model)
 - CPU microcode version
 - Amount and speed of DRAM
 - Operating system, and exact version/patch

### Example
 - Intel Xeon Gold 6312U CPU
 - microcode v0xd000375
 - 512GB of DDR4 (3200MHz)
 - Ubuntu Linux 22.04.3, kernel 5.15.0-86-generic

## Setup reporting
 - Scheduling configuration, including any core pinning

### Example

# Attack evaluation guidelines

# Defense evaluation guidelines

# Reproducability
