# SolveWithExcel – Challenge #5
## Conditional Formatting for Risk Monitoring

This challenge focuses on turning logical risk rules into visual signals using Excel’s Conditional Formatting. You will highlight high-risk orders automatically and add visual alerts to summaries so risks are visible at a glance.

This is a core technique used in operational monitoring, audit reviews, and management dashboards.

# Difficulty

Early Intermediate
Estimated Time
15–25 minutes

# The Problem

You already know which orders are high risk based on business rules.
Now the challenge is to make those risks instantly noticeable—without reading numbers.

Your task is to:

Visually highlight high-risk orders
Add stronger alerts for very high-risk cases
Signal risk presence in a summary section

All visuals must update dynamically as data changes.

# Dataset

This challenge uses the Orders dataset from Challenge #4, including:

Order ID
Customer
Order Date
Quantity
Unit Price
Order Value
Risk Flag

Order Value and Risk Flag are already calculated using formulas.

# Your Tasks
## 1. Highlight High-Risk Orders

Apply Conditional Formatting so that:

Entire rows are highlighted when Risk Flag = "High Risk"

Use a clear but professional color (e.g., light red).

## 2. (Optional) Add a Very High-Risk Level

Add an additional rule to visually distinguish:

Very High Risk when Order Value ≥ 15000

This rule should override or stand out from the standard High-Risk formatting.

## 3. Visual Alert in the Summary

Enhance the Summary section so that:

The High-Risk Orders count changes color when the value is greater than 0

This acts as an immediate signal for decision-makers.

# Requirements

Use Excel Conditional Formatting only

Do not apply manual cell coloring

Formatting must update automatically

Keep visuals readable and consistent

# Learning Objectives

By completing this challenge, you will learn how to:

Translate business logic into visual alerts
Use formula-based Conditional Formatting
Build scan-friendly Excel sheets
Improve usability of operational spreadsheets

# Files Included

solvewithexcel_challenge_5_solution_hidden.xlsx
→ Conditional Formatting not applied (learner builds the rules)

solvewithexcel_challenge_5_solution_revealed.xlsx
→ All Conditional Formatting rules applied

# Next Challenge

In the next challenge, you will:

Combine logic, visuals, and layout
Move toward dashboard-style monitoring
Introduce KPI-level indicators

# About SolveWithExcel

SolveWithExcel focuses on solving real business problems using Microsoft Excel through structured, challenge-based learning.

Visit https://solvewithexcel.org
 to learn more.
