### cash

## Basic

The cash command can take three type of arguments : 
cash <amount> <ActualCurrency> <TargetCurrencies>
  
 # Amount #
 
 Amount can be a integer or a float value. 
 It represents the sum we want to convert from our curency to our target currencies.
 If not filled, the default value is set to 1 and the function will ignore the first following currency.
 # ActualCurrency #
 
 ActualCurrency is a 3 letters string. It must be amongst the currency of the cash/lib/currencies.json file to be converted.
 If empty, the function will use the default ActualCurrency(can be modified).
 
 # TargetCurrency #
 
 TargetCurrencies is a list of currencies from the cash/lib/currencies.json file. 
 It represents the currencies in wich we would like to convert the amount.
 If not set, the function will use the default TargetCurrencies(can be modified).
 
 
 * The currencies can be written in lower or upper case letter, the program will parse them in upper case to match the string of the currencies.json file. *
 
 
 ## Function ##
 
 The function gives the converted amount from the ActualCurrency to each of the TargetCurrency.
 
 
 ## Default Value ##
 
 The default values at the beginning of the program are:
 -ActualCurrency:   USD
 -TargetCurrencies: USD / EUR / GBP / JPY
    

## Flags

# -s
cash -s <ActualCurrency> <TargetCurrencies> 
The -s flag will change the default currencies.
  The ActualCurrency will become the new default ActualCurrency and the list of the Target Currencies the new default TargetCurrencies.
  They will be saved in the config.json file.
  






