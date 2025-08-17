
# 🍔 Food Delivery App

## 📌 Overview

The **Food Delivery App** is a simple web application that allows users to browse a menu, add food items to the cart, and place orders. It is built using **React.js** for the frontend and a **fake JSON server** to simulate backend API requests.

---

## 🛠️ Technologies Used

* **Frontend:** React.js, HTML, CSS, JavaScript
* **Backend (Mock API):** JSON Server
* **State Management:** React Hooks / Context API
* **Tools:** Axios / Fetch API for API calls

---

## ⚙️ Features

* 📋 Browse menu items dynamically fetched from JSON server
* 🛒 Add, remove, and update items in the cart
* 💳 Place orders with total price calculation
* 🎨 Responsive UI with clean design

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/food-delivery-app.git
   cd food-delivery-app
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start JSON Server (for mock API):

   ```bash
   npx json-server --watch db.json --port 5000
   ```

4. Run the React app:

   ```bash
   npm start
   ```

---

## 📈 Future Improvements

* Add user authentication (login/signup).
* Implement real-time order tracking.
* Integrate with a real backend (Node.js/Express + MongoDB).
