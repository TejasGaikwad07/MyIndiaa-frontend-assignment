# MERN-Shopping-App

One Stop EShop - A Modern Fullstack E-commerce Website Built with the React, Redux Toolkit, Express, Tailwind CSS, Heroicons, Mongo DB and Payment Gateway.

## Features 

- User Authentication and Registration using Tokens
- Home Page for Product Listing
- Product Listing with Pagination
- Option to Add Item To Cart
- Option to edit User Profile Details
- Ability to pay for orders
- Modern Payment Gateway using Paypal Client SDK


## Run This Application

Following steps are required to run the application:

- Open Terminal

- Clone One Stop EShop Repository

```bash
    git clone https://github.com/TejasGaikwad07/MyIndiaa-frontend-assignment.git
```

- Go to Root Directory of MERN-Shopping-App

- Setup Environment Variables

To run this project, you will need to add the following environment variables to your `.env.example` file for both the backend and frontend folders:

**Backend**:

- `MONGODB_URI`: Your MongoDB URI
- `PORT`: Port for the backend server
- `NODE_ENV`: Node environment (e.g., "development" or "production")
- `PAYPAL_CLIENT_ID`: PayPal client ID
- `SECRET`: Your secret key
- `PRODUCTION_CLIENT_ORIGIN`: Client origin for production
- `DEVELOPMENT_CLIENT_ORIGIN`: Client origin for development

**Frontend**:

- `VITE_NODE_ENV`: Vite Node environment (e.g., "development")
- `VITE_PRODUCTION_BASE_URL`: Production base URL for the frontend
- `VITE_DEVELOPMENT_BASE_URL`: Development base URL for the frontend
- `VITE_PRODUCTION_API`: Production API URL for the frontend
- `VITE_DEVELOPMENT_API`: Development API URL for the frontend

Create these environment variables, save them in respective folders. File name can be `.env`.

- Start One Stop Stop

```bash
  cd backend
  npm run dev

  cd frontend
  npm run dev
```

## Tech Stack

**Frontend:**

- React
- Tanstack Query (React Query)
- Tailwind
- React Paypal SDK
- Redux Toolkit
- React Router DOM

**Backend:**

- Node
- Express
- Mongoose
- MongoDB

**Language Used:**

- Typescript
- Javascript










