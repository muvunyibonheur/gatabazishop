# Organic Shop Backend

## Overview
This is the backend part of the Organic Shop e-commerce application. It is built using Node.js and Express, providing a simple API to serve data to the frontend.

## Setup Instructions

1. **Clone the repository**
   ```
   git clone <repository-url>
   cd organic-shop/backend
   ```

2. **Install dependencies**
   ```
   npm install
   ```

3. **Run the server**
   ```
   npm start
   ```

   The server will start on `http://localhost:5000`.

## API Endpoints

- **GET /api/products**
  - Description: Retrieves a list of products available in the shop.
  
- **GET /api/contact**
  - Description: Retrieves contact information for the shop.

## Folder Structure

- `src/app.js`: Entry point of the application, sets up the Express server.
- `src/routes/index.js`: Defines the API routes.
- `src/controllers/index.js`: Contains the business logic for handling requests.