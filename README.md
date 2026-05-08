🛍️ ShopBot – AI Powered WhatsApp Commerce Platform

📌 Overview

ShopBot is an intelligent AI-powered WhatsApp eCommerce platform designed to transform traditional online shopping into a conversational commerce experience directly inside WhatsApp.

The platform allows users to browse products, search using natural language, receive AI-powered personalized recommendations, perform image-based product search, manage cart and wishlist, place orders, generate invoices, and complete payments — all without leaving WhatsApp.

Unlike traditional eCommerce applications, ShopBot focuses on conversational shopping, making the shopping experience faster, simpler, and more interactive.

---

🎯 Problem Statement

Modern eCommerce platforms require users to:
- Install applications
- Create accounts
- Navigate complex interfaces
- Search manually through large catalogs

This creates friction for users.

ShopBot solves this problem by enabling:
- Shopping directly from WhatsApp
- AI-powered conversational search
- Personalized product recommendations
- Image-based product discovery
- Seamless checkout experience

The goal is to create a smart commerce assistant capable of understanding user interests and improving shopping experience over time.

---

🚀 Key Features

🧠 AI Powered Recommendation Engine

ShopBot tracks:
- Browsing history
- Product categories viewed
- Product interests
- Wishlist behavior
- Previous purchases

Using this information, the system generates personalized product recommendations for every user.

Example:
- A user interested in finance books gets finance recommendations.
- Another user browsing self-help products receives self-help suggestions.

This creates a personalized shopping experience for every customer.

---

📷 AI Image-Based Product Search

Users can upload product images directly inside WhatsApp.

The system:
1. Analyzes uploaded image
2. Detects object/product category
3. Searches similar products
4. Returns matching products automatically

This feature simulates a "Google Lens for Shopping" experience inside WhatsApp.

---

💬 Conversational Commerce

Users can:
- Browse categories
- Open subcategories
- View products
- Add/remove products
- Checkout
- Track orders

using simple chat interactions.

No website or mobile application is required.

---

🛒 Smart Shopping Features

Product Catalog
- Electronics
- Clothing
- Grocery
- Shoes
- Bags
- Makeup
- Books
- Home Decor
- Cooking Utensils

---

Smart Search

Users can search naturally like:

```txt
show shoes under 2000
best finance books
cheap bags
recommend phones


User (WhatsApp)
        │
        ▼
WhatsApp Cloud API
        │
        ▼
Node.js Express Server
        │
 ┌───────────────┐
 │ Business Logic│
 └───────────────┘
        │
 ┌───────────────┐
 │ AI Services   │
 └───────────────┘
        │
 ┌───────────────┐
 │ MongoDB       │
 └───────────────┘
        │
 ┌───────────────┐
 │ Razorpay API  │
 └───────────────┘


 # Clone repository
git clone <repository-url>

# Move into project folder
cd Ecommercebot

# Install all dependencies
npm install

# Install specific modules manually (if needed)
npm install express
npm install mongoose
npm install dotenv
npm install razorpay
npm install node-fetch
npm install pdfkit

# Start MongoDB
mongod

# Run project
npm start

# OR run directly
node server.js


# Create package-lock.json again
npm install --package-lock-only
