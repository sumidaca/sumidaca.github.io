---
layout: project
type: project
image: images/Sudoku1.png
title: Hexadecimal Sudoku Solver
permalink: projects/hexadecimal-sudoku-solver
# All dates must be YYYY-MM-DD format!
date: 2020-03-27
labels:
  - Java
summary: A program designed to solve a hexadecimal sudoku puzzle developed for ICS211.
---

<img class="ui medium right floated rounded image" src="../images/Sudoku1.png">
<img class="ui medium right floated rounded image" src="../images/Sudoku2.png">

## What is Sudoku?

Sudoku is a puzzle where you're given a grid of squares and need to fill out all the squares with numbers so that no row, column, or big box has the same number twice. A traditional sudoku is 9x9 with 9 3x3 boxes, but this project uses a 16x16 square with 16 4x4 boxes instead. To simplify the output of the program, the count starts at 0 and 10-15 have been replaced with A-F. 

## What Does This Program Do?

The hexadecimal sudoku solver is a program that was designed to solve a hexadecimal sudoku puzzle using recursive functions. The purpose of the project was to develop skills with recursion. The way the program solves the puzzle is through backtracking. The program iterates through every cell until it finds an empty one. Then it goes through the list of values until it finds a value that counts as a legal value. Then it inputs that value in that cell and moves on to the next empty spot. If a cell is found to have no legal values, the program reverts back to the previous cell filled out and chooses another legal value. The program will eventually complete when all cells are filled out. 

## What Did I Do and What Did I Learn?
Most of the code was provided by the teacher. The sections of the code I was responsible for was the solveSudoku method and the legalValues method. I also added a remove method to assist with the backtracking, and I added three tests to the test program to check a few cases not addressed by the original version of the test. The project allowed me to improve on my Java skills, as well as improve my understanding of recursion. It also gave me a chance to think about how I test programs, requiring me to think of test cases that weren't included with the code.

[Here is a link to a GitHub Repository containing the source code for this project, including the code and the test program.](https://github.com/sumidaca/Sudoku-Solver)
