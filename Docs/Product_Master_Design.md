# Product Master Design

The Product Master is the foundation of the CONTRAX Piano Works ERP-style data model.

Every inventory record, purchase order, production order, sales order, and shipment will reference a product from this table.

## Purpose

The Product Master stores information about every finished piano, accessory, and selected service component sold by CONTRAX Piano Works.

## Planned Fields

| Field | Description |
|---|---|
| Product_ID | Unique identifier for each product |
| Product_Name | Product name and model |
| Category | Broad product category |
| Product_Family | Product line or series |
| Unit_Cost | Standard manufacturing or purchase cost |
| Sales_Price | Standard selling price |
| Supplier_ID | Primary supplier or source reference |
| Lead_Time_Days | Standard replenishment or production lead time |
| Unit_Weight_lb | Product weight in pounds |
| Product_Status | Active or Discontinued |

## Planned Categories

- Grand Pianos
- Upright Pianos
- Digital Pianos
- Stage Pianos
- Hybrid Pianos
- MIDI Controllers
- Piano Accessories
- Replacement Components

## Initial Goal

Create the first 10 products manually to establish the naming conventions and product structure.

Additional products will later be generated and reviewed using Python.

The Product Master will support all future supply chain datasets and analytics projects.
