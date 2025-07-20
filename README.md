# 🎟️ Event Ticket Booking System

A full-stack web application that allows users to browse, book, and pay for event tickets. Built with the **MERN Stack** (MongoDB, Express.js, React.js, Node.js) and integrated with **Razorpay/Stripe** for secure online payments.

---

## 🚀 Features

- ✅ User registration and login (authentication)
- 📅 Browse upcoming events
- 🧾 Book tickets for events
- 💳 Online payment integration (Razorpay/Stripe)
- 📊 Admin panel to manage events and bookings
- 🔐 Secure backend using JWT authentication
- 📬 Email notifications (optional add-on)

---

## 🛠️ Tech Stack

**Frontend:**
- React.js
- Axios
- TailwindCSS / Bootstrap (optional)

**Backend:**
- Node.js
- Express.js
- MongoDB (Mongoose)

**Payment Gateway:**
- Razorpay or Stripe

---

## 📁 Folder Structure


---

## ⚙️ Installation & Setup

### 🔧 Prerequisites
- Node.js
- MongoDB
- Razorpay/Stripe account

### 💻 Clone the repository

```bash
git clone https://github.com/yourusername/event-ticket-booking-system.git
cd event-ticket-booking-system

📦 Backend Setup

cd backend
npm install

Create a .env file in backend/ and add:
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
RAZORPAY_KEY_ID=your_razorpay_key
RAZORPAY_KEY_SECRET=your_razorpay_secret

Start backend server:
npm run dev

🌐 Frontend Setup
cd frontend
npm install
npm start

🧠 Future Improvements
Email ticket confirmation

QR code generation for tickets

Seat selection system

Admin analytics dashboard
