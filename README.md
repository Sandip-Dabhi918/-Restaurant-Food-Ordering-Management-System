# Restaurant Food Ordering Management System

A comprehensive, modern food ordering platform built with the MERN stack (MongoDB, Express.js, React, Node.js) featuring real-time order management, payment processing, analytics dashboard, and advanced search capabilities.

## ✨ Features

### 🍽️ Core Functionality

- **Restaurant Management**: Complete CRUD operations for restaurants
- **Menu Management**: Dynamic menu creation and management
- **Order Processing**: Real-time order tracking and status updates
- **Payment Integration**: Secure Stripe payment processing
- **User Authentication**: Auth0-based secure authentication

### 📊 Advanced Features

- **Analytics Dashboard**: Business insights with charts and metrics
- **Advanced Search**: Multi-filter search with real-time results
- **API Documentation**: Interactive Swagger-like API docs
- **Performance Monitoring**: Real-time system health monitoring
- **Order Status Tracking**: Comprehensive order lifecycle management

### 🎨 User Experience

- **Responsive Design**: Mobile-first responsive layout
- **Modern UI**: Shadcn/ui components with Tailwind CSS
- **Real-time Updates**: Live order status and notifications
- **Toast Notifications**: Professional status feedback
- **Dark/Light Mode**: Theme switching capability

---

## 🛠️ Technology Stack

### Frontend

- **React 18.2.0** - Modern React with hooks and concurrent features
- **TypeScript 5.3.3** - Type-safe development
- **Vite** - Fast build tool and development server
- **Tailwind CSS** - Utility-first CSS framework
- **Shadcn/ui** - Modern component library
- **React Query** - Server state management
- **React Router** - Client-side routing
- **React Hook Form** - Form handling with validation
- **Zod** - Schema validation
- **Auth0** - Authentication and authorization
- **Stripe** - Payment processing
- **Lucide React** - Beautiful icons

### Backend

- **Node.js** - JavaScript runtime
- **Express.js** - Web application framework
- **TypeScript** - Type-safe backend development
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling
- **Stripe** - Payment processing API
- **Auth0** - Authentication middleware
- **Cloudinary** - Image upload and management
- **Multer** - File upload handling
- **Express Validator** - Request validation
- **CORS** - Cross-origin resource sharing

### Development Tools

- **ESLint** - Code linting
- **Prettier** - Code formatting
- **Nodemon** - Development server with auto-reload
- **Concurrently** - Run multiple commands simultaneously

---

## 📁 Project Structure

```bash
food-ordering/
├── food-ordering-frontend/          # React frontend application
│   ├── src/
│   │   ├── components/              # Reusable UI components
│   │   │   ├── ui/                  # Shadcn/ui components
│   │   │   ├── EnhancedOrdersTab.tsx
│   │   │   ├── OrderStatusDetail.tsx
│   │   │   ├── AdvancedSearchBar.tsx
│   │   │   └── ...
│   │   ├── pages/                   # Page components
│   │   │   ├── HomePage.tsx
│   │   │   ├── ManageRestaurantPage.tsx
│   │   │   ├── AnalyticsDashboardPage.tsx
│   │   │   └── ...
│   │   ├── api/                     # API integration
│   │   ├── auth/                    # Authentication logic
│   │   ├── config/                  # Configuration files
│   │   ├── forms/                   # Form components
│   │   ├── layouts/                 # Layout components
│   │   ├── lib/                     # Utility functions
│   │   ├── types.ts                 # TypeScript type definitions
│   │   └── AppRoutes.tsx           # Application routing
│   ├── package.json
│   └── vite.config.ts
│
├── food-ordering-backend/           # Node.js backend application
│   ├── src/
│   │   ├── controllers/             # Request handlers
│   │   ├── middleware/              # Custom middleware
│   │   ├── models/                  # MongoDB schemas
│   │   ├── routes/                  # API routes
│   │   └── index.ts                 # Server entry point
│   ├── package.json
│   └── .env.example
│
└── README.md                        # This file
```
