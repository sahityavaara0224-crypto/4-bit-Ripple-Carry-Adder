# 4-Bit Ripple Carry Adder

## Project Overview

This project implements a 4-bit Ripple Carry Adder using Full Adder
circuits in Logisim Evolution.

The circuit adds two 4-bit binary numbers and produces a 4-bit sum
along with a final carry output.

## Objectives

- Understand binary addition.
- Design Half Adder and Full Adder circuits.
- Connect four Full Adders to create a 4-bit Ripple Carry Adder.
- Verify the circuit using test cases.

## Tools Used

- Logisim Evolution
- Git
- GitHub

## Circuit Design

The circuit consists of four cascaded Full Adders. The carry output
from each stage becomes the carry input of the next stage.

## Inputs

- A3, A2, A1, A0
- B3, B2, B1, B0

## Outputs

- S3, S2, S1, S0
- Cout

## Test Results

| A | B | Expected Result |
|---|---|---|
| 0101 | 0011 | 01000 |
| 0111 | 0010 | 01001 |
| 1111 | 0001 | 10000 |
| 1010 | 0101 | 01111 |
| 1111 | 1111 | 11110 |

## Applications

- Arithmetic Logic Units
- Digital processors
- Embedded systems
- Digital calculators
- Arithmetic circuits



Sahitya

Third-Year B.Tech – Electronics and Communication Engineering
