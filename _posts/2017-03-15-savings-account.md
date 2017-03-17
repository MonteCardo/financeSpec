---
category: Investment Models
title: 'Savings Account'
---

A Savings Account is an investment that has an invested value in each day of the month and that pays daily a value referent to the same day on last month.

### Calculating

<!-- TODO Make it LaTeX later -->
* Total value in day *x* of month *y* = (Total value of yesterday) + ((Value invested in day *x* of last month) * (Interest Rate))

### Problems

* This model has a little question: How to treat days that will not have an equivalent next month? Like March 29, 30 and 31, that don't have the respective February 29, 30 and 31 to derive their values. Some places ignore those days, registering everything put on these days on the first day of next month. Should study if there is another popular strategy.
* How to treat withdrawals? Possible strategies:
    * First Movement - Takes the oldest investment and start removing money from him.
    * Last Movement - Takes the latest investment and start removing money from him.
    * Farthest Return - Considers the farthest day that will give any return and start removing from him.
    * Nearest Return - Considers the next day that will give any return and start removing from him.
