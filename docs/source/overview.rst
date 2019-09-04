Overview
========

Why Write This?
---------------

Static Timing is a task that can be very difficult to perform correctly.
The tools themselves will let you write any constraint.
However, they can not tell you if your constraints are correct.

I have seen many instances of incorrect timing constraints.
Sometimes they are benign.
Other times there are part failures at temperature extremes.

This document is an attempt to provide the practical working knowledge of static timing.
I intend to provide a thorough examination of a timing example.
This will include:

* Deriving the equations
* Writing the timing constraints
* Validating the timing constraints

It is also my goal to provide TCL constraints which can be freely used to perform aspects of STA.
