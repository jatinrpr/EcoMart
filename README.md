# 🛍️ EcoMart

EcoMart is a full-stack buy & sell marketplace built using Next.js (App Router), MongoDB, and JWT-based authentication.  
It enables users to list products, explore available items, and manage their profiles within a modern and seamless platform.

---

## 🚀 Features

### 👤 Authentication
- Email & password-based sign-up and login  
- Secure authentication using JWT  
- Role-based access control (only owners can modify their listings)  

### 💼 Product Management
- Add products with title, description, price, and image  
- Browse all available listings  
- Product owners can:
  - Edit product details  
  - Mark items as Sold  
  - Delete listings  

### 💬 Communication
- Buyers can express interest via the **Buy** option  
- Sellers receive buyer details via email  
- Final transactions are completed offline  

### 🧑‍💻 Profile Management
- Update name, phone, location, bio, and profile image  
- Data is stored and synced with MongoDB  

---

## 🧱 Tech Stack

| Layer            | Technology |
|------------------|-----------|
| Frontend         | Next.js (App Router), TypeScript, Tailwind CSS, Framer Motion |
| Backend          | Next.js API Routes |
| Database         | MongoDB Atlas |
| Authentication   | JSON Web Token (JWT) |
| Email Service    | Nodemailer |
| Deployment       | Vercel |

---

## ⚙️ Installation & Setup

Follow these steps to run EcoMart locally on your system 👇

### 1️⃣ Clone the Repository  
git clone clone-this-repo  
cd EcoMart  

### 2️⃣ Install Dependencies  
npm install  

### 3️⃣ Create a .env.local File  
In the root folder of your project, create a file named `.env.local` and add the following environment variables 👇  

MONGODB_URI=your_mongodb_connection_string  

JWT_SECRET=your_jwt_secret_key  

EMAIL_USER=your_email_address  

EMAIL_PASS=your_email_app_password  

⚠️ Note: Replace the above values with your own credentials. Do not push this file to GitHub — it should remain private.  

### 4️⃣ Run the Development Server  
npm run dev  

Now open http://localhost:3000 in your browser to see the app running locally 🎉

---
