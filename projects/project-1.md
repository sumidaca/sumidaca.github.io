---
layout: project
type: project
image: images/micromouse.jpg
title: Bank Record Database
permalink: projects/bankrecorddatabase
# All dates must be YYYY-MM-DD format!
date: 2020-12-03
labels:
  - C
  - C++
summary: A program to modify a bank record database developed for ICS 212.
---


The bank record database is a program that allows a user to modify a database of people's information. The program includes a user interface that prompts the the user to choose a option from a list. The options the user can choose are to add a record, remove a record, find a record, print all the records, and quit the program. The user picks an option by typing their choice into the command line. The program is designed so that only the options available can be chosen. For example, typing "bank" or "123" will prompt the user to choose a valid option, and takes them back to the menu. This is also true for any prompt that requires a number, rejecting any inputs starting with a string and asking the user again. The program is also able to take a shorted version of the choices as valid inputs, which means that typing "a" will be the same as typing "add". The information that is stored in the database include an account number, a name, and an address. The program saves the database to a file after the user selects the quit options, and loads the file if it's in the same directory when the program starts.

This project was programmed entirely by me, and was originally programmed in C and converted to C++ at a later date. This allowed me to experience the difference between the two programs by letting me learn which functions were in both languages and which functions needed to be changed during the transition to C++, like the different ways to catch invalid user inputs. The project also allowed me to practice C and C++ skills I learned prior to the project, such as making a user interface on the command line and reading/writing files. The project involved a makefile for both versions, letting me practice compiler commands. There were two makefiles for each version; a normal version and a debug version. The debug version lists the functions in the output as they are used, as well as any input variables used in those functions. This taught me how to run two versions of a single program.
