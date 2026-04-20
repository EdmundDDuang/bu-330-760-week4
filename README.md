# BU-330-760 Week 4 – Math Agent

## Overview

This project implements a math agent that solves questions using tools in a ReAct-style loop.

The agent reads a list of questions from a markdown file and uses different tools to generate step-by-step solutions.

## Features

- Uses a **calculator tool** for arithmetic operations
- Implements a **product lookup tool** to retrieve product prices from a JSON file
- Handles both math problems and product-related questions
- Provides step-by-step reasoning for each answer

## Tools Implemented

### Calculator Tool
Evaluates mathematical expressions such as:
- Multiplication
- Exponents
- Percentages

### Product Lookup Tool
- Reads data from `products.json`
- Returns the price of a given product
- Lists available products if the requested one is not found

## Example Questions

The agent can solve:
- Basic arithmetic (e.g., 847 × 293)
- Financial calculations (compound interest)
- Logical problems (bat and ball problem)
- Product comparisons (best deal between items)

## How to Run

```bash
uv run agent.py