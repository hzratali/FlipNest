# FlipNest

FlipNest is a fully functional e-commerce website built with the MERN stack (MongoDB, Express.js, React.js, and Node.js). The project includes an admin panel for managing products and user interfaces for browsing and purchasing items. Payments are processed through Stripe.

## Features

- **Admin Panel**: 
  - Add, edit, and delete products
  - Manage product details including pricing and descriptions
  - Upload product images to Cloudinary

- **User Interface**:
  - Browse products
  - Search and filter products by category
  - Sort products by price (low to high or high to low)
  - Add products to cart and proceed to checkout

- **Payment Processing**:
  - Secure payment transactions using Stripe

## Technologies Used

- **Frontend**: React.js, Redux, CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Payment Gateway**: Stripe
- **Cloud Storage**: Cloudinary

## Installation

To run FlipNest locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/hzratali/FlipNest.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd flipnest
   ```
   
3. **Install Backend Dependencies**:

   ```bash
    cd backend
    npm install
   ```
   
4. **Install Frontend Dependencies**:

   ```bash
    cd ../frontend
    npm install
   ```
   
5. **Set up environment variables**: 

    - Backend: Create a .env file in the backend directory with the following content:
   ```bash
    MONGODB_URI = 
    TOKEN_SECRET_KEY = 
    FRONTEND_URL = http://localhost:3000
    STRIPE_SECRET_KEY = 
    STRIPE_ENPOINT_WEBHOOK_SECRET_KEY = 
   ```
   
    - Frontend: Create a .env file in the frontend directory with the following content::
   ```bash
    REACT_APP_CLOUD_NAME_CLOUDINARY = 
    REACT_APP_STRIPE_PUBLIC_KEY = 
    REACT_APP_BACKEND_URL = http://localhost:8080
   ```
   
6. **Start the Backend Server**:

   ```bash
    cd backend
    npm start    
   ```
   
7. **Start the Frontend Application**:

   ```bash
    cd ../frontend
    npm start
   ```

## Contributing
  -Feel free to fork the repository and submit pull requests. If you encounter any issues or have suggestions, please open an issue on GitHub
