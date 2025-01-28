# Student DataFrame Query

This project involves querying a DataFrame to select the name and age of a student with a specific `student_id`. The given DataFrame contains information about various students, including their `student_id`, `name`, and `age`.

## Table Structure

The `students` table has the following structure:

| Column Name | Type   |
|-------------|--------|
| student_id  | int    |
| name        | object |
| age         | int    |

## Problem Statement

You are asked to write a query to select the `name` and `age` of the student with `student_id = 101`.

## Example

### Input

| student_id | name    | age |
|------------|---------|-----|
| 101        | Ulysses | 13  |
| 53         | William | 10  |
| 128        | Henry   | 6   |
| 3          | Henry   | 11  |

### Output

| name    | age |
|---------|-----|
| Ulysses | 13  |

### Explanation

The student with `student_id = 101` is Ulysses, who is 13 years old. Therefore, the query should return the `name` and `age` of Ulysses.
