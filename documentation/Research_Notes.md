# CrumbCount — Research Notes

## 1. Research Overview

**Project:** CrumbCount  
**Research Area:** Home Bakery Operations  
**Research Method:** Secondary Research  
**Status:** In Progress

### Purpose

The purpose of this research is to understand how small home bakeries operate, identify their common business challenges and determine where data analytics can support better decision-making.

## 2. Areas of Investigation

The research will focus on the following areas:

1. Recipe Costing and Pricing
2. Ingredient Inventory Management
3. Order and Sales Management
4. Profitability Analysis
5. Batch Production and Unsold Products
6. Food Wastage Management
7. Demand Forecasting

## 3. Research Findings

*Findings will be added as research progresses, along with their supporting sources.*

| Research Area | Finding | Source | Status |
|---|---|---|---|
| Costing | To be investigated | Pending | Not started |
| Pricing | To be investigated | Pending | Not started |
| Inventory | To be investigated | Pending | Not started |
| Sales | To be investigated | Pending | Not started |
| Profitability | To be investigated | Pending | Not started |
| Wastage | To be investigated | Pending | Not started |
| Forecasting | To be investigated | Pending | Not started |

## 4. Initial Assumptions

The following are preliminary assumptions, not verified findings:

- Some home bakers may rely on manual records for business management.
- Ingredient price fluctuations may affect production costs.
- Advance production may result in unsold products.
- Inaccurate costing may lead to incorrect pricing decisions.
- Historical sales information may help improve production planning.

These assumptions will be evaluated during research.

## 5. Analytical Questions

- What factors contribute to the total cost of a bakery product?
- How should bakers determine their selling prices?
- How can ingredient wastage be measured?
- How can unsold products affect profitability?
- What is the relationship between sales volume and product profitability?
- Can historical demand help optimise production quantities?

## 6. Research Sources

*External sources and references will be documented here.*

## 7. Research Limitations

- No direct home baker interviews have been conducted yet.
- Initial findings will depend on publicly available information.
- Sample datasets may not represent every home bakery.
- Assumptions will need validation before being treated as established facts.

## 8. Research Progress

This document will be updated throughout the project as new information, findings and requirements are identified.

## Research Topic 1: Recipe Costing & Pricing

**Status:** Initial Research Completed

### 1. Key Findings

- Ingredient costs should be calculated based on the actual quantity used in a recipe.
- Production costs include ingredients, packaging, labour, utilities, overheads and wastage.
- Revenue and profit are different financial measures.
- Selling prices should account for the complete production cost.
- Changes in ingredient purchase prices can affect product profitability.

### 2. Cost Components Identified

| Component | Description |
|---|---|
| Ingredients | Flour, sugar, butter, chocolate, eggs, etc. |
| Packaging | Cake boxes, boards, labels and ribbons |
| Labour | Time spent preparing and decorating |
| Utilities | Electricity, gas and water |
| Overheads | Equipment maintenance and other shared expenses |
| Wastage | Ingredients or products lost during production |

### 3. Initial Analytical Questions

1. Which cost component contributes the most to production costs?
2. How do ingredient price changes affect product profitability?
3. Are products priced using their complete production costs?

### 4. Implications for CrumbCount

The system should eventually record:

- Ingredient purchase prices and quantities.
- Recipe-level ingredient consumption.
- Packaging expenses.
- Labour and overhead costs.
- Production wastage.
- Product selling prices.

### 5. Research Sources

- Baker's Bridge – Cake Cost Calculation and Pricing.
- MyPadosi – Homemade Food Pricing.
- Nilu's Cakes & Bakes – Home Bakery Pricing Guide.

### 6. Research Limitations

The information gathered provides general costing guidance. Actual costs and pricing practices may vary between home bakeries and require validation using real business records.

## Research Topic 2: Ingredient Inventory Management

**Status:** Initial Research Completed

### 1. Key Findings

- Ingredient purchase records should capture quantities, prices and procurement sources.
- Inventory should be monitored to avoid shortages and unnecessary purchases.
- FIFO (First In, First Out) and FEFO (First Expire, First Out) are important stock rotation concepts.
- Appropriate storage conditions and expiry monitoring are important for food safety.
- Raw ingredients and finished bakery products should be tracked separately.

