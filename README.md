# 🛍️ EShop - Premium E-Commerce Platform

A state-of-the-art, full-stack E-Commerce solution built with the **MERN Stack** (MongoDB, Express, React, Node.js). Designed for a premium shopping experience with AI-powered recommendations, localized pricing, and a modern UI.

## 🚀 Live Features

### 👤 User Experience
-   **Secure Authentication**: JWT-based login/register with secure sessions.
-   **User Profiles**: Manage profile details, view order history.
-   **Wishlist & Favorites**: Save items for later.
-   **Smart Search & Filtering**: Filter by Brand, Price, RAM, and more.
-   **Visual Mega Menu**: Icon-based category navigation (Mobiles, Fashion, Beauty, etc.).

### 🛒 Shopping & Checkout
-   **Dynamic Cart**: Real-time state management with Redux/Context.
-   **Stripe Payments**: Secure credit card processing.
-   **Order Management**: Track order status (Processing, Shipped, Delivered).

### 🤖 Intelligent Features
-   **AI Recommendations**: Smart product suggestions on product pages.
-   **Best Sellers & Trending**: Automated highlighting of top products.

### 🎨 Modern UI/UX
-   **Responsive Design**: Mobile-first approach using **Tailwind CSS**.
-   **Theming**: Light/Dark mode support.
-   **Premium Aesthetics**: Glassmorphism, smooth transitions, and high-quality imagery.

### 🛠️ Admin Dashboard
-   **Product Management**: Add, edit, or delete inventory.
-   **Order Control**: Manage customer orders and update delivery statuses.
-   **User Management**: View and manage registered users.

---

## 🛠️ Tech Stack

-   **Frontend**: React.js, Vite, Tailwind CSS, Redux/Context API
-   **Backend**: Node.js, Express.js
-   **Database**: MongoDB (Mongoose)
-   **Payment Gateway**: Stripe
-   **Deployment**: Ready for Vercel/Render/Heroku

---

## 📦 Installation & Setup

Follow these steps to run the project locally.

### 1. Prerequisites
-   Node.js (v14 or higher)
-   MongoDB (Local or Atlas)
-   Git

### 2. Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd ecommerce-platform
```

### 3. Install Dependencies
Install dependencies for both Client and Server.

**Root Directory (Automated Script):**
```bash
npm run install-all
```

**Or Manually:**
```bash
# Server
cd server
npm install

# Client
cd ../client
npm install
```

### 4. Environment Variables (.env)
Create a `.env` file in the `server` folder with the following credentials:

```env
NODE_ENV=development
PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/ecommerce
JWT_SECRET=your_jwt_secret_key_here
PAYPAL_CLIENT_ID=sb (or your credential)
STRIPE_SECRET_KEY=your_stripe_secret_key
```

### 5. Seed Database (Optional)
Populate the database with sample products (Mobiles, Fashion, Electronics, Beauty).

```bash
# From root directory
npm run data:import
```

### 6. Run the Application
Start both Backend and Frontend concurrently.

```bash
# From root directory
npm run dev
```

-   **Frontend**: [http://localhost:5173](http://localhost:5173)
-   **Backend**: [http://localhost:5000](http://localhost:5000)

---

## 🌍 Deployment to GitHub

1.  **Initialize Git**: `git init`
2.  **Add Files**: `git add .`
3.  **Commit**: `git commit -m "Initial commit"`
4.  **Push**:
    ```bash
    git branch -M main
    git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
    git push -u origin main
    ```

---

## 🤝 Contributing
Contributions are welcome! Please fork the repository and submit a pull request.


