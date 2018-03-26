# Purchase-Fulfillment-System
Project for my coursework CS251-Object Oriented Analysis.

Hospitals, universities, airlines, large-scale retailers (Amazon, Wall Mart), governments, and armies use Enterprise Resource Planning (ERP) software like SAP to integrate systems that manage specific resources such as money (accounting), employees (HR), customers (Fulfillment), and inventory.
ERP Subsystems

Based on the descriptions given below and on your team's research, create use-case, domain, and if needed, process models, for the following ERM subsytems.

·       Human Resource Management (HRM)
·       Supply Chain Management
·       Fulfillment
·       Inventory Management
·       Accounting
·       Project Planning
·       Shipping

#Purchase Fulfillment System (PFS):
A PFS maintains an account for each registered customer. The account keeps track of the customer's purchase orders, shopping cart, contact info, credit cards, discount coupons, and invoices.
Of course the PFS allows a customer to browse and/or search inventory. A customer can add and remove items to and from his cart.
When a customer purchases the items in his cart, a purchase order (PO) is created and sent to the inventory management system (IMS) and the Shipping System (SS).
(The PO includes the cart, status (QUERY, IN_STOCK, OUT_OF_STOCK, CONFIRMED, CANCELLED, PURCHASED, SHIPPED, etc.) and the delivery information—address, speed of delivery, etc.) The IMS sends a confirmation back to the PFS indicating if the items in the PO are in stock or not.
The SS sends back the shipping cost. The PO is updated to reflect this information. If the items are in stock and if the customer agrees to the shipping costs, he confirms the purchase, otherwise he may change the items in his cart, modify the delivery information, or cancel the entire transaction. (When a transaction is cancelled, the cancelled PO is sent back to the IMS, which "returns" the items in the cart to the warehouse.)
If the PO is confirmed, an invoice is generated. The invoice reflects any discount coupons the customer may have. The invoice is displayed to the customer, who may pay with a credit card on file or with a new credit card. The credit card is charged. If the charge is denied, the customer is prompted for another credit card.
The customer may also cancel the transaction. Otherwise the invoice is marked as paid and the status of the PO is changed. The PO is sent back to the IMS for fulfillment and delivery.
A customer or a service agent may inquire about the status of an invoice or a PO. A service agent may cancel a PO and refund an invoice.

The project can be found here:
purchasefulfillmentsystem.wordpress.com
