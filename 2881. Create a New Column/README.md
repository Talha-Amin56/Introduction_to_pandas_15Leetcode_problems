# Employee Bonus Calculation

This project involves calculating a bonus for employees by doubling their salary. The given DataFrame contains information about employees, including their `name` and `salary`.

## Table Structure

The `employees` table has the following structure:

| Column Name | Type   |
|-------------|--------|
| name        | object |
| salary      | int    |

## Problem Statement

You are asked to create a new column `bonus` that contains the doubled values of the `salary` column for each employee.

## Example

### Input

| name    | salary |
|---------|--------|
| Piper   | 4548   |
| Grace   | 28150  |
| Georgia | 1103   |
| Willow  | 6593   |
| Finn    | 74576  |
| Thomas  | 24433  |

### Output

| name    | salary | bonus  |
|---------|--------|--------|
| Piper   | 4548   | 9096   |
| Grace   | 28150  | 56300  |
| Georgia | 1103   | 2206   |
| Willow  | 6593   | 13186  |
| Finn    | 74576  | 149152 |
| Thomas  | 24433  | 48866  |

### Explanation

A new column `bonus` is created by doubling the value in the `salary` column for each employee.
