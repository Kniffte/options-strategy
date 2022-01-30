# #1

### Underlying selection

### Option selection
* Theta decay 
    * OTM - acceleration during last __90 DTE__
    * ATM - acceleration during last __30 DTE__
    * ITM - linear time decay
* Select options __ATM & ~30 DTE__
### Trading rules
* 70 % take profit 
* Check position __@ ~5 DTE__
    1. Option OTM
        * Close & search new trade
    2. Option ATM
        * Close & search new trade
    3. Option ITM
        * Close if profit
        * Roll position for a credit
            1. New option with lower strike & 30 - 60 DTE
            2. New option with same strike & 30 - 60 DTE
            3. New option x2 with lower strike & 30 - 60 DTE


### 