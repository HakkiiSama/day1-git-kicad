# Day 1 Git + KiCad

KiCad and Git practice project.

## Tools

- KiCad
- Git
- GitHub

## Project Purpose

This project was created to practice PCB design with KiCad and version control with Git and GitHub.

The hardware is a simple regulated power supply that converts an approximately 12 V input to a 5 V output using an L78L05 linear voltage regulator.

## Circuit Description

The circuit contains:

- A 12 V input connector
- A 1N4007 diode for input protection
- An L78L05 linear voltage regulator
- Input and output filtering capacitors
- An LED with a 620 ohm resistor for output indication
- A 5 V test point
- A 5 V output connector

The main power path is:

12 V input → protection diode → voltage regulator → regulated 5 V output