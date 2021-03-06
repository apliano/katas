# Discounts

## Description

The marketing team for a local grocery store wants to boost sales. To do so, they want to start using automatic discounts during checkout. The automatic discounts that they would like to have are:

- Buy one bag of grapes and get another bag of grapes for free ("Two for the price of one")
- Buy at least two apples and get a 20% discount on apples

The products that are currently available in their store are:

- Bag of grapes priced at $5 per bag
- Apples priced at $3 per apple
- Peaches priced at $7 per peach
  Your task: Build a program to calculate the total price at checkout for a customer, taking discounts into consideration.

## Behaviour

The input to your solution should match the following schema: `[ [ <product>, <quantity> ],...]`
The output of your solution should be a number representing the total price at checkout after discounts.
Your solution should work for any combination of products listed above, in any quantities equal to or above 0. You do not need to handle unlisted products or quantities below 0.

## Input/Output Expectations

Here are some example inputs and outputs. Note that the input does not have to look _exactly_ like this. It can vary based on whatever is customary for the chosen language. For example, ruby commonly uses nested arrays but strongly typed languages like C#, Java, and C++ would commonly use lists of tuples. It is the spirit of the input that matters. Shape your input in whatever way makes sense for your language of choice. This isn't meant to be an input parsing challenge.

```ruby
 # eg. in ruby
 [ ['grapes', 1], ['apples', 0], ['peaches', 1] ] # output => 12
 [ ['grapes', 1], ['apples', 1], ['peaches', 1] ] # output => 15
 [ ['grapes', 2], ['apples', 2], ['peaches', 1] ] # output => 16.8
 [ ['grapes', 3], ['apples', 5], ['peaches', 2] ] # output => 36
 [ ['peaches', 7], ['grapes', 7], ['apples', 7] ] # output => 85.8
```

```java
  // eg. in Java
  Arrays.asList(new Tuple("grapes", 1), new Tuple("apples", 0), new Tuple("peaches", 1))
```
