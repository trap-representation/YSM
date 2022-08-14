### STVM ###
![STVM logo](./stvm-logo-github-light.png#gh-light-mode-only)
![STVM logo](./stvm-logo-github-dark.png#gh-dark-mode-only)

----

This is STVM - a stack-based virtual machine, which aims to be fast and lightweight.

STVM is meant to be small.

- STVM leaves off a lot of details for implementations to define, resulting in implementations to be more optimized for certain environments.
- STVM has a very small *base instruction set*, which may be extended to support more instructions.

#### STVM naming convention: ####
\<implementation-name\>\<implementation-type\>n\<number-of-implementation-defined-instructions\>

*implementation-type* can be **one of**:

- `S`: Optimized for modern, high-end devices,
- `E`: Optimized for embedded devices,
- `P`: Optimized to be fast*,
- `R`: Optimized to minimize consumption of resources*.

*These implementations may not support certain instructions from the *basic instruction set*.


STVM has a (WIP) specification that you'll be able to find here in about 3-4 months.

You'll also be able to find the source of the implementation of STVM I've been working on here soon.
