# Systematic Program Design - Final Problems
Release 0.6.0

A collection of final projects while studying Systematic Program Design, the most interesting bits anyway.

The programs are currently written in BSL using Dr.Racket, since those are the language and the tool used to teach Systematic Program Design at the University of British Columbia, along with the corresponding UBCx course.

The entire SPD path has been recently restructured into a new set of 6 parts.

[Software Development](https://www.edx.org/micromasters/software-development)

## Index
- 01. Lander
- 02. Bubbles
- 03. Naturals
- 04. Helpers
- 05. Trees
- 06. Mutual Reference
- 07. Crossed Data - Two One-of Types
- 08. Locals

## 01. Lander
Assignment involving Compound data.

Lander is a very basic interactive video game where the player has to land a block on the bottom side of a canvas against gravity.

## 02. Bubbles
Assignment involving Reference and Self Reference.

Bubbles of various sizes and colors pop up and fade away at the pressure of the "space bar".

## 03. Naturals
An interesting experiment redefining a custom set of Natural numbers (more precisely an equivalent representation) and relative methods to work with it.

## 04. Helpers
A small set of methods to support a various set of functions operating on lists.
- Blobs
- Pyramid & pyramid-random
- Sorting

## 05. Trees
Working with Binary Search Trees. A proper BST data definition following the SPD method, and a set of functions to work with Binary Search Trees like "insert", "lookup", and "balance-factor".

## 06. Mutual Reference
Working with data with self and mutual reference.

## 07. Crossed Data - Two One-of Types
Functions operating on crossed data, and relative templates. The key here is to first visualize how the problem can be solved, and to identify areas that can be grouped or simplified.

## 08. Locals
Lexical scope and encapsulation allow for a cleaner code, packing helpers within the function that depends from them, avoiding at the same time to pollute the global scope. Locals may also improve performances reducing the computation load.
