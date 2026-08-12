# Ordering

How to make a purchase?

### Cart Item

- Cart
- Product
- Offer (initialy null)
- Quantity (initialy null)

### Cart 

- Delivery Address

### Order Item

- Order
- Seller
- Product
- Commercial Unit
- Unit Prive
- Quantity
- Total Price 
- Status

### Order 

- Delivery Address
- Delivey Date
- Delivery Time
- Total Amount
- Status

## Bussiness Rules

- A Cart Item is add as a Product via Catalog
- The Delivery Address attached to the Cart can influence the availible Offer options
- Changing the Cart's Delivery Address invalidates any selected Offers that are no longer available for the new address.
- To proceed to the Order is necessary make the payment
- To proceed to the payment is necessary choose a Offer and Quantity for each Item Cart
- When an Order is created, each Cart Item is converted into an Order Item
- Once created, an Order cannot be modified or cancelled.