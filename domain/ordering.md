# Ordering

How to make a purchase?

## Cart Item

- Cart
- Product
- Offer (initially null)
- Quantity (initially null)

## Cart

- Delivery Address

## Order Item

- Order
- Seller
- Product
- Offer
- Commercial Unit
- Unit Price
- Quantity
- Total Price
- Status

## Order

- Delivery Address
- Delivery Date
- Delivery Time
- Total Amount
- Status

## Business Rules

- Every Business can make a Order.
- A Product is added to the Cart as a Cart Item through the Catalog.
- A Cart Item must have an Offer and Quantity before an Order can be created.
- Offers are only available to Buyers within the Seller's delivery areas.
- Changing the Cart's Delivery Address may invalidate selected Offers.
- Payment must be completed before an Order can be created.
- When an Order is created, each Cart Item is converted into an Order Item.
- Once created, an Order can only be cancelled until the Seller accept the Order.
