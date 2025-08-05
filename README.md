# Nxt Trendz 🛒

Nxt Trendz is a fully responsive e-commerce web application inspired by Amazon and Flipkart. It includes user authentication, product listings, product details, cart functionality, and secure routing.

## 🔗 Live URL

👉 [https://nxttrenzshoping.ccbp.tech/](https://nxttrenzshoping.ccbp.tech/)

## 🔗 GitHub Repository

👉 [https://github.com/Kalyanpandaga/nxtTrendz](https://github.com/Kalyanpandaga/nxtTrendz)

---

## 🚀 Project Features

### ✅ Authentication

- Login using credentials.
- Redirect to `/` (Home) on successful login.
- Show error message on invalid credentials.
- Redirect unauthenticated users trying to access `/`, `/products`, `/cart`, or `/products/:id` to `/login`.
- Redirect authenticated users accessing `/login` to `/`.

### ✅ Products Page

- List products using API.
- Search by title, filter by category, filter by rating.
- Display `No Products` or `Failure` views when applicable.
- Reset filters with "Clear Filters" button.

### ✅ Product Details Page

- Show product details and similar products.
- Allow quantity increment/decrement.
- Display failure view on error.
- Navigate back to `/products` from error page.

### ✅ Cart Functionality

- Add products to cart with quantity.
- Update quantity using plus/minus buttons.
- Remove single item or all items.
- Show cart summary with total price and item count.
- Show `Empty Cart` view when cart is empty.

---

## 🛠️ Tech Stack

- **Frontend**: React JS
- **Routing**: React Router v6
- **State Management**: React Context API
- **Styling**: CSS3

---

## 🔐 Login Credentials

- **Username**: `rahul`
- **Password**: `rahul@2021`

---

## 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/Kalyanpandaga/nxtTrendz
cd nxtTrendz
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm start
```

---

## 📁 Folder Structure

```
nxtTrendz/
├── public/
├── src/
│   ├── components/     # All React components
│   ├── context/        # Context for Cart Management
│   ├── pages/          # Page Components (Home, Products, Cart, etc.)
│   ├── App.js
│   └── index.js
├── package.json
└── README.md
```

---

## ✨ Highlights

- Fully mobile responsive design 📱
- JWT-based secure login 🔐
- Persistent Cart using local storage 🛍️
- Clean folder structure and reusable components ♻️

---

## 📌 Note

This project is part of the **NxtWave CCBP 4.0** training program and is intended for learning purposes.

---

## 📧 Contact

For any queries, feel free to reach out:

- [Kalyan Pandaga – GitHub](https://github.com/Kalyanpandaga)

---
