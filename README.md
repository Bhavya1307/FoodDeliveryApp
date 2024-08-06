# Full Stack Food Delivery Website

## Project Overview

This project is a complete Full Stack Food Delivery Website built with React JS, MongoDB, Express, Node JS, and Stripe. It includes a frontend website, an admin panel, and a backend server. The website allows users to create accounts, log in, add food items to their cart, and place orders with online payments via the Stripe payment gateway. Additionally, it includes features for updating the order status.

## Features

- **User Authentication:** Users can create accounts and log in to the food order website.
- **Shopping Cart:** Users can add food items to their cart and place orders.
- **Online Payment:** Integration with Stripe payment gateway for processing online payments.
- **Order Status:** Users can view and update the status of their orders.
- **Admin Panel:** Admin users can manage the food items, orders, and user accounts.

## Tech Stack

- **Frontend:** React JS
- **Backend:** Node JS, Express
- **Database:** MongoDB
- **Payment Gateway:** Stripe

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Bhavya1307/FoodDeliveryApp.git
    cd root
    ```

2. **Install dependencies for both client and server:**
    ```bash
    cd food-del/frontend
    npm install
    cd ../backend
    npm install
    cd ..admin
    npm install
    ```

3. **Set up environment variables:**
   - Create a `.env` file in the `server` directory and add the following:
    ```env
    JWT_SECRET="YOUR JWT_SECRET"
    STRIPE_SECRET_KEY="YOUR STRIPE KEY"
    ```

4. **Run the application:**
    - **Client:**
      ```bash
      cd client
      npm start
      ```
    - **Server:**
      ```bash
      cd server
      npm start
      ```

## Usage

1. **Frontend:** Access the frontend at `http://localhost:5173`.
2. **Backend:** The backend server runs on `http://localhost:4000`.
3. **Admin:** The admin side runs on `http://localhost:5174`.

## Contributing

We welcome the contributions. Please fork the repository and send pull request.

## Acknowledgements

- React JS
- Node JS
- Express
- MongoDB
- Stripe

## Contact

For any inquiries or feedback, feel free to reach out at bdp9834@gmail.com.
