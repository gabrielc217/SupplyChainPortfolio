# Data Dictionary

This document defines the core datasets used in the CONTRAX Piano Works supply chain analytics portfolio.

All data is fictional and created for educational and professional portfolio purposes.

---

## Products

| Column | Description |
|---|---|
| Product_ID | Unique product identifier |
| Product_Name | Name of the product |
| Category | Product category |
| Product_Family | Product line or series |
| Unit_Cost | Cost to manufacture or purchase one unit |
| Sales_Price | Selling price per unit |
| Supplier_ID | Primary supplier identifier |
| Standard_Lead_Time_Days | Expected replenishment lead time |
| Product_Status | Active or discontinued |

---

## Suppliers

| Column | Description |
|---|---|
| Supplier_ID | Unique supplier identifier |
| Supplier_Name | Fictional supplier name |
| Region | Supplier region |
| Average_Lead_Time_Days | Average delivery lead time |
| Supplier_Rating | Overall supplier score |
| Defect_Rate | Estimated quality defect rate |

---

## Warehouses

| Column | Description |
|---|---|
| Warehouse_ID | Unique warehouse identifier |
| Warehouse_Name | Facility name |
| City | Facility city |
| State | Facility state |
| Facility_Type | Manufacturing plant or distribution center |

---

## Inventory

| Column | Description |
|---|---|
| Inventory_ID | Unique inventory record |
| Product_ID | Product identifier |
| Warehouse_ID | Warehouse identifier |
| Quantity_On_Hand | Current inventory quantity |
| Safety_Stock | Minimum buffer inventory |
| Reorder_Point | Inventory level that triggers replenishment |
| Inventory_Value | Quantity on hand multiplied by unit cost |

---

## Purchase Orders

| Column | Description |
|---|---|
| PO_ID | Unique purchase order identifier |
| Supplier_ID | Supplier identifier |
| Product_ID | Product identifier |
| Order_Date | Date purchase order was created |
| Due_Date | Expected delivery date |
| Received_Date | Actual delivery date |
| Quantity_Ordered | Quantity ordered |
| Quantity_Received | Quantity received |
| PO_Status | Open, received, late, or cancelled |

---

## Sales Orders

| Column | Description |
|---|---|
| Sales_Order_ID | Unique sales order identifier |
| Customer_ID | Customer identifier |
| Product_ID | Product identifier |
| Order_Date | Date customer order was placed |
| Requested_Ship_Date | Date customer requested shipment |
| Quantity_Ordered | Quantity ordered by customer |
| Sales_Revenue | Quantity multiplied by sales price |
| Order_Status | Open, shipped, backordered, or cancelled |

---

## Production Orders

| Column | Description |
|---|---|
| Production_Order_ID | Unique production order identifier |
| Product_ID | Product identifier |
| Warehouse_ID | Manufacturing facility |
| Start_Date | Production start date |
| Planned_Completion_Date | Expected completion date |
| Actual_Completion_Date | Actual completion date |
| Quantity_Planned | Planned production quantity |
| Quantity_Completed | Finished quantity |
| Scrap_Quantity | Quantity scrapped during production |
| Production_Status | Open, completed, delayed, or cancelled |

---

## Shipments

| Column | Description |
|---|---|
| Shipment_ID | Unique shipment identifier |
| Sales_Order_ID | Related sales order |
| Ship_Date | Actual shipment date |
| Carrier | Fictional logistics carrier |
| Delivery_Date | Actual delivery date |
| On_Time_Flag | Indicates whether shipment was delivered on time |
