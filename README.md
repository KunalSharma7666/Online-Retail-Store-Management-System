# Online Retail Store Management System

An online retail store management system designed to streamline inventory management, enhance customer experience, and provide seamless shopping and checkout processes. The system integrates features like product categorization, loyalty coupon redemption, privilege-based delivery, and more.

---

## Key Features

- **User Management**: Enables secure user registration and login with privilege-based services (Normal/Pro users).
- **Product Browsing**: Customers can explore a wide range of products categorized for ease of navigation.
- **Cart System**: Add, remove, and update items in the cart with automatic cost recalculations.
- **Checkout Process**: Integrates coupons for discounts and calculates delivery speed based on privilege status.
- **Order Tracking**: Keeps track of orders, including delivery status and payment details.
- **Administrator Dashboard**: Simplifies inventory management, order tracking, and stock updates.

---

## Tech Stack

- **Database**: MySQL
- **Programming Language**: SQL, Python
- **OLAP Support**: Advanced queries for revenue analysis and customer insights.
- **Triggers**: Automated actions for cart updates and coupon usage.

---

## Database Design

### Tables and Descriptions

1. **`admin`**: Stores administrator credentials.
2. **`user`**: Manages customer data, including privilege status, contact details, and unique credentials.
3. **`product`**: Stores product details, including price, quantity, and categories.
4. **`cart`**: Tracks items added to a user's cart, including quantity and total cost.
5. **`my_orders`**: Tracks the products in an order.
6. **`order`**: Manages overall order details, including payment, coupon usage, and delivery.
7. **`coupons`**: Stores coupon details with expiry and usage status.
8. **`category`**: Categorizes products for better organization.
9. **`payments`**: Tracks payment methods and addresses.
