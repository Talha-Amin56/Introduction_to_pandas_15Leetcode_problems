# Solution to Fill Missing Quantity Values in Products DataFrame

## Problem Description:
In this task, you are asked to fill the missing values (represented as `None`) in the `quantity` column of the `products` DataFrame with `0`.

## DataFrame Structure:

The DataFrame has the following columns:
- `name`: The name of the product.
- `quantity`: The quantity of the product in stock, which may have missing (`None`) values.
- `price`: The price of the product.

### Example Input:
| name            | quantity | price |
|-----------------|----------|-------|
| Wristwatch      | None     | 135   |
| WirelessEarbuds | None     | 821   |
| GolfClubs       | 779      | 9319  |
| Printer         | 849      | 3051  |

### Example Output:
| name            | quantity | price |
|-----------------|----------|-------|
| Wristwatch      | 0        | 135   |
| WirelessEarbuds | 0        | 821   |
| GolfClubs       | 779      | 9319  |
| Printer         | 849      | 3051  |

## Task:
The goal is to replace any missing values (`None`) in the `quantity` column with `0`. The output DataFrame should have the missing quantity values filled in.

## Conclusion:
This solution will address any missing values in the `quantity` column of the `products` DataFrame, ensuring data completeness for further analysis or processing.
