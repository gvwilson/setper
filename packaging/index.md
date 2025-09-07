# Packaging

## Exercises

<section class="exercise" markdown="1">

### Build a Dependency Tree

1.  Write a program that parses Python source files,
    detects `import` statements,
    and builds a list of imported packages.

2.  Describe two situations in which
    your program will fail to detect dependencies.

</section>

<section class="exercise" markdown="1">

### Resolve Dependencies

Use [Z3][z3-solver] to build a tool that reads a YAML file of inter-package dependencies
and produces (a) a single solution and (b) all possible solutions.
(See [this chapter][sdxpy-pack] for details.)

</section>

