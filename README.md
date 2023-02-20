# Applying-Greedy-Algorithm-
An example of Applying a Greedy Agorithm

Marty has a bar of gold. Marty's firend Shea is to be paid this gold over course of 15 days, such that on day x, where 0<=x<=15, sheah has exactly x/15 of the total gold. Additionally on day 0 shea has no avaliable gold to use as change, what is the minimum number of pirecec that marty must break the gold bar into so that he can pay shea in this way?
Solution
We can solve this problem by using a greedy algorithm. The idea is to make the largest possible payment on each day while still being able to make the remaining payments using only the remaining gold.

First, we find the largest unit of gold that is less than or equal to the payment due on each day. Then, we use that unit of gold to make the payment and update the remaining gold. We repeat this process for each day until all payments are made.

To determine the minimum number of pieces, we must be able to break the gold bar into all of the units used to make the payments. The minimum number of pieces is equal to the number of unique unit sizes used.
