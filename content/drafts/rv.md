+++
title = "What is Runtime Verification?"
date = 2025-01-19
description = "A little primer on one of my old research topics"
[extra]
featured = true
short_title = "RV"
+++

Outline:
- Disclaimers: will mostly describe RV a la JavaMOP bc that's what I'm familiar with
- More resources
  - Cornell SE
  - [CS6156](https://www.cs.cornell.edu/courses/cs6156/2020fa/)
  - RV textbook?
  - RV conference
    - Other cool work: RV theory (hyperproperties), Cyberphysical systems

You wouldn't verify a runtime. lol

![meme](../../img/rv/meme.jpeg)

## What is Runtime Verification?

- Intro: Defining Runtime Verification (also called Runtime Monitoring)
  - While the program is running, check whether specifications are met.
  - Reason why it's called "verification" is bc theoretically you can recover after failure. So your programs will "always be correct".
    - Realistically (or often in JavaMOP), you raise an alarm when specs are violated so that the programmer can fix bugs later.
  - Draw funky RV + DUT box picture
  - Why is RV cool?
    - Formal verification vs testing
      - Formal verification: correctness guarantees via proving, but difficult to adopt in practice
      - Testing: no guarantees since we can only check outputs, but easy to adopt in practice
      - RV: the specific program execution we check is correct


### Why Runtime Verification?

![Comparing Formal Verification, Runtime Verification, and Testing](../../img/rv/fv-rv-testing.jpg)

*I think I need to write some stuff about what it means to establish correctness. Formal guarantee means across ALL executions of the program, the program does what it is supposed to do*

Runtime Verification sits in a sweet spot where it can offer _some_ formal guarantees, while also having the flexibility to apply to more number of, and bigger programs. Two other prevalent ways to assess correctness of a program are **Formal Verification** and **Testing**. On one hand, formally verifying your code involves constructing a mathematical proof of the correctness of your program. This is the closest to being absolutely sure that your program is correct, but it also involves an expensive process and building background in theorem proving tools. On the other hand, we can test our program by feeding inputs and comparing outputs with expected ones. Testing is relatively less difficult than formally verifying, since we only have to consider the inputs and outputs. We also have testing frameworks and automatic test generators that can help us run and write tests for many programs. But testing never _proves_ correctness (without giving infinite inputs and outputs, which we cannot do), and we only see the end points of our program. Due to its ease, testing is the de-facto standard way of quality assurance/correctness checking, but what if we still wanted more _formal_ guarantees about our code?

In Runtime Verification, you provide a set of specifications. The specifications reason about the internals of your program, not just the input and output. Since it's a dynamic analysis, it will only apply to one execution at a time and hence not give you the full guarantees that formal verification does. But, you get more guarantees about the correctness of your program than simply testing does.<!-- Since RV simply needs executions, why not use the inputs used by your unit tests?-->

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

<!--
- Open challenges and techniques (ASE '16)
  - Scaling
    - eMOP
    - Kevin's work
  - Specification writing + quality
    - Will hopefully have a followup blog post about DSI!
-->

For more information, check out [_How Good Are the Specs? A Study of the Bug-Finding Effectiveness of Existing Java API Specifications_](https://www.cs.cornell.edu/~legunsen/pubs/LegunsenETAL16SpecEval.pdf) (Legunsen et al., ASE 2016).