### 2. Inventory Information Identified

| Information | Purpose |
|---|---|
| Ingredient name | Identify the material |
| Supplier | Track procurement sources |
| Purchase date | Record when stock was received |
| Quantity purchased | Track incoming stock |
| Purchase price | Calculate ingredient costs |
| Quantity consumed | Monitor production usage |
| Available quantity | Determine remaining stock |
| Expiry date | Monitor expiry risks |
| Batch/Lot ID | Identify individual stock batches |

### 3. Initial Analytical Questions

1. Which ingredients are consumed most frequently?
2. Which ingredients need restocking?
3. How much inventory remains unused?
4. Which ingredients are at risk of expiring?
5. How much financial value is lost through expired or wasted ingredients?
6. Does purchasing in larger quantities reduce costs or increase wastage?

### 4. Implications for CrumbCount

The inventory module should eventually support:

- Ingredient purchase tracking.
- Stock balance calculations.
- Ingredient consumption records.
- Batch and expiry tracking.
- FIFO and FEFO stock rotation.
- Reorder-level monitoring.
- Ingredient wastage analysis.
- Separate tracking of raw ingredients and finished products.

### 5. Research Sources

- FSSAI – Food Safety and Management System Guidelines.
- FSSAI – Bakery Level 1 Training Material.
- FSSAI – Food Safety and Standards operational guidance.

### 6. Research Limitations

The research provides general food-storage and inventory-management guidance. Actual inventory practices may vary according to the bakery's size, ingredients, storage facilities and operating model.

Specific storage conditions and shelf lives must be determined using appropriate food-safety guidance rather than assumed by the analytical system.

## Research Topic 3: Order & Sales Management

### 1. Research Objective
To understand how small home bakeries manage customer orders, record sales, track payments and identify product demand.

### 2. Types of Bakery Sales

**A. Made-to-Order Sales**
- Products are prepared after receiving confirmed customer orders.
- Examples: customised cakes, birthday cakes and personalised desserts.
- Orders require customer details, product specifications, quantity, agreed price, due date and payment status.

**B. Advance-Batch Sales**
- Products are prepared before receiving individual customer orders.
- Examples: brownies, cupcakes and cookies sold through Instagram, WhatsApp or stalls.
- Sales records should track quantities produced, quantities sold and remaining finished products.

### 3. Important Information to Record
- Order ID
- Order date
- Customer details
- Product name
- Quantity
- Selling price
- Total order value
- Advance payment and balance due
- Order status
- Fulfilment date
- Sales channel

### 4. Key Findings
- Customer enquiries should be distinguished from confirmed orders.
- Sales revenue and actual profit are different measurements.
- Order status and payment status should be tracked separately.
- Different sales channels may generate different levels of revenue.
- Made-to-order and advance-batch sales require different tracking approaches.

### 5. Initial Analytical Questions
1. Which products generate the highest revenue?
2. Which products sell the highest number of units?
3. Which days or periods have the highest sales?
4. What is the average order value?
5. How many orders are cancelled?
6. How much payment is outstanding?
7. Which sales channel generates the highest revenue?

### 6. Initial Business Hypotheses

**Hypothesis 1 — Product Bundling**

Offering a discounted combination of a high-revenue product and a complementary product may encourage customers to purchase additional items.

Example: Offering cookies at a discounted price when customers purchase a chocolate cake.

This should be tested against product costs and profit margins before implementation.

**Hypothesis 2 — Production Planning**

Products with consistently high sales quantities may deserve higher production priority, provided that demand, ingredient availability and wastage are considered.

### 7. Requirements Identified
CrumbCount should support:
- Order recording and status tracking.
- Sales transaction recording.
- Payment and outstanding balance tracking.
- Product-wise sales analysis.
- Sales channel analysis.
- Comparison of revenue and profitability.
- Separate tracking for made-to-order and advance-batch sales.

### 8. Limitations
Initial observations and hypotheses require validation using actual bakery sales data. High sales quantity does not automatically indicate high profitability or prove that a product's price caused greater demand.





---

**CrumbCount — Every crumb counts. Every decision matters.**
