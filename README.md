# 🛍️ EcoMart

EcoMart is a full-stack buy & sell marketplace built using Next.js (App Router), MongoDB, and JWT-based authentication.  
It enables users to list products, explore available items, and manage their profiles within a seamless and modern web platform.

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
  - Mark items as **Sold**
  - Delete listings

### 💬 Communication
- Buyers can express interest via **Buy** action
- Sellers receive buyer details via email
- Final transactions are completed offline

### 🧑‍💻 Profile Management
- Update personal details (name, phone, location, bio, profile image)
- Data is securely stored and synced with MongoDB

---

## 💡 How to Use

### 🧾 For Sellers
1. Navigate to the **Sell** section  
2. Enter product details and upload an image  
3. Product becomes visible to all users instantly  
4. Receive buyer details via email when interest is shown  
5. Mark the product as **Sold** after completing the deal  

### 🛍️ For Buyers
1. Browse products in the **Products** section  
2. Select an item of interest  
3. Click **Buy** to notify the seller  
4. Seller will contact you to finalize the transaction  

---

## 🧱 Tech Stack

| Layer        | Technology |
|-------------|-----------|
| Frontend    | Next.js (App Router), TypeScript, Tailwind CSS, Framer Motion |
| Backend     | Next.js API Routes |
| Database    | MongoDB Atlas |
| Authentication | JSON Web Token (JWT) |
| Email Service | Nodemailer |
| Deployment  | Vercel |

---

## ⚙️ Installation & Setup

Follow these steps to run EcoMart locally:

### 1️⃣ Clone the Repository
```bash
git clone <your-repo-url>
cd EcoMart
