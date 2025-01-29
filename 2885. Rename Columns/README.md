# Solution to Rename DataFrame Columns

## Problem

You are given a DataFrame `students` with the following columns:

| Column Name | Type   |
|-------------|--------|
| id          | int    |
| first       | object |
| last        | object |
| age         | int    |

The goal is to rename the columns to the following:

- `id` → `student_id`
- `first` → `first_name`
- `last` → `last_name`
- `age` → `age_in_years`

## Example

### Input:

| id  | first   | last     | age |
|-----|---------|----------|-----|
| 1   | Mason   | King     | 6   |
| 2   | Ava     | Wright   | 7   |
| 3   | Taylor  | Hall     | 16  |
| 4   | Georgia | Thompson | 18  |
| 5   | Thomas  | Moore    | 10  |

### Output:

| student_id | first_name | last_name | age_in_years |
|------------|------------|-----------|--------------|
| 1          | Mason      | King      | 6            |
| 2          | Ava        | Wright    | 7            |
| 3          | Taylor     | Hall      | 16           |
| 4          | Georgia    | Thompson  | 18           |
| 5          | Thomas     | Moore     | 10           |
