# ACME Supermarket

Build a client-side interactive shopping basket.

The application should allow you to add the following products to your basket:

| Product Code | Name | Price |
| --- | --- | --- |
| `FR1` | Fruit tea | £3.11 |
| `SR1` | Strawberries | £5.00 |
| `CF1` | Coffee | £11.23 |

The basket should automatically apply the following promotions:

- Buy-one-get-one-free for Fruit Tea
- The unit price for Strawberries drops to £4.50 when there are three or more of them in the basket

The user should be able to see all the items in their basket and the basket total. Items should animate in when added to the basket.

## Test Data

```
Basket: FR1, SR1, FR1, CF1
Total price expected: £19.34

Basket: FR1, FR1
Total price expected: £3.11

Basket: SR1, SR1, FR1, SR1
Total price expected: £16.61
```
