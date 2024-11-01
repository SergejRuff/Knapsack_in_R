# Knapsack_in_R


0/1 Knapsack Problem in R

based on: https://www.youtube.com/watch?v=cJ21moQpofY

Decision Problem is NP-complete, however we can archive pseudo polynomial time
with dynamic programming.


Problem description

Given a set of objects, which have both value and weight (Vi,Wi), what
is the maximum value we can obtain by selecting a subset of these objects
such as that the sum of the weights does not exceed a certain (knapsack) capacity.


capacity = 7 kg

object 1 V=5, W=4


object 2 V=2, W=3

object 3 V=2,W=1

object 4 V=4,W=3

object 5 V=3,W=2

Not all objects fit in the 7 kg bag. We haveto select one subset with the maximum
V where sum of W<7.

Here we require DP, since we have to account for one object in regard to the previous
once and their information.
