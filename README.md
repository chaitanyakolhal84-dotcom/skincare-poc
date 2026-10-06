Skincare POC



A full-stack skincare e-commerce application with a React/Vite frontend and Node.js/Express/MongoDB backend.



Project Structure



skincare-poc/

├── frontend/

└── backend/



Technology Stack

Frontend

React

Vite

JavaScript

CSS

Axios

React Router

Backend

Node.js

Express.js

MongoDB

Mongoose

JWT

bcrypt

CORS

dotenv

Features

Customer

Registration and Login

Product browsing

Shopping Cart

Checkout

Coupon application

Order placement

Order history

Profile

Rewards and referrals

Admin

Admin Dashboard

Product Management

Stock Management

Order Management

Coupon Management

Promotion Management

Home-page Promotion Control

Local System Execution

1\. Start MongoDB



Make sure MongoDB is running on the local system.



2\. Start Backend



Open PowerShell and run:



cd "C:\\Skincare POC\\skincare-poc\\backend"



npm install



node server.js



Backend runs on:



http://localhost:5000



3\. Start Frontend



Open a second PowerShell window and run:



cd "C:\\Skincare POC\\skincare-poc\\frontend"



npm install



npm run dev



Frontend normally runs on:



http://localhost:5173



4\. Open Application



Open the browser and visit:



http://localhost:5173



Application Flow



Browser

↓

React / Vite Frontend

↓

Axios API Service

↓

Express Backend

↓

MongoDB



API



Backend:



http://localhost:5000



API Base:



http://localhost:5000/api



Environment Variables



Create a .env file inside the backend folder.



PORT=5000

MONGO\_URI=mongodb://127.0.0.1:27017/skincare\_poc

JWT\_SECRET=your\_secure\_jwt\_secret



Do not commit .env to GitHub.



Important Commands

Frontend



npm install



npm run dev



Backend



npm install



node server.js



Production Frontend Build



npm run build



npm run preview



Development Flow



React Frontend

↓

Axios API Service

↓

Express Backend

↓

MongoDB



Author



Chaitanya Kolhal

