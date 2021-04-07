# ACME Supermarket

Build a shopping basket in JavaScript or TypeScript.

You should be able to add the following products to your basket:

| Product Code | Name | Price |
| --- | --- | --- |
| `FR1` | Fruit tea | £3.11 |
| `SR1` | Strawberries | £5.00 |
| `CF1` | Coffee | £11.23 |

The basket should automatically apply the following promotions:

- Buy-one-get-one-free: applies only to Fruit Tea
- Bulk-buy: the unit price for Strawberries drops to £4.50 when there are three or more of them in the basket

The basket should be able to calculate the correct basket total.

## Test Data

```
Basket: FR1, SR1, FR1, CF1
Total price expected: £19.34

Basket: FR1, FR1
Total price expected: £3.11

Basket: SR1, SR1, FR1, SR1
Total price expected: £16.61
```
