# Profiling

## Exercises

<section class="exercise" markdown="1">

### Dataframe Storage

Compare the performance of list-of-dicts vs. dict-of-lists representation of dataframes
for filtering and aggregation.
Which representation is better,
and how does the answer depend on exactly what question you ask?

</section>

<section class="exercise" markdown="1">

### Instrumentation

Write a program in Python that:

1.  parses a single-file program containing function definitions
    (but not classes with methods);

1.  replaces each function with a version of itself
    that records the start and end time of each invocation;
    and

1.  saves the execution times for each function to a file
    when the program terminates.

</section>
