# CrumbCount — Data Requirements & Database Design

## 1. Objective

The objective of this document is to define the information required by CrumbCount, identify the system requirements and establish an initial relational database structure.

## 2. Business Focus

CrumbCount is designed as a Home Bakery Intelligence System covering:

- Recipe costing and profitability.
- Ingredient inventory management.
- Customer orders and sales.
- Production planning.
- Unsold products and wastage.
- Business decision support.

## 3. Functional Requirements

| ID | Requirement |
|---|---|
| FR01 | Product management |
| FR02 | Recipe costing |
| FR03 | Profitability analysis |
| FR04 | Ingredient purchase management |
| FR05 | Inventory tracking |
| FR06 | Expiry monitoring |
| FR07 | Order management |
| FR08 | Sales analysis |
| FR09 | Payment tracking |
| FR10 | Production tracking |
| FR11 | Finished goods tracking |
| FR12 | Wastage analysis |
| FR13 | Leftover value recovery |
| FR14 | Business dashboard |

## 4. Non-Functional Requirements

- Usability: Easy for small home bakers to understand.
- Accuracy: Financial calculations should be accurate.
- Data Integrity: Records should remain consistent.
- Performance: Reports should load efficiently.
- Maintainability: Data and calculations should be easy to update.
- Reliability: Reports should use valid and complete data.

## 5. Initial Data Entities

The proposed database entities are:

1. Products
2. Ingredients
3. Recipe_Ingredients
4. Purchases
5. Stock_Movements
6. Orders
7. Order_Items
8. Payments
9. Production_Batches
10. Finished_Stock_Movements

## 6. Database Design Principles

- Each table should have a primary key.
- Foreign keys should connect related records.
- Many-to-many relationships should use a linking table.
- Ingredient purchases should support batch-level expiry tracking.
- Inventory changes should be recorded as stock movements.
- Financial values should use appropriate decimal data types.
- Repeated information should be minimised.

## 7. Analytical Priorities

### Core
- Product-wise costing and profitability.
- Sales and revenue analysis.
- Ingredient stock monitoring.
- Production versus sales.
- Unsold products and wastage.
- Outstanding payments.

### Advanced
- Demand forecasting.
- Reorder recommendations.
- Product bundle analysis.
- Leftover value recovery.

## 8. Design Status

Initial requirements and database entities have been identified. Table structures, keys, relationships and data types will be refined before implementation in MySQL.

The database design will be reviewed against the project's business questions before dataset creation.
