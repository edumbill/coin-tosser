Coin tossing simulation
=======================

In his book the Black Swan, Nicholas Nassim Taleb describes
a simple way to derive a Gaussian distribution curve. Gamble
repeatedly on the outcome of a coin toss. If it's heads, you
win a dollar. If it's tails, you lose a dollar. Repeat the
experiment for, say, 20 tosses, and record your net winnings.
Run the experiment repeatedly, and then plot the frequency
of each amount: you get a Gaussian "bell curve".

This program runs the game Taleb describes.

* clojure/ -- a simple Clojure command line implementation
* clojurescript -- a web based demonstration

Read more about this curve here at
http://www.mathamazement.com/Lessons/Pre-Calculus/10_Sequences-Induction-and-Probability/probability.html