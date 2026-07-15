# Global-Ecommerce-Profitability-Fulfillment-Intelligence-System
A global online retailer operating across 20 countries analyzes how customer segments, product categories, discounts, shipping costs, and payment methods impact sales and profitability.

The goal was to build a database,data warehouse, and gain business insights.

Dataset overview: A kaggle dataset, has about 2,000 transactions, from 5 global regions and 20 countries.

### Business Insights
1. Profitability is not driven by sales
    High sales do not always mean high profit
    Shipping cost can reduce profitabilit
2. Regional Differences Matter
    Customer behavior varies across regions
     Payment preferences differ by market
3. Discounts Requires Strategic Management
    Discounts may increase order volume
    Aggressive discounts weaken profitability
		
### Business Rules		
	1. Customer Rules	
		>  Each customer belongs to one customer segment
		>  A customer segment can include many customers
		>  Customer segments include Consumer, Corporate, and Home Office
		>  Each customer is associated with one country
		>  Customer names are not unique >  Customer_ID required
		
	2. Geography Rules	
		>  Each country belongs to one region
		>  A region includes multiple countries
		>  Regions: North America, Europe, Asia Pacific, Middle East & Africa, South America
		
	3. Product Rules	
		>  Each product belongs to one product category
		>  A category includes multiple products
		>  Product categories: Technology, Furniture, Office Supplies, Clothing & Accessories
		>  Product names are not unique >  Product_ID required
		
	4. Order Rules	
		>  Each order has a unique Order_ID
		>  Each order is placed by one customer
		>  One customer can place multiple orders
		>  Each order occurs on one date
		>  Each order uses one payment method
		
	5. Order Line Rules	
		>  Each order contains at least one product
		>  One product can appear in multiple orders
		>  Each order line records quantity, price, discount, sales, shipping, profit
		>  Quantity >  0
		>  Discount between 0%–30%
		>  Total_Sales = Quantity × Unit_Price × (1 − Discount)
		>  Profit includes discount and shipping impact
		
	6. Payment Rules	
		>  Each order uses one payment method
		>  Payment methods: Credit Card, PayPal, Bank Transfer, Cash on Delivery
		>  Payment method can be analyzed by region and segment
		
	7. Shipping Rules	
		>  Shipping cost depends on region and quantity
		>  Each order line includes shipping cost
		>  Higher shipping cost reduces profit
		>  Assumption: Each region operates its own fulfillment center<img width="512" height="725" alt="image" src="https://github.com/user-attachments/assets/591751af-545b-4d16-96ef-d2c2f9206997" />

