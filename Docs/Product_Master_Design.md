# Product Master Design

The Product Master is the foundation of the CONTRAX Industries ERP system.

Every inventory transaction, purchase order, production order, sales order, and shipment references a product from this table.

## Purpose

The Product Master stores information about every product manufactured and sold by CONTRAX Industries.

## Planned Fields

| Field | Description |
|--------|-------------|
| Product_ID | Unique identifier for each product |
| Product_Name | Product name |
| Category | Product category |
| Unit_Cost | Manufacturing cost per unit |
| Sales_Price | Selling price per unit |
| Primary_Supplier | Main supplier |
| Lead_Time_Days | Standard lead time |
| Unit_Weight | Product weight |
| Product_Status | Active or Discontinued |

## Initial Goal

Create approximately 50 unique products across several product categories.

The Product Master will serve as the foundation for all future datasets and analytics projects.
