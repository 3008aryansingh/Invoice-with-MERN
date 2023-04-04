# Invoice-with-MERN
Fullstack open source Invoicing application made with (MERN)
Built with the MERN stack (MongoDB, Express, React and NodeJS). Invoice


I am pleased to inform you that the name of this repository has been changed from Arc Invoice to Accountill. There are so many things coming! Stay tuned!!

This is a side project I've been working on. A full stack invoicing application made using the MERN stack (MongoDB, Express, React & Nodejs), specially designed for freelancers and small businesses, but can be used for almost any type of business need. With this application, you can send beautiful invoices, receipts, estimates, quotes, bills etc to your clients. Jump right off the Live App and start sending invoice or download the entire Source code and run it on your server. This project is something I've been working on in my free time so I cannot be sure that everything will work out correctly. But I'll appreciate you if can report any issue.

Key Features

Send invoices, receipts, estimates, quotations and bills via email
Generate and send/download pdf invoices, receipts, estimates, quotations and bills via email
Set due date.
Automatic status change when payment record is added
Payment history section for each invoice with record about payment date, payment method and extra note.
Record partial payment of invoice.
Clean admin dashboard for displaying all invoice statistics including total amount received, total pending, recent payments, total invoice paid, total unpaid and partially paid invoices.
Multiple user registration.
Authentication using jsonwebtoken (jwt) and Google auth

Technologies used

This project was created using the following technologies.

Client
React JS
Redux (for managing and centralizing application state)
React-router-dom (To handle routing)
Axios (for making api calls)
Material UI & CSS Module (for User Interface)
React simple Snackbar (To display success/error notifications)
Cloudinary (to allows users to upload their business logo)
Apex Charts (to display payment history)
React-google-login (To enable authentication using Google)
Server
Express
Mongoose
JWT (For authentication)
bcryptjs (for data encryption)
Nodemailer (for sending invoice via email)
html-pdf (for generating invoice PDFs)
Database
MongoDB (MongoDB Atlas)

Configuration and Setup
In order to run this project locally, simply fork and clone the repository or download as zip and unzip on your machine.

Open the project in your prefered code editor.
Go to terminal -> New terminal (If you are using VS code)
Split your terminal into two (run the client on one terminal and the server on the other terminal)
In the first terminal

cd client and create a .env file in the root of your client directory.
Supply the following credentials
