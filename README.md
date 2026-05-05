# 🛒 Greencart Grocery App

A full-stack **MERN Grocery Web Application** with real-world features like authentication, cart system, order management, and online payments.

🚀 **Live App:** https://greencart-grocery-app-vlmk.vercel.app  

---

## 📌 Features

- 🔐 User Authentication (JWT + HTTP-only cookies)
- 🛍️ Browse products by categories
- 🔍 Smart product search
- 🛒 Add to Cart & Manage Cart
- 💳 Online Payment Integration (Stripe)
- 📦 Order Placement (COD + Online Payment)
- 👤 User & Seller Role Management
- ☁️ Image Upload via Cloudinary
- 🌐 Fully Deployed (Frontend + Backend)

---

## 🧠 Key Learnings

- Handling real-world **CORS issues & cookies in production**
- Managing **frontend-backend communication**
- Working with **environment variables in deployment**
- Building scalable APIs using **Node.js & Express**
- Debugging deployment issues on **Vercel**

---

## ⚙️ Tech Stack

**Frontend:**
- React.js
- Tailwind CSS
- Axios

**Backend:**
- Node.js
- Express.js
- MongoDB (Mongoose)

**Other Tools & Services:**
- Stripe (Payments)
- Cloudinary (Image Upload)
- Vercel (Deployment)

---

## 📂 Project Structure


Greencart-Grocery-App/
│
├── client/ # React Frontend
├── server/ # Node.js Backend
├── models/ # MongoDB Models
├── routes/ # API Routes
├── controllers/ # Business Logic
└── middleware/ # Auth Middleware


---

### 🔐 Environment Variables

Create a `.env` file in the root directory:

**Server**  
PORT=4000  
FRONTEND_URL=http://localhost:5173  

**Database ** 
MONGO_URI=your_mongodb_connection  

**Auth ** 
JWT_SECRET=your_secret_key  

**Payments ** 
STRIPE_SECRET_KEY=your_stripe_key  

**Cloudinary  **
CLOUDINARY_NAME=your_name  
CLOUDINARY_API_KEY=your_key  
CLOUDINARY_SECRET_KEY=your_secret_key  

🚀 Installation & Setup  

1️⃣ Clone Repository  
git clone https://github.com/Sanskrity0804/Greencart-Grocery-App  

cd Greencart-Grocery-App  

2️⃣ Install Dependencies  

**Frontend ** 
cd client  
npm install  
npm run dev  

**Backend ** 
cd server  
npm install  
npm start

---


## 🎯 Future Improvements

- 🧾 Order tracking system
- 📊 Admin dashboard analytics
- ❤️ Wishlist feature
- 📱 Mobile responsiveness improvements

---


## 📬 Contact

👩‍💻 **Sanskrity Jaiswal**  
📧 sanskrityjaiswal@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/sanskrity-jaiswal-55a27b252/ 
