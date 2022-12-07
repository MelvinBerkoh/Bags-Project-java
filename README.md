# Bags-Project-java
After many long hours 
In client application, determine some probability of picking a certain coin from bag.
Example:  A bag contains 8 coins: 1 penny, 5 nickels, and 2 dimes. If you take one coin out, don’t put it back, and take another coin out, what is the probability that you'll get 1 nickel followed by 1 penny?
Begin by noting that since the coins are not replaced, each draw depends on previous draws and thus the draws are dependent.
P(1 nickel on first pick) = 5/8.
P(1 penny on second pick) = 1/7.
P(picking 1 nickel then picking 1 penny) = (5/8) × (1/7) = 5/56

I can randomly determine what coins and how many of each coin are in the bag.  Using  the methods from the ResizableArrayBag class to complete the problems.  Coming up with at least 5 scenarios that  would calculate the probability.  Making sure two of the problems deal with three picks. Also has examples that put the coin back in the bag before drawing the next one.  Probability is calculated differently when you put it back
