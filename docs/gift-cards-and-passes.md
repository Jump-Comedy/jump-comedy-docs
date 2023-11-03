# Gift Cards and Passes

Gift cards are a form of payment. Customers can purchase gift cards and then use it to purchase tickets. Passes are 
different than gift cards in that they allow for purchases of tickets with a certain time frame. Gift card have no time frame.

## How Gift Card Work
- You can create multiple denominations of gift cards, $50, $100 etc.
- When customer purchases a gift card they will get an email with a gift card code which they can apply when purchasing tickets.
- Gift cards never expire, and remaining balances can be used on subsequent purchases.
- Gift cards apply to all events under your account. You can optionally restrict the application of a gift card to a category of products
- Customer buying gift cards pays service fees and taxes when purchasing the gift card.
- Customer using the gift card to buy tickets does not pay any service fee if gift card covers entire total; if gift card does not cover entire total, service fee is applied.
- Money from gift card purchases is immediately deposited into your Stripe account

## How Passed Work

- You can create a pass by setting a price for the pass and a start/end date for when that pass is applicable.
- When customer purchases a pass they will get an email with a pass code which they can apply when purchasing tickets.
- The pass allows you to buy any tickets under your account during that time period for free. You can optionally restrict the application of a pass to a category of products.
- Service fee is applied only when purchasing the pass. There is no service fee applied during purchase of tickets with the pass (since the total will always be 0 as it's a pass).
- One small caveat/restriction: When creating passes, you must keep the price of the pass higher than any of the tickets that the pass will be used with. For example, don't create a pass for $20 which would be used on tickets which are on sale for $50 (that would be kind of odd anyway)
- Money from pass purchases is immediately deposited into your Stripe account

*Important Note:* Gift Cards and Passes are not shown on the home page right now. If you want to use them you'll have to create them in the backend, copy the Gift Card/Pass URL and promote it through other means (e.g., email campaigns).  We are still deciding exactly where to show gift cards on the site as we don't want to confuse people by mixing up events and gift cards/passes. If you have ideas on this, let us know.