# Uplift model project


Task - get a part of the "Fox" (shop name) clients so that the total profit from a campaign
with a similar offer is as large as possible.

Files:

**customers.csv — user description:**
| customer_id      | age | location | 
| -----------------|:---:| --------:|
| ID               | age | location | 


**receipts.csv — purchase history:**
| customer_id | date           | purchase_amt                            | purchase_sum   |
| ------------|:--------------:|----------------------------------------:|---------------:|
| ID          | day of purchase| amount of purchased fisstech (in grams) | purchase price | 


**campaigns.csv — campaign history:**
| customer_id | date                 | n_offer_days                       | target_group_flag                   |
| ------------|:--------------------:|-----------------------------------:|------------------------------------:|
| ID          | first day of purchase| duration (in days) of the discount | target (1) / control (0) group flag | 
