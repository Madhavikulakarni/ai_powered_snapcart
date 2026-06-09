# AI Powered SnapCart

AI Powered SnapCart is a smart e-commerce platform that combines AI-powered product recommendations, real-time communication, and role-based order management to provide an enhanced online shopping experience. The platform enables customers to shop seamlessly, administrators to manage orders efficiently, and delivery agents to handle deliveries through a dedicated dashboard.

## Live Demo

https://ai-powered-snapcart.vercel.app/

## Key Features

### Customer Features

* User registration and login
* Browse and search products
* Add products to cart
* Place orders securely
* Track order status in real time
* Chat with delivery agents
* Receive AI-powered product recommendations
* Responsive and user-friendly interface

### Admin Features

* Admin login and dashboard
* Manage products and inventory
* View and manage customer orders
* Update order status from:

  * Pending
  * Processing
  * Out for Delivery
  * Delivered
* Monitor platform activities

### Delivery Agent Features

* Delivery agent login
* View assigned delivery orders
* Accept or reject delivery requests
* Update delivery progress
* Real-time communication with customers
* Manage delivery workflow efficiently

### AI Features

* Personalized product recommendations
* Intelligent shopping assistance
* Enhanced product discovery experience
* Recommendation engine based on customer preferences

### Real-Time Features

* Socket.IO based communication
* Instant order status updates
* Real-time customer and delivery agent chat
* Seamless order tracking experience

## Technology Stack

### Frontend

* Next.js
* React.js
* JavaScript
* CSS

### Backend

* Node.js
* Socket.IO

### AI Integration

* AI Recommendation Engine

## Project Structure

```text
ai_powered_snapcart/
├── 1.snapcart/      # Frontend (Next.js)
└── socketServer/    # Backend (Socket.IO Server)
```

## Screenshots

### Home Page

![Home Page](screenshots/home.png)

### User Login

![User Login](screenshots/login.png)

### Product Catalog

![Product Catalog](screenshots/product-catalog.png)

### AI Recommendations

![AI Recommendations](screenshots/ai-recommendations.png)

### Shopping Cart

![Shopping Cart](screenshots/cart.png)

### Customer Order Tracking

![Order Tracking](screenshots/order-tracking.png)

### Admin Dashboard

![Admin Dashboard](screenshots/admin-dashboard.png)

### Order Management

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/ce892fdc-6971-4c19-a566-7afe705ecd8f" />


### Delivery Agent Dashboard

![Delivery Agent Dashboard](screenshots/delivery-agent-dashboard.png)

### Chat Interface

![Chat Interface](screenshots/chat-interface.png)

## Installation

### Frontend

```bash
cd 1.snapcart
npm install
npm run dev
```

### Backend

```bash
cd socketServer
npm install
node index.js
```

## Future Enhancements

* Online payment integration
* Order analytics dashboard
* Advanced AI recommendation models
* Push notifications
* Mobile application support

## Author

Madhavi Kulkarni

GitHub: [https://github.com/Madhavikulakarni](https://github.com/Madhavikulakarni/ai_powered_snapcart)
