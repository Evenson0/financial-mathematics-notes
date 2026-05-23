# Financial Mathematics Notes

**A structured set of financial mathematics notes for SOA Exam FM preparation, with a companion JSON problem bank and an interactive practice tool.**

## Overview

This repository contains my personal study notes for the **SOA Exam FM**. The notes are designed as a growing reference in financial mathematics, with definitions, formulas, examples, exercises, and problem-solving intuition.

The material follows the main structure of the FM syllabus and is supported by a companion problem bank written in JSON. This JSON file contains a collection of **1,000 exercises** using the same format as the interactive practice tool available on my personal website.

The goal of this project is to build a clean, reusable, and well-documented resource for learning financial mathematics, preparing for Exam FM, and developing actuarial problem-solving skills.

## Repository Contents

```text
financial-mathematics-notes/
│
├── README.md
├── notes/
│   └── financial-mathematics-notes.pdf
│
├── data/
│   └── fm_practice_problems.json
```

## PDF Notes

The PDF notes are available directly in this repository:

[Open the Financial Mathematics Notes PDF](notes/financial-mathematics-notes.pdf)

The notes include:

- clear definitions and notation;
- compact formulas and relationships;
- worked examples with structured solutions;
- exercises in SOA Exam FM style;
- problem-solving intuition for financial mathematics.

## Interactive Practice Tool

The exercises are also connected to an interactive practice tool on my website:

<a href="https://evenson0.github.io/tools/soa-fm-practice/" target="_blank" rel="noopener noreferrer">
  Open the FM Practice Tool
</a>

The tool is designed for active preparation. It allows users to work through FM-style exercises, select answers, and review structured solutions.

## JSON Problem Bank

This repository also includes a structured JSON problem bank:

```text
data/fm_practice_problems.json
```

The JSON file contains **1,000 financial mathematics exercises** written in the same format used by the interactive practice tool on my blog.

Each problem follows a structured format similar to:

```json
{
  "id": 1,
  "title": "Example 1.1.1",
  "statement": "Problem statement...",
  "choices": {
    "A": "Choice A",
    "B": "Choice B",
    "C": "Choice C",
    "D": "Choice D",
    "E": "Choice E"
  },
  "correct": "A",
  "solution_steps": [
    "Step 1...",
    "Step 2...",
    "Step 3..."
  ],
  "answer_text": "Final answer...",
  "topic": "Time Value of Money",
  "difficulty": "Basic",
  "tags": ["interest theory", "accumulation", "exam-fm"]
}
```

This format makes the problem bank reusable for websites, practice tools, flashcards, dashboards, or future actuarial education projects.

## Core Topics

### Chapter 1 — Time Value of Money

**Exam weight: 5–15%**

This chapter covers the foundations of financial mathematics: simple and compound interest, accumulation functions, present value, accumulated value, discount factors, nominal and effective rates, force of interest, inflation, real rates, and equations of value.

### Chapter 2 — Annuities and Non-Contingent Cash Flows

**Exam weight: 20–30%**

This chapter studies level annuities, annuities-immediate, annuities-due, perpetuities, and increasing or decreasing cash-flow patterns. It focuses on present value, accumulated value, and the calculation of unknown payment or term quantities.

### Chapter 3 — Loans

**Exam weight: 15–25%**

This chapter focuses on loan structure and amortization. Topics include principal, payment schedules, outstanding balance, interest and principal components of each payment, balloon payments, refinancing, and loan valuation formulas.

### Chapter 4 — Bonds

**Exam weight: 15–25%**

This chapter introduces bond pricing and yield. It includes coupon rates, redemption value, premium and discount amortization, book value, market value, callable bonds, and accumulated value with reinvestment of coupons.

### Chapter 5 — General Cash Flows, Portfolios, and Asset Liability Management

**Exam weight: 20–30%**

This chapter develops the broader theory of financial cash flows. It includes yield rates, spot and forward rates, yield curves, duration, convexity, matching, immunization, and portfolio construction for asset-liability management.

## Project Goals

This project aims to provide:

- a clean reference for financial mathematics;
- structured notes for SOA Exam FM preparation;
- a reusable JSON database of FM-style problems;
- a bridge between written notes and interactive practice;
- a public actuarial education resource that can grow over time.

## Why This Repository Exists

Financial mathematics is best learned through both theory and practice. Reading formulas is not enough; one must solve problems, recognize patterns, and understand how different concepts connect.

This repository combines three layers:

1. **Notes** for theory and reference;
2. **Exercises** for active learning;
3. **Interactive tools** for practice and reinforcement.

Together, these resources form a small open educational project in actuarial science and financial mathematics.

## Website

You can find more actuarial, mathematical, and quantitative finance resources on my website:

[https://evenson0.github.io](https://evenson0.github.io)

## Author

**Evenson Auguste**

Actuarial analyst interested in actuarial science, financial mathematics, quantitative finance, probability, and mathematical education.
