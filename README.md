
# 🏫 TransactPro - School Payment Management System


## ✨ Overview

TransactPro is a comprehensive school payment management system that helps educational institutions track, manage, and process student payments efficiently. The system features a modern React frontend with a responsive design and a robust Node.js/Express backend.

## 🚀 Features

### Frontend Features
- 🌓 Dark/Light mode support
- 📱 Responsive design for all devices
- 🔐 Secure authentication system
- 📊 Real-time transaction tracking
- 🏫 School-specific transaction filtering
- 🔍 Advanced search functionality
- 📋 Detailed transaction status view

### Backend Features
- 🔒 JWT-based authentication
- 📝 Transaction management
- 🏢 School-specific data filtering
- 📤 CSV data import capability
- 🔄 Webhook integration
- ✏️ Manual status updates



## 📺 Demo  
[<img src="https://res.cloudinary.com/dwiq4s5ut/image/upload/v1736615227/Screenshot_715_v6lykv.png" alt="Video Icon" width="50" height="50"/>](https://drive.google.com/file/d/1rRWQb6hveufDCwiUwC4ZOk6YNZnsvZFs/view?usp=sharing)  

*Click the image above to watch the demo video.*


## 🖥️ Screenshots

### Landing Page

| **Landing Page** | **Landing Page Dark Mode** |
|-------------------------|-------------------|
| ![Add landing page screenshot here](https://res.cloudinary.com/dwiq4s5ut/image/upload/v1736615227/Screenshot_715_v6lykv.png) | ![Error Message Screenshot](https://res.cloudinary.com/dwiq4s5ut/image/upload/v1736616291/Screenshot_729_kp0eje.png) |


*Modern landing page with feature highlights*

### Login Page  
![Login Page Screenshot](https://res.cloudinary.com/dwiq4s5ut/image/upload/v1736615241/Screenshot_716_unbqzh.png)  
*A clean and user-friendly login page designed for secure and seamless access.*
### Dashboard  
| **Dashboard - Light Mode** | **Dashboard - Dark Mode** |
|-----------------------------|---------------------------|
| ![Dashboard Screenshot - Light Mode](https://res.cloudinary.com/dwiq4s5ut/image/upload/v1736615276/Screenshot_717_obakgo.png) | ![Dashboard Screenshot - Dark Mode](https://res.cloudinary.com/dwiq4s5ut/image/upload/v1736615275/Screenshot_722_yg8lwu.png) |

*A comprehensive dashboard showcasing transaction analytics with clear visualizations for better decision-making. Available in both light and dark modes for improved usability.*

---

### Transaction Status  
| **Transaction Status - Light Mode** | **Transaction Status - Dark Mode** |
|-------------------------------------|-------------------------------------|
| ![Transaction Status Screenshot - Light Mode](https://res.cloudinary.com/dwiq4s5ut/image/upload/v1736615275/Screenshot_721_ado35m.png) | ![Transaction Status Screenshot - Dark Mode](https://res.cloudinary.com/dwiq4s5ut/image/upload/v1736616947/Screenshot_732_d0xjme.png) |

*A detailed transaction status page providing complete insights into transaction histories and statuses, available in both light and dark modes for user convenience.*

---

### School Transactions  
| **School Transactions - Light Mode** | **School Transactions - Dark Mode** |
|---------------------------------------|-------------------------------------|
| ![School Transactions Screenshot - Light Mode](https://res.cloudinary.com/dwiq4s5ut/image/upload/v1736615275/Screenshot_718_dwyc0i.png) | ![School Transactions Screenshot - Dark Mode](https://res.cloudinary.com/dwiq4s5ut/image/upload/v1736616949/Screenshot_734_hhzjxn.png) |

*School-specific transaction listings with advanced filtering options to ensure seamless access to relevant data. Supports both light and dark modes for enhanced user experience.*

---

### Update Status  
| **Update Status - Light Mode** | **Update Status - Dark Mode** |
|--------------------------------|------------------------------|
| ![Update Status Screenshot - Light Mode](https://res.cloudinary.com/dwiq4s5ut/image/upload/v1736615673/Screenshot_723_tz3gig.png) | ![Update Status Screenshot - Dark Mode](https://res.cloudinary.com/dwiq4s5ut/image/upload/v1736617072/Screenshot_736_tpqxhu.png) |

*Users can easily update the status of school transactions in real-time, ensuring accurate tracking and reflection of changes. Both light and dark modes are supported for better accessibility.*


### Error Message Example  
Below is a side-by-side view showcasing the **Initial Phase** feature and an example of an error message:  

| **Inital Phase Page** | **Error Message** |
|-------------------------|-------------------|
| ![Update Status Screenshot](https://res.cloudinary.com/dwiq4s5ut/image/upload/v1736615276/Screenshot_719_lrelw2.png) | ![Error Message Screenshot](https://res.cloudinary.com/dwiq4s5ut/image/upload/v1736616000/Screenshot_726_xcomvq.png) |


## 🛠️ Tech Stack

### Frontend
- ⚛️ React.js
- 🎨 TailwindCSS
- 📍 React Router DOM
- 🔄 Axios
- 🎯 Lucide React Icons
- 🍞 React Toastify

### Backend
- 📦 Node.js
- 🚂 Express.js
- 🗃️ MongoDB with Mongoose
- 🔑 JWT Authentication
- 🔒 bcryptjs
- 📄 CSV Parser

## 🚀 Installation

### Prerequisites
- Node.js (v14+ recommended)
- MongoDB
- npm or yarn

### Frontend Setup
```bash
# Clone the repository
git clone https://github.com/NalagamdinniRaju/School_Payment_Management.git

# Navigate to frontend directory
cd frontend

# Install dependencies
npm install

# Start development server
npm run dev
```

### Backend Setup
```bash
# Navigate to backend directory
cd backend

# Install dependencies
npm install

# Create .env file and add:
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key

# Start server
npm start
```

## 🌐 API Endpoints

### Authentication
```
POST /api/auth/login - User login
```

### Transactions
```
GET /api/transactions - Get all transactions
GET /api/transactions/school/:school_id - Get school transactions
GET /api/transactions/check-status/:custom_order_id - Check status
POST /api/transactions/webhook - Update transaction status
POST /api/transactions/manual-update - Manual status update
```

## 🔐 Environment Variables

### Frontend
```env
VITE_API_URL=https://school-payment-manage-backend.onrender.com
```

### Backend
```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```

## 📱 Responsive Design

The application is fully responsive and works seamlessly across:
- 💻 Desktop
- 💪 Tablet
- 📱 Mobile

## 🔒 Security Features

- JWT Authentication
- Password Hashing
- Protected Routes
- Input Validation
- CORS Configuration

## 🎨 UI Components

- Custom Navigation Bar
- Interactive Dashboard Cards
- Transaction Tables
- Status Indicators
- Search Filters
- Modal Windows
- Loading States
