# 20_ProfitSplitter_Solidity

## Level One Contract: AssociateProfitSplitter contract
AssociateProfitSplitter contract is for equal payment for all employee. 
Each employee will receive equal amount of payment from Human Resources. 

![LevelOne_code]()

Before Deploy the contract, only employee account numbers need to be enter in the field. Transaction total amount enter in the message value and then deposit function will divide the amount equally in number of employee. 

Leftover amount will be transfer back to Human Resources. 

Balance will be return 0. 
![LevelOne_code]()

AssociateProfitSplitter contract : [LevelOne]()

## Level Two Contract: TieredProfitSplitter contract
TieredProfitSplitter contract helps to pay in different tiers in the company. It is calculated by the different percentages in each tier.

Before Deploy the contract, only employee account numbers need to be enter in the field. It will calculate according to the order of employee account entered and its percentage detail. 

![LevelTwo_code]()

TieredProfitSplitter contract : [LevelTwo]()

## Level Three Contract : DeferredEquityPlan contract
DeferredEquityPlan contract is for stock distribution over 4 years for a single employee. 

![LevelThree_code]()

DeferredEquityPlan contract : [LevelThree]()