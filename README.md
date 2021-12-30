# BlackJack
I created a blackjack simulation app from scratch using python.
Can be used in automatic mode where the ai plays blackjack using basic strategy.
There is also a manual mode where the user can decide for himself which action to take.
And there is an automatic mode where the ai uses basic strategy as well as card counting using the popular Hi/Lo system.
https://www.blackjackapprenticeship.com/how-to-count-cards/

## How to run

First you need to install Matplotlib and Pndas using following commands
```
$ pip install matplotlib
$ pip install pandas
```
Now you can run the app using following command
```
$ python blackjack.py [how many decks should be in the shoe] [gamemode (manual, auto, autocount)] [how many hands should be played] [betsize for 1 hand] [starting money(bankroll)] 

For example:
$ python blackjack.py 4 manual
