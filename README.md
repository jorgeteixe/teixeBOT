# teixeBOT
Telegram bot for my personal things.

## Commands
#### Cryptocurrency watchlist
Receive scheduled updates on the selected pair each n minutes.

Usage: 
```
/watch <pair> <interval>       >> Adds to watchlist
    pair:       valid pair from Binance Exchange
    interval:   minutes between messages [min: 1  max: 1440 (day)]

/unwatch <pair>                >> Removes from watchlist
    pair:       pair on your watchlist

/watching                      >> Shows watchlist
```


#### Trade cryptocyrrency watchlist
Receive scheduled updates on the selected pair each n minutes.

Usage: 
```
/wtrade <pair> <interval> <enterPrice>      >> Adds to watchtrades-list
    pair:       valid pair from Binance Exchange
    interval:   minutes between messages [min: 1  max: 1440 (day)]
    enterPrice: base price to show actual position

/unwtrade <pair>                            >> Removes from watchtrades-list
    pair:       pair on your watchtrades-list

/wtrades                                    >> Shows watchtrades-list
```



### Telegram-like format command list
```
watch - add a cryptocurrency pair to your watchlist
unwatch - remove a pair from your watchlist
watching - show your watchlist
wtrade - add a trade to your watchtrades-list
unwtrade - remove a pair from your watchtrades-list
wtrades - show your watchtrades-list
```