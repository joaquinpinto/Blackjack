# Blackjack

Joaquin Pinto's Blackjack Project
Created June 2018



Background:

I learned to program with Python during my time at the University of Chicago. 
I created this project as a way to practice my Python skills. 

Problems:

  1. I had some free time and wanted to improve my Python skills.
  2. We lost our Blackjack set in 2017 due to Hurricane Harvey.

Solution:

I decided to kill 2 birds with 1 stone.



How it works:

This program uses classes, dictionaries and lists to quickly handle the inputed data.
This Blackjack program is best played on IPython through Terminal, but works with any Python console.

It begins by asking how many players will be joining and asking for each person's name.
Make sure to write your name correctly and read instructions carefuly, the program will ask you to confirm.

Next each player is given 1000 chips, and asked if they would like to buy-in this round. 
The Players who chose to buy-in must then chose how much to bet.

Once all bets are in, each player is given two cards face-up. 
The dealer then receives one card face-up and one face-down.

The goal of the game is to get as close to 21 without going over.

Each card's value are as follows:
  2 through 10 are worth their numbers.
  J, Q, K are worth 10.
  A is worth 1 or 11 (depending on if the larger value would put you over 21).



Important terms:

Hit - You ask for an extra card.

Stay - You are content with your score.

Bust - You went over the score of 21; you lose your bet.



Round Play:

You are only playing against the Dealer.
This means that as long as you have more than the Dealer's final score without busting, you win.
The Dealer is required to hit until it gets to 17 or above.

Each player can chose to Hit or Stay, as long as they do not Bust



Win Condition:

You have blackjack if you start with a score of 21. 
Blackjack gives a payout of 2.5 times your initial bet.

You can otherwise win if you have a score greater than the Dealers and less than or equal to 21.
This can be done by hitting until you are as close as you are willing to go or staying at your original score.
Winning this way gives a payout of 2 times your initial bet.

If you bust or get less than the Dealer (without the Dealer busting) you lose your initial bet.



GOOD LUCK AND HAVE FUN
