# Product Features
## Purpose
Shipsmart is a web app designed to facilitate inventory and order management for wholesale companies and make the tedious and error-prone work done accurately and elegantly.

## Users
- Manager/Admin
- Purchasing
- Warehouse Staff (Inventory Admin)
- Order Desk
- Account(billing) -> Customers(shipping)
- _Sales person_
- _Sample department_

## Functional Requirements
### General
- Register as a user/login
### Manager
- Assign/unassign users to/from roles
- Manage Roles
- Manage users

### Purchasing
- Create product/collection
- Create purchase order
- Update purchase order status/ETA
- Set low inventory alert for a product (or bulk edit) => weekly email?

### Warehouse Staff/Inventory Admin
- Confirm shipment arrival ATA, actual quantity, and add batch#
- Update warehouse location map

### Order Desk
- Get email on product arrival
- Notify customers with existing order by email
- _Notify sales person for new product sample_
- Check product availability and price (by collection or by product)
- Create, edit and cancel sales order
- Create temporary hold (auto delete with email notification in 72 hours)
- Allocate inventory/shipment to an order
- Set ship date (partial, courier)
- Sort/search for orders
- Generate packing list for order shipping/return/stock transfer
- Send invoice for shipped orders

### Accounts/Customers
- Check product availability and price
- Create temporary hold
- Create order
- Check account status

### Sales Person
- Check product availability and price
