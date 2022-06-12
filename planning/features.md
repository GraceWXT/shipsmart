# Product Features
## Purpose
Shipsmart is a web app designed to facilitate inventory and order management for wholesale companies and make the tedious and error-prone work done accurately and elegantly.

## Users
- Manager/Admin
- Purchasing
- Warehouse Staff (Inventory Admin)
- Order Desk
- Account(billing & ordering, admin?)
- Customers(ordering)
- _Sales person_
- _Sample department_

## Functional Requirements
### General
- Register as a user/login
- Export inventory, pricing, customer, and order summary reports to excel

### Manager
- Assign/unassign users to/from roles
- Manage Roles
- Manage users
- Create, edit and deactivate warehouses
- _Approve special quote from sales person_

### Purchasing
- Create product/collection
- Create purchase order
- Update purchase order status/ETA
- Set low inventory alert for a product (or bulk edit) => weekly email?

### Warehouse Staff/Inventory Admin
- Confirm shipment arrival ATA, actual quantity, and add batch#
- Update warehouse location map

### Order Desk
- Add price points based on account/customer/product/quantity
- Get email on product arrival
- Notify customers with existing order by email
- _Notify sales person for new product sample_
- Check product availability and price (by collection or by product)
- Confirm, edit and cancel sales order
- Confirm temporary hold (auto delete with email notification in 72 hours)
- Allocate inventory/shipment to an order
- Set ship date (partial, courier)
- Sort/search for orders
- Generate packing list for order shipping/return/stock transfer
- Generate pickup summary for one or several given order number/project tag
- ~~Send invoice for shipped orders~~ (assuming QuickBooks for all accounting requirements)
- _Confirm sample order_
- _Schedule sample order ship date and create packing list (generate email)_
- _Update sample order status & tracking number_
- _Update sample display info_

### Accounts/Customers
- ~~Check account status (only account admin)~~ (assuming QuickBooks for all accounting requirements)
- Check product availability and price
- Create temporary hold request
- Create, view, edit and cancel sales order
- _View Claim request status_
- _View sample order status_

### Sales Person
- _Check product availability and price (mobile responsive)_
- _Create special quote_
- _Start, view and edit Claim request_
- _Create, view, edit and cancel sample order_
- _Update sample display info_

### Sample Department
- _View and update sample order status and dimension info_
- _Update sample order inventory_
