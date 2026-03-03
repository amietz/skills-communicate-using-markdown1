# Fresh Vegetables Online Shop

<img alt="Fresh vegetables basket" src="https://octodex.github.com/images/original.png" width="150" align="right">

Welcome to our online vegetable store! Browse our selection of fresh, organic vegetables delivered straight to your door.

## Shopping List

Plan your weekly groceries with our vegetable checklist:

- [ ] Carrots (1 kg)
- [ ] Broccoli (2 heads)
- [ ] Spinach (500 g)
- [ ] Tomatoes (1 kg)
- [ ] Bell Peppers (4 pcs)
- [ ] Zucchini (3 pcs)

## How to Place an Order

1. Browse our product catalogue
1. Add items to your cart
1. Proceed to checkout
1. Choose delivery date and address
1. Confirm and pay

## Review

Here is a quick script to check current vegetable stock using our API:

```bash
curl -X GET "https://api.freshveggies.example.com/stock" \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Accept: application/json"
```
