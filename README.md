# E-Commerce Website

A modern full-stack e-commerce application built with **Spring Boot 3** for the backend and **React + Vite** for the frontend.

## Features

- JWT authentication and user authorization
- Product listing, search, and filtering
- Shopping cart and checkout flow
- Order management and order details
- Wishlist and review support
- Admin dashboard with product, category, order, and user management

## Tech Stack

- Backend: Java 21, Spring Boot 3.2, Spring Security, Spring Data MongoDB
- Frontend: React 18, Vite 5, Tailwind CSS, Zustand
- Database: MongoDB

## Setup

### Backend

```bash
cd backend
# configure backend/.env with your MongoDB URI and JWT secret
./mvnw.cmd spring-boot:run
```

Server runs at `http://localhost:8080`

### Frontend

```bash
cd frontend
npm install
npm run dev
```

App runs at `http://localhost:5173`

## Environment Variables

### Backend (`backend/.env`)

```env
MONGODB_URI=mongodb://localhost:27017/ecommerce
JWT_SECRET=your-secret-key
```

### Frontend (`frontend/.env`)

```env
VITE_API_URL=http://localhost:8080/api
```

## License

This project is licensed under the MIT License.

**Built with ❤️ by the project team.**
