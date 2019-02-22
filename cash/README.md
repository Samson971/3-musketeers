# Cash


## Installation

* Clone the repository
* Run `npm i` in the folder cash


## Function

To run the program:
`node bin/index.js <amount> <ActualCurrency> <TargetCurrencies[]>`      
  
The function can take several arguments: 

  * amount    
    The amount represent the value we want to convert.       
    **Should be filled.**

  * ActualCurrency   
    The currency we want to convert.     
    **If not filled, the default ActualCurrency will be used.**

  * TargetCurrencies[]        
    List of the currencies we would like the amount of ActualCurrency to be converted to.      
    **If not filled, the default TargetCurrencies will be used.**


 ### Remarks
 If there is no arguments, the program will run with 1 unit of the Default ActualCurrency to the Default TargetCurrencies[] (USD to USD,  GBP, EUR, JPY when the program starts).     
 If the amount is not filled but there one or several currencies in arguments, the first one will be ignored and the fixed amount will be 1 unit of the second/default currency.

## Flag

* -s      
  `cash -s <ActualCurrency> <TargetCurrencies[]>`   
  The flag -s can modified and save the default currencies.     
  The ActualCurrency will be the new default currency and the TargetCurrencies will be the new default TargetCurrencies.
  
 
* --set       
  `cash --set <ActualCurrency> <TargetCurrencies[]>`   
  Gives the change rate of the ActualCurrency for all the TargetCurrencies.    
  Same result as `cash 1  <ActualCurrency> <TargetCurrencies[]>`
