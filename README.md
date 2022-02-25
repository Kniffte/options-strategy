# #1

### Underlying selection

### Option selection
* Theta decay 
    * OTM - acceleration during last __90 DTE__
    * ATM - acceleration during last __30 DTE__
    * ITM - linear time decay
* Select options __ATM & ~30 DTE__
### Trading rules
* Sell put 1x __ATM / OTM & ~30 DTE__
* 70 % take profit 
* Check position __@ ~5 DTE__
    1. Put OTM
        * Close & search new trade
    2. Put ATM
        * Close & search new trade
    3. Put ITM
        * Close if profit
        * Roll position for a credit
            1. New put with lower strike & 30 DTE
            2. New put with lower strike & 60 DTE
            3. New put with same strike & 30 DTE
            4. New put with same strike & 60 DTE
            5. New put x2 with lower strike & 30 DTE
            6. New put x2 with lower strike & 60 DTE
* Owning 200 stocks
* Sell call 1x __ATM / OTM & 30 DTE__
    1. 


### 