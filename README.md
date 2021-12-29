# BlackJack
I created a blackjack simulation app from scratch using python.
Can be used in automatic mode where the ai plays blackjack using basic strategy.
There is also a manual mode where the user can decide for himself which action to take.
And there is an automatic mode where the ai uses basic strategy as well as card counting.

## How to run

First install Matplotlib aswell as pandas
```
$ pip install matplotlib
$ pip install pandas
```
Now you can run the app using following command
```
$ python blackjack.py [number of decks shuffled in the shoe] [gamemode (manual, auto, autocount)]

For example:
$ python blackjack.py 4 manual
