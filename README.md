# FinalFoodDeliveryAppPublic
🍔 Food Ordering App
A full-stack food ordering application with separate user and admin portals. The app allows users to browse food items, manage their cart, place orders with Razorpay payment integration, and lets admins manage food items and view orders. The app also supports image uploads using AWS S3 and includes JWT-based authentication.

🛠 Tech Stack

Frontend

React.js (Vite)
Tailwind CSS
Axios
React Router
JWT Auth (localStorage)
Razorpay (Test Mode)

Backend

Java Spring Boot
MongoDB (NoSQL)
Spring Security + JWT
AWS S3 for image upload
Lombok, Spring Data, Spring Web

🔐 Authentication

JWT-based Auth for Users and Admins.
Tokens are stored in localStorage.
Role-based access control for frontend routing and backend APIs.

💳 Payment Integration

Razorpay is integrated in test mode.
Users can place orders and simulate payments.

☁️ Image Upload

Admins can upload food images which are stored in AWS S3.
Uploaded image URL is saved in MongoDB and shown in the app.

⚙️ Features

👤 User Side
Sign up / Log in
Browse food items
Search + filter by category
Add to cart / Remove from cart
Place order with Razorpay
View past orders

🛠 Admin Side
Admin login
Add/edit/delete food items
Upload images
View all orders placed by users

🚀 How to Run

Prerequisites
Node.js + npm
Java 17+
MongoDB
AWS S3 Bucket
Razorpay test keys

📦 Deployment 

Frontend on Vercel / Netlify
Backend on Render / Railway / AWS
MongoDB Atlas for cloud DB
AWS S3 for production image storage

🙌 Conclusion
This Food Ordering App showcases a complete full-stack implementation with modern technologies, role-based access, secure payments, and cloud integration. It's scalable, responsive, and designed to provide a seamless experience for both users and admins.
