# cash


## Function
cash <amount> <ActualCurrency> <TargetCurrencies[]>
  The function can take several arguments.

* amount    
  The amount represent the value we want to convert.       
  **Should be filled.**

* ActualCurrency   
  The currency we want to convert.     
  **If not filled, the default ActualCurrency will be used.**

* TargetCurrencies[]        
  List of the currencies we would like the amount of ActualCurrency to be converted to.      
  **If not filled, the default TargetCurrencies will be used.**

## Flag

* -s
  cash -s <ActualCurrency> <TargetCurrencies[]>   
  The flag -s can modified and save the default currencies.     
  The ActualCurrency will be the new default currency and the TargetCurrencies will be the new default TargetCurrencies.
  
 
* --set
  'cash --set <ActualCurrency> <TargetCurrencies[]>'   
  Gives the change rate of the ActualCurrency for all the TargetCurrencies.    
  Sames result as 'cash 1  <ActualCurrency> <TargetCurrencies[]>'
