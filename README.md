# sales-stock-level-planner
This simulates a sales and operations planning using the zero-stock level strategy.
## Required data and usage 
- An initial stock level for a product

- The number of month(s) to plan

- The planned sales quantity for each month
## How stock level calculation will be executed 
Based on this data, calculate the required production quantity as follows:

- If the sales quantity is smaller than the stock level of the previous month, the production quantity is 0

- If the sales quantity is larger than the stock level of the previous month, the production quantity is this difference
