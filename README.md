# K-MAP Analyzer

A web-based Digital Logic Design tool for simplifying Boolean functions using Karnaugh Maps.

## About

K-MAP Analyzer is an interactive Boolean logic simplification system designed for Digital Logic Design (DLD).

The application allows users to enter minterms/maxterms and don't-care conditions and automatically generates:

- Karnaugh Map
- Truth Table
- Simplified Boolean Expression
- Gate-Level Logic Circuit

The system supports Boolean functions with **1 to 5 variables**.

## Features

- Support for 1–5 Boolean variables
- SOP simplification
- POS simplification
- Minterm and maxterm input
- Don't-care conditions
- Automatic Karnaugh Map generation
- Automatic Truth Table generation
- Boolean expression simplification
- Gate-level circuit generation
- Separate SOP/POS circuit representation
- SVG circuit download
- Report download
- Example input generation
- Light and dark themes
- Full-screen mode
- Copy simplified expression
- Responsive user interface

## How It Works

1. Select the number of variables.
2. Enter the variable names.
3. Select SOP or POS.
4. Enter the minterms/maxterms.
5. Enter don't-care terms if required.
6. Click **Generate**.
7. The application generates the Karnaugh Map, Truth Table, simplified expression, and corresponding gate-level circuit.

## Example

For a function such as:

```text
F(A,B,C) = Σm(1,3,5,7)
