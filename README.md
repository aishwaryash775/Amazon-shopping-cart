# 🛒 Amazon Shopping Cart

A React-based e-commerce web application inspired by Amazon’s shopping experience.  
This project demonstrates product listing, category filtering, cart management, and checkout flow using modern React tools.

---

## 🚀 Features

- Product listing on home page  
- Category-wise product filtering  
- Add to Cart functionality  
- Cart page with total price calculation  
- Checkout / Place Order action  
- Responsive UI design  
- Optional category-based video display  

---

## 🧠 Technologies Used

- React.js  
- Vite  
- JavaScript (ES6)  
- React Router DOM  
- Context API  
- HTML5  
- CSS3 / Bootstrap  

---

## 📁 Project Structure
src/
├─ components/
│ ├─ Navbar.jsx
│ ├─ Products.jsx
│ ├─ Trending_Slider.jsx
│ └─ ShopByCategory.jsx
├─ pages/
│ ├─ Cart.jsx
│ ├─ ProductByCategory.jsx
│ ├─ Product_Detail.jsx
├─ context/
│ ├─ DataContext.jsx
│ └─ data.js
├─ App.jsx
├─ main.jsx
└─ index.css


---

## 🛠 Installation & Setup

1️⃣ Clone the repository

git clone https://github.com/aishwaryash775/Amazon-shopping-cart
cd Amazon-shopping-cart2️⃣ Install dependencies
npm install

3️⃣ Run the project
npm run dev

4️⃣ Open in browser
http://localhost:5173

🔀 Routing Overview

/ → Home / Product listing

/cart → Shopping cart

/product/:id → Product details

/product/category/:cat → Products by category

🛒 Cart Management

Global cart state handled using React Context API

Functions used:

Add item to cart

Clear cart

Calculate total amount

🎥 Video Feature (Optional)

Category-based videos can be shown using video URLs mapped to categories in data.js.
This feature is optional and used for UI enhancement.

🧪 Key Learnings

React component structure and reusability

Context API for global state management

Client-side routing using React Router

Debugging import and runtime errors

Handling undefined props safely

📌 Future Enhancements

Backend integration (Node.js / Express)

Database support (MySQL / MongoDB)

Payment gateway integration

Quantity and order history management

📄 Note

This project was built and customized by debugging and enhancing an open-source React repository for learning and portfolio purposes.

👩‍💻 Author

Aishwarya Santosh Shinde
React E-Commerce Project (Amazon Shopping Cart)



