# BU-330-760 Week 4 – Math Agent

## Overview

This project implements a math agent that solves different types of questions using tools in a ReAct-style loop.

The agent reads questions from a markdown file and answers them step by step by selecting the appropriate tool.

## Features

- Solves math and logic problems automatically
- Uses tools dynamically based on the question
- Provides step-by-step reasoning
- Handles both arithmetic and product-related questions

## Tools Implemented

### Calculator Tool

- Evaluates mathematical expressions
- Supports multiplication, exponents, and percentages

### Product Lookup Tool

- Reads product data from `products.json`
- Returns the price of a requested product
- Lists available products if the product is not found

## Example Questions

The agent can solve:

- Basic arithmetic (e.g., 847 × 293)
- Financial calculations (compound interest)
- Logic problems (bat and ball problem)
- Product comparisons (finding the best deal)

## Project Structure

```text
.
├── agent.py
├── calculator.py
├── products.json
├── math_questions.md
└── README.md
```

## How to Run

Run the following command in the terminal:

uv run agent.py

## Video Walkthrough

This video demonstrates the agent running in the terminal and solving all questions, including product-based queries using the product lookup tool:

https://youtu.be/ruojyXNXmjw