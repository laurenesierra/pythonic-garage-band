# Modules and testing
codefellows 401, lab 4

## Author
Lauren Sierra

 ## Credits and Collaborations
Glenn Clark

## Project Overview

This is a garage band made using Object Oriented Programming

## Band Tests

A Band instance should have a name attribute which is a string.
A Band instance should have a members attribute which is a list of instances that inherit from Musician base (or super) class.
A Band instance should have a play_solos method that asks each member musician to play a solo, in the order they were added to band.
A Band instance should have appropriate __str__ and __repr__ methods.
A Band should have a class method to_list which returns a list of previously created Band instances

## Musician Subclass Tests

Each kind of Musician instance should have appropriate __str__ and __repr__ methods.
Each kind of Musician instance should have a get_instrument method that returns string.
Each kind of Musician instance should have a play_solo method that returns string.