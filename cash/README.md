### cash


## Function
cash <amount> <ActualCurrency> <TargetCurrencies[]>
  The function can take several arguments.

* amount    
  The amount represent the value we want to convert.       
  **Should be filled

* ActualCurrency   
  The currency we want to convert.     
  **If not filled, the default ActualCurrency will be used.

* TargetCurrencies[]        
  List of the currencies we would like the amount of ActualCurrency to be converted to.      
  **If not filled, the default TargetCurrencies will be used.

## Flag
cash -s <ActualCurrency> <TargetCurrencies[]>
  The flag -s can modified and save the default currencies.
  The ActualCurrency will be the new default currency and the TargetCurrencies will be the new default TargetCurrencies.
  
 
