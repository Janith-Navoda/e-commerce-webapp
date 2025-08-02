# 🛒 Breezy Fits - MERN eCommerce App
**🌐Live Demo:** [Click here to view the live site](https://e-commerce-webapp-3dx9.vercel.app/)

A **fully functional e-commerce website** built using the MERN stack (MongoDB, Express.js, React.js, Node.js), with modern tools like **Redux Toolkit**, **Tailwind CSS**, and integrations such as **Cloudinary** for image upload and **PayPal** for payment processing.

## 🚀 Features

- User authentication & authorization with JWT
- Product browsing, search & filtering
- Admin dashboard for product and order management
- Shopping cart & order management
- Product image uploads using Cloudinary
- Secure payment integration with PayPal
- Responsive UI styled with Tailwind CSS
- State management using Redux Toolkit + Thunk
- Dummy data seeding for products

---

## 🧪 Tech Stack

| Frontend       | Backend     | Other Integrations  |
| -------------- | ----------- | ------------------- |
| React          | Node.js     | Cloudinary          |
| Tailwind CSS   | Express.js  | PayPal API          |
| Redux Toolkit  | MongoDB     | JWT Authentication  |
| Axios          | Mongoose    | Dotenv              |

---

## 🛠️ Setup Instructions

### ⚙️ Prerequisites

- Node.js & npm
- MongoDB Atlas account
- PayPal Developer account
- Cloudinary account
- Git

### 🔧 Installation

1. **Clone the Repository**

```bash
git clone https://github.com/Janith-Navoda/e-commerce-webapp.git
cd e-commerce-webapp
```

2. **Backend Setup**
```bash
cd backend
mv dotenv .env
# Add the following variables in .env
# MONGO_URI=your_mongodb_uri
# JWT_SECRET=your_jwt_secret
# CLOUDINARY_CLOUD_NAME=your_cloud_name
# CLOUDINARY_API_KEY=your_api_key
# CLOUDINARY_API_SECRET=your_api_secret

npm install
npm run seed  # Seed initial product data
# Expected output: "Product data seeded successfully!"
npm run dev   # Starts backend server on port 9000
```
2. **Frontend Setup**
```bash
cd ../frontend
mv dotenv .env
# Add the following in .env
# VITE_PAYPAL_CLIENT_ID=your_paypal_client_id

npm install
npm run dev   # Starts React app on port 5173
```
## 📁 Project Structure
```bash
├── backend
│   ├── config/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── data/
├── frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── redux/
│   │   └── assets/
└── README.md
```
## 🙌 Contributing
We welcome contributions from the community! Feel free to:

- Fork this repository
- Submit issues
- Open pull requests
  
Let’s build something amazing together!





