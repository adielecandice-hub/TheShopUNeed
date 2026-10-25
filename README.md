# TheShopUNeed — Starter website

This is a mobile-friendly storefront prototype with a warm cream / beige / espresso palette.

## Open it
1. Extract `TheShopUNeed_Starter.zip`.
2. Open `index.html` in a browser.
3. Use the **Admin** button in the top navigation.
4. Demo password: `candice123`.

## What works in this prototype
- Responsive home page and product grids
- Category filters
- Product detail modal and product options
- Shopping bag with quantity changes
- Demo checkout form
- Browser-local demo orders
- Admin product create/edit/delete
- Stock counts and basic shop settings
- Browser local storage, so changes persist in the same browser/device

## Important before real launch
This is a front-end prototype, **not a live ecommerce system**. Do not use it to accept real payments or store real customer information.

Before publishing for customers, it needs:
- A secure backend/database for products, variations, stock and orders
- Real admin authentication (the demo password is visible in the source and is not secure)
- A payment provider integration (e.g. Paystack/Flutterwave, subject to account approval and current requirements)
- Verified payment webhooks and server-side order confirmation
- Delivery/shipping rules, customer notifications and privacy/terms/refund policies
- Real product photography and confirmed descriptions/prices
- Deployment and domain setup

## Easy first edits
In `index.html`, find the `seedProducts` array to change the sample products. Or use the demo Admin dashboard to add/edit products locally.
