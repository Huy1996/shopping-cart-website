# Online Shopping Cart

## Introduction
This project is built using the MERN stack (MongoDB, Express, React, and Node.js).
The purpose of this project is to provide a user-friendly platform for online shopping.
<br><br>
This project is containerized using Docker, making it easy to set up and
run locally or in a production environment.

## Technologies Used
### 1. Frontend
The frontend is built using React & Redux, a JavaScript library for building user interface.
It runs on port 3000. The frontend communicate with the backend and retrieve data and display
it to the user.

### 2. Backend
The backend is build using ExpressJS, a Node.js web application framework. It runs on port 4000
and serves as the RESTful API for the frontend. The backend communicates with MongoDB to persit data.

### 3. Database
The database used in this project is MongoDB, a NoSQL document-oriented database.
MongoDB is a highly scalable and flexible database that can be easily integrated with a Node,js application.

### 4. Other
PayPal and Mailgun are used for payment and email services respectively. <br>
AWS S3 Bucket is used for storing pictures related to the products. <br>
Swagger is used for API documentation <br>
__This project is containerized using Docker__


## User stories
As a shopkeeper, I want to:
1. Add, edit and delete products
2. View the list of products and their details
3. Process and manage orders
4. Update the order status
5. View order history

As a shopper, I want to:
1. View all the available products
2. Add, remove items in my cart
3. View all items in my cart
4. Checkout and make a payment
5. Check the order status


## Getting Started
1. Clone the repository to your local machine <br>
> `git clone --recursive https://github.com/Huy1996/shopping-cart-website.git`
2. Navigate to the project directory
> `cd shopping-cart-website`
3. Build the Docker containers.
> `docker-compose build`
4. Start the containers.
> `docker-conpose up`
5. Access the frontend at `http://localhost:3000` and the backend API documentation
at `http://localhost:4000/docs`

Note: To be able to run this app, you need to add `.env` file in the shopping-cart-api 
directory. Below is the requirement variable needed for the env file
> MONGO_ATLAS_PW <br>
> JWT_KEY <br>
> JWT_ADMIN_KEY <br> 
> JWT_SECRET <br>
> PAYPAL_CLIENT_ID <br>
> GOOGLE_API_KEY <br>
> MAILGUN_API_KEY <br>
> MAILGUN_DOMAIN <br>
> accessKeyId <br>
> secretAccessKey <br>