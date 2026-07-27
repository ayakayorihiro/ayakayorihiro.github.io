+++
title = "RV part 2 or 3 or whatever"
date = 2025-01-19
description = "A little primer on one of my old research topics"
[extra]
featured = true
short_title = "RV-next"
+++

## An example

- An example where we find a bug
  - `iterator_has_next`
  - draw and explain monitor FSM
  - might be worth writing out the trace (alluding to trace slicing without actually defining it)

### A specification

## Runtime Verification in Practice

### Usefulness of RV
- Usefulness of RV (ASE '16)
  - Adding RV to the testing process!


### Open challenges and techniques

**Specifications**: As with many specification-reliant tools, RV quality depends on the specifications that are used. A large question then is, *who writes and validates these specifications?* Writing specifications

**Speeding up RV**:

One dimension we can consider improving performance is reducing the amount of testing + RV needed based on code updates. Software Development cycles often employ Continuous Integration (CI), where tests are executed after every commit to a repository. We implemented [eMOP](https://github.com/SoftEngResearch/emop) in Java, which you can read about it more in our [paper](/files/publications/emop.pdf).

<!--
- Open challenges and techniques (ASE '16)
  - Scaling
    - eMOP
    - Kevin's work
  - Specification writing + quality
    - Will hopefully have a followup blog post about DSI!
-->

For more information, check out [_How Good Are the Specs? A Study of the Bug-Finding Effectiveness of Existing Java API Specifications_](https://www.cs.cornell.edu/~legunsen/pubs/LegunsenETAL16SpecEval.pdf) (Legunsen et al., ASE 2016).

## More Resources
- More resources
  - Cornell SE
  - [CS6156](https://www.cs.cornell.edu/courses/cs6156/2020fa/)
  - RV textbook?
  - Wikipedia is surprisingly verbose
  - RV conference
    - Other cool work: RV theory (hyperproperties), Cyberphysical systems
