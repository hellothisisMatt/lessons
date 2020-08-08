Assignment 1
============

You're going to be creating a really really basic lease calculator!

The goal of your application is to calculate the weekly, bi-weekly, or monthly payment amounts to own a car of a certain value.

As this will be a basic calculator (not really an accurate lease payment) we will be calculating our costs as follows:

```
Car Cost + Tax = Final Cost

For this example our tax will be fixed at 12% and our car will cost $12,000.

Example:
12000 + (0.12 * 12000) = 13440
```

For calculating the different payments you will take the total purchase amount (13440) in our last example and perform the following to get the payments:

Weekly = Total Purchase Amount / 52

Bi-Weekly = Total Purchase Amount / 26

Monthly = Total Purchase Amount / 12

The Calculator
===============
You're going to need to a couple things to create this calculator.

1. Ask the user for their purchase amount.
2. Ask the user if they are paying Weekly (W), Bi-Weekly (BW), or Monthly (M)
3. Calculate their payment amount and print it to the user.

Example:
```
Lease Calculator 1.0

What is your purchase amount?
> 50000
What payment frequency would you like to use?
> W
Your weekly payment will be $1076.92
```

Hints
-----
1. You're going to need to ask the user for their input. Use a scanner for this task.
2. The user will enter W, BW, or M for their payment frequency. You're going to need to have some control flow to account for each scenario.
3. When calculating a payment amount, the general rule is to NEVER use a float, use a double instead.
4. To get the payment amount to print out correctly, research on formatting options that you can do to print out a money value.