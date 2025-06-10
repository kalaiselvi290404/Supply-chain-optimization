 📁  Supply Chain Optimization

### 🔍 Background
A retail company seeks to:
- Optimize inventory levels
- Improve supplier collaboration
- Reduce stockouts and carrying costs
- Analyze shipment and order trends

### ✅ Solution
A relational database model is used to:
- Track suppliers, products, orders, and shipments
- Execute SQL queries for analysis and optimization

### 🗃️ Database Schema

#### Suppliers Table
- `supplier_id` (Primary Key)
- `supplier_name`
- `contact_person`
- `phone_number`
- `email`

#### Products Table
- `product_id` (Primary Key)
- `product_name`
- `description`
- `unit_price`
- `quantity_in_stock`

#### Orders Table
- `order_id` (Primary Key)
- `product_id` (Foreign Key)
- `supplier_id` (Foreign Key)
- `order_date`
- `quantity_ordered`
- `order_status`

#### Shipments Table
- `shipment_id` (Primary Key)
- `order_id` (Foreign Key)
- `shipment_date`
- `delivery_date`
- `shipping_company`
- `tracking_number`

### 📊 SQL Queries Include

#### 🟢 Basics
- Select suppliers, products, orders, and shipments
- Count products and calculate average price

#### 🟡 Intermediate
- Order quantities by supplier
- Top ordered products
- Products needing restocking

#### 🔴 Advanced
- Revenue per supplier
- Delivery performance
- Seasonal trend analysis
- Forecast future demand

📁 **Dataset Link:** [Click to Access](https://drive.google.com/drive/folders/1ZIkg3-rl1BLdlO4wZiUZV85HMsMCnejk?usp=sharing)
