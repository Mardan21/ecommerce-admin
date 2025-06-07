# E-commerce Admin Dashboard

This is the administrative dashboard for managing an e-commerce store. It enables CRUD operations for products and displays customer order data synced with Stripe. Built with **Next.js** and connected to the same backend/database as the `ecommerce-store`.

## 🚀 Features

- Add/edit/delete products with full form validation
- View and manage order data (payment status, order contents)
- Secure backend API routes for server-side operations
- Stripe API integration for payment tracking
- Clean admin dashboard interface

## 🛠️ Tech Stack

- **Frontend/Backend Framework**: Next.js (React, TypeScript)
- **ORM**: Prisma
- **Database**: PlanetScale (MySQL)
- **Payments**: Stripe API
- **Optional**: Zustand (for UI state), Tailwind CSS (if used)

## 🔁 Integration with [`ecommerce-store`](https://github.com/Mardan21/ecommerce-store) — Customer-facing online store with cart and checkout

- Shares the same PlanetScale database with `ecommerce-store`.
- Products created or edited here are reflected in the storefront.
- Orders placed through the store appear in the admin dashboard with Stripe payment metadata.
- Together, these apps simulate a full B2C e-commerce system.

## 📽️ Demonstration

The app is not deployed.  
A walkthrough is available in the same YouTube demo as the store:  
🎥 [Watch the demo](https://www.youtube.com/watch?v=lq6q3VwNKbE&ab_channel=MardanMahmut)

## 📦 Skills Demonstrated

- Backend API route creation (Next.js)
- Database modeling and querying with Prisma
- Stripe payment API integration
- Full-stack CRUD and dashboard UI design
- System design connecting admin and customer-facing interfaces
