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
- An example where we find a bug
  - `iterator_has_next`
  - draw and explain monitor FSM
  - might be worth writing out the trace (alluding to trace slicing without actually defining it)
- Usefulness of RV (ASE '16)
  - Adding RV to the testing process!
- Open challenges and techniques (ASE '16)
  - Scaling
    - eMOP
    - Kevin's work
  - Specification writing + quality
    - Will hopefully have a followup blog post about DSI!
- More resources
  - Cornell SE
  - [CS6156](https://www.cs.cornell.edu/courses/cs6156/2020fa/)
  - RV textbook?
  - RV conference
    - Other cool work: RV theory (hyperproperties), Cyberphysical systems
