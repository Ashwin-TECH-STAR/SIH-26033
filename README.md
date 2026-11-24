# 🌾 SMART INDIA HACKATHON – SIH 26033
# Direct Farmer-to-Consumer Digital Marketplace

---

## 1. WORKSHOP DETAILS

**Workshop Name:** Smart India Hackathon Workshop

**Date:**  20.11.2026

**Reference Number:** 26019039

**Team / Participant Name:** Ashwin M

---

## 2. PROBLEM TITLE

**SIH 26033: Multiple Intermediaries Reduce Farmers' Earnings and Increase Consumer Prices.**

### Problem Creator's Organization
Ministry of Consumer Affairs, Food & Public Distribution

### Theme
Agriculture, FoodTech & Rural Development

---

## 3. PROBLEM DESCRIPTION

Agriculture plays an important role in India's economy. Farmers produce essential food products such as vegetables, fruits, grains and other agricultural goods. However, farmers often depend on multiple intermediaries to sell their products to consumers.

These intermediaries increase the overall cost of agricultural products. As a result, farmers receive lower prices for their products, while consumers are forced to pay higher prices.

The lack of direct communication between farmers and consumers also creates difficulties in identifying market demand, maintaining product availability and arranging transportation.

### Major Problems Identified

1. Multiple intermediaries increase product prices.
2. Farmers receive less profit for their hard work.
3. Consumers pay higher prices for agricultural products.
4. Lack of direct communication between farmers and buyers.
5. Difficulty in predicting market demand.
6. Inefficient transportation and delivery systems.
7. Agricultural products may get wasted due to improper distribution.
8. Farmers have limited access to larger markets.

### Expected Solution

Develop a digital marketplace that:

- Connects farmers and Farmer Producer Organizations (FPOs) directly with consumers and bulk buyers.
- Provides efficient logistics and transportation support.
- Uses Artificial Intelligence for demand forecasting.
- Uses route optimization to improve delivery efficiency.
- Reduces unnecessary intermediaries in the agricultural supply chain.

---

# 4. PROPOSED SOLUTION

## 4.1 Detailed Explanation of the Proposed Solution

We propose an AI-powered digital agricultural marketplace that creates a direct connection between farmers, consumers, retailers and bulk buyers.

The platform acts as a common online marketplace where farmers can register, upload their agricultural products, update prices and receive orders directly from customers.

Consumers can browse available products, compare prices, view product details and place orders through the platform.

The system also includes AI-based demand forecasting to help farmers understand which agricultural products are likely to be required in the market. Logistics support helps coordinate product transportation and delivery.

### Main Features

**1. Farmer Registration**

Farmers can create accounts by providing their basic details, location and contact information.

**2. Product Listing**

Farmers can upload details such as:
- Product name
- Product category
- Quantity available
- Price per kilogram
- Product images
- Harvest or availability date
- Farm location

**3. Direct Buying and Selling**

Consumers can directly purchase agricultural products from farmers without depending on unnecessary intermediaries.

**4. Bulk Buyer Connection**

Retailers, supermarkets, hotels and wholesalers can purchase agricultural products in larger quantities.

**5. AI Demand Forecasting**

Artificial Intelligence analyses previous sales, seasonal trends and market demand to estimate future product requirements.

**6. Logistics Management**

The platform helps coordinate transportation, delivery schedules and product distribution.

**7. Route Optimization**

The system uses location and delivery information to identify efficient delivery routes and reduce unnecessary travel.

**8. Order Tracking**

Farmers and consumers can check order status, including order confirmation, processing and delivery.

**9. Price Transparency**

Farmers can display their selling prices clearly, allowing consumers to understand the cost of products.

## 4.2 How It Addresses the Problem

| Existing Problem | Proposed Solution |
|---|---|
| Multiple intermediaries | Direct farmer-to-consumer connection |
| Low farmer earnings | Better selling opportunities |
| High consumer prices | Reduced unnecessary costs |
| Lack of market information | AI demand forecasting |
| Transportation difficulties | Logistics management |
| Delivery delays | Route optimization |
| Product wastage | Demand-based distribution |

