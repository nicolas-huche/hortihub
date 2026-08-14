# Future Features

Features planned for future versions.

## Seller Delivery Areas

Allow Sellers to define the areas where they deliver.

- Offers are only available to Buyers within the Seller's delivery areas.
- Changing the Cart's Delivery Address may invalidate selected Offers.

## Marketplace Payment & Fulfillment

Allow Sellers to accept or decline Order Items in case of stock shortages, operational issues, or other unexpected circumstances.

- Sellers can accept or decline their Order Items.
- The marketplace holds the corresponding payment until fulfillment is confirmed.
- Declined or unfulfilled Order Items can be partially refunded.
- Seller failures may result in penalties or suspension.
- Add abuse detection for Buyers and Sellers exploiting refunds or compensation.

## Natural Language Cart Input

Allow Buyers to describe their desired purchase in natural language.

Examples:

- Banana Prata, 5 kg, Seller A -> Product + Offer + Quantity
- Banana Prata, 5 kg -> Product + Quantity, Offer selected later
- Banana Prata -> Product, Offer and Quantity selected later
- Banana -> Product Family, system asks the Buyer to select a Product

## Business Organization

Allow multiple Users to belong to the same Business.

- A Business can have multiple Users.
- Users can have different roles within a Business.
- Orders, Offers, and other commercial data belong to the Business rather than to an individual User.
- A User's permissions are determined by their role within a Business.
- Removing a User from a Business must not remove the Business's historical commercial data.

### Example Roles

- Business Owner -> manages the Business and its Users.
- Buyer -> creates and manages purchases.
- Seller Manager -> manages Offers and Seller operations.
- Finance -> manages payments and financial information.