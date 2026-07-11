# Online Grocery Shopping Platform

A full-stack grocery shopping web application built using the 
MERN Stack as part of my MCA final year project. The goal was 
to build a complete e-commerce experience for grocery shopping 
— from browsing products to placing orders — with a separate 
admin panel to manage everything behind the scenes.

---

## Why I Built This

Grocery shopping apps are something everyone uses in daily life. 
I wanted to build something practical and relatable, while also 
challenging myself to implement real e-commerce features like 
cart management, checkout flow, and order tracking.

---

## What It Can Do

**If you are a Customer:**
- Register and login to your account
- Browse products by category
- Add items to cart and manage quantities
- Place orders with delivery address and payment method
- View your order history and profile

**If you are an Admin:**
- Login to a dedicated admin panel
- Add, update, and delete products and categories
- Manage and track customer orders
- View contact messages from users

---

## Tech Stack

- **Frontend:** React.js, React Router DOM, Axios
- **Backend:** Node.js, Express.js
- **Database:** MongoDB, Mongoose
- **Authentication:** JWT, Bcrypt
- **File Uploads:** Cloudinary, Multer
- **Tools:** Vite, Git, Postman

---

## How to Run This Locally

**Clone the project**
```bash
git clone https://github.com/makadia-deep/Online-Grocery-Shopping.git
```

**Run the backend**
```bash
cd server
npm install
nodemon index.js
```

**Run the frontend**
```bash
cd client
npm install
npm run dev
```

**Set up your .env file in the server folder**

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

---

## What I Learned

- Building a complete e-commerce flow from cart to checkout
- Integrating Cloudinary for image uploads
- Managing authentication and protected routes in React
- Structuring a REST API with multiple models and routes

---

## Built By

This project was collaboratively developed by:

**Mihir Parekh**
- GitHub: [github.com/Mihir-3](https://github.com/Mihir-3)
- LinkedIn: [linkedin.com/in/parekh-mihir](https://linkedin.com/in/parekh-mihir)

**Makadia Deep**
- GitHub: [github.com/makadia-deep](https://github.com/makadia-deep)
- LinkedIn: [linkedin.com/in/deep-makadia-dev](https://www.linkedin.com/in/deep-makadia-dev/)

> We built this as part of our academic journey, aiming to 
> create something that reflects real-world e-commerce 
> development beyond what textbooks cover.