## 4.3 Innovation and Uniqueness

The uniqueness of our solution is the combination of direct agricultural trading, AI-based demand forecasting and logistics optimization in one platform.

Unlike traditional agricultural marketing systems, this platform focuses on connecting farmers directly with buyers while providing intelligent support for product demand and transportation.

The system aims to provide:
- A transparent agricultural marketplace.
- Direct communication between farmers and buyers.
- Intelligent demand prediction.
- Efficient transportation planning.
- Better utilization of agricultural resources.
- Support for individual farmers and FPOs.

---

# 5. TECHNICAL APPROACH

## 5.1 Technologies to Be Used

The project will use modern web development technologies, database management systems and Artificial Intelligence techniques.

### Frontend Technologies

**HTML5**
- Used to create the structure of the website.
- Displays product information, registration forms and dashboards.

**CSS3**
- Used to design attractive and responsive web pages.
- Improves the overall appearance and user experience.

**JavaScript**
- Provides interactive features.
- Helps manage product search, filters and dynamic page updates.

### Backend Technologies

**Python**
- Used for server-side programming.
- Handles application logic and data processing.

**Django Framework**
- Manages user registration and authentication.
- Handles product listings and orders.
- Connects the frontend with the database.

### Database

**MySQL**
- Stores farmer and consumer information.
- Maintains product details and prices.
- Stores order and transaction records.

### Artificial Intelligence and Machine Learning

**Python Machine Learning Libraries**
- Pandas for data processing.
- NumPy for numerical operations.
- Scikit-learn for machine learning models.

AI techniques will be used for:
- Predicting agricultural product demand.
- Analysing historical sales information.
- Identifying seasonal purchasing patterns.
- Supporting efficient product distribution.

### Additional Technologies

- Google Maps API for location and mapping services.
- Git for version control.
- GitHub for source code management.
- REST APIs for communication between system components.

## 5.2 Methodology and Process for Implementation

The project will be developed through the following stages.

### Step 1: User Registration

Farmers, consumers and bulk buyers register on the platform using their basic information.

### Step 2: Farmer Dashboard

Farmers access a dashboard to manage their profiles, upload products and view incoming orders.

### Step 3: Product Management

Farmers add product details, prices, quantities and availability information.

### Step 4: Consumer Dashboard

Consumers access the marketplace to view agricultural products and search for required items.

### Step 5: Product Selection

Consumers select products, choose quantities and add them to their shopping cart.

### Step 6: Order Placement

Consumers confirm their orders, and the system sends the order details to the respective farmers.

### Step 7: Order Management

Farmers receive order notifications and update the order status.

### Step 8: AI Demand Forecasting

The AI module analyses historical sales and seasonal information to predict future demand.

### Step 9: Logistics Management

The system coordinates transportation based on product quantity, delivery location and availability.

### Step 10: Route Optimization

The route optimization module helps identify efficient delivery paths.

### Step 11: Order Tracking

Consumers can monitor their orders until the products are delivered.

### Step 12: Feedback and Reviews

Consumers can provide feedback about product quality and delivery services.

## 5.3 System Architecture

The system consists of five major components:

1. **User Interface:** Provides separate dashboards for farmers, consumers and bulk buyers.
2. **Application Server:** Processes requests and manages business operations using Django.
3. **Database Layer:** Stores user, product, order and delivery information.
4. **AI Module:** Predicts product demand and analyses market trends.
5. **Logistics Module:** Supports transportation planning and route optimization.

### System Workflow

```text
        FARMERS / FPOs
              |
              v
       PRODUCT LISTING
              |
              v
       DIGITAL MARKETPLACE
              |
       +------+------+
       |             |
       v             v
   CONSUMERS      BULK BUYERS
       |             |
       +------+------+
              |

