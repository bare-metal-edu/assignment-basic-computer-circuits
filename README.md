![Vector art of 200 in hex, subtitle of course: Bare Metal in pale green and printer's black](https://raw.githubusercontent.com/allegheny-college-cmpsc-200-fall-2024/course-materials/media/images/CMPSC%20-%200xC8%20Banner.png)

# Basic Circuits of a Computer

| Date              |           |
|:------------------|:----------|
| 3 October 2025   | Assigned  |
| 10 October 2025  | Due       |
| Fundamental            | [![Assignment Progress](../../actions/workflows/main.yml/badge.svg?branch=main)](../../actions/workflows/main.yml) |
| Hack                   | [![Assignment Progress](../../actions/workflows/hack.yml/badge.svg?branch=hack)](../../actions/workflows/hack.yml) |

## Introduction

As we extend our understanding of circuits, we see that we can build _real things_ that have _real functions_. This
assignment asks you to build a digital padlock which can:

* store a three-bit combination
* allow a programmer to "hide" this three-bit combination to secure the circuit
* evaluate input of a three-bit combination
* notify the user that entered combination matches the programmed combination, when true
  * if and only if true, an "unlock" light should latch high

* `1` 74LS86 (`XOR`)
* `2` 74HC02 (`NOR`)
* `2` 74HC04 (`NOT`)
* `3` 74HC08 (`AND`)
* `2` 4-input DIP switches
* `2` 830-pin breadboards
* `1` LED (for final circuit)
  * To test the circuit,you're allowed `5` total LEDs
* as many transistors as desired

Finishing this circuit will require the correct application of circuits we've learned this week
as well as incorporating logic similar to the `Equality Comparator` (an earlier `Hack`).

## Instructions

You must complete and demonstrate this circuit to  an instructor or TL using your breadboard and associated parts. This 
can be done any time during the duration of the assignment until the due date. 

In addition, you must record your findings in the `report.md` file in the `docs/` directory. This documentation will require you to fill
in some truth tables, provide some breadboard layouts, and explain how each of the circuits work, ostensibly. The report also contains
a table for the instructor or TL to fill out when circuits are demonstrated. Again, this table _must be filled out by the instructor
or a course TL_. (This means that you'll have to have `commit`s authored by one of these folks!)

## Assignment "Hack"

> Note: to complete this hack:
> * you will need to request permission to use up to two (2) additional chipsl
>   * request these of the instructor or a TL and document them in the `Hack`'s `report.md`. 
> * `Hack`ers are also permitted an additional switch in order to incorporate the `Enable` function of the involved circuit(s).

How much work does it take to turn this into a `4` bit combination lock? Do this hack, and you'll find out.
