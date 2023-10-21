# Trade-master
Backend Application written in type script and express for trading platform like zerodha where we can perform limit, quotes, check, order, balance operations for trading. 

This code is implementation of a server for a simplified trading platform. It handles limit orders (both "bid" and "ask"), maintains a depth chart, and manages user balances. Let's break down the code step by step:
flipBalance:
Swaps assets and money between two users based on the price and quantity of an executed order.
fillOrders:
Fills orders based on their type (bid or ask), price, and quantity.
Updates the order book and user balances accordingly.
Returns the remaining quantity after processing orders.
