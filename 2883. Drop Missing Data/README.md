# Remove Rows with Missing Values

## DataFrame: students

| Column Name | Type   |
|-------------|--------|
| student_id  | int    |
| name        | object |
| age         | int    |

There are some rows having missing values in the name column.

## Task
Write a solution to remove the rows with missing values.

## Example

### Input:

| student_id | name    | age |
|------------|---------|-----|
| 32         | Piper   | 5   |
| 217        | None    | 19  |
| 779        | Georgia | 20  |
| 849        | Willow  | 14  |

### Output:

| student_id | name    | age |
|------------|---------|-----|
| 32         | Piper   | 5   |
| 779        | Georgia | 20  |
| 849        | Willow  | 14  |

### Explanation:
Student with id 217 has an empty value in the name column, so it will be removed.
