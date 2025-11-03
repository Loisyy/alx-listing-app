The project title: ALX Listing App.

Project Description

ALX Listing App is a modern web application inspired by Airbnb’s property listing interface.
The goal of this project is to build a responsive, reusable, and scalable listing platform using Next.js, TypeScript, and Tailwind CSS.

It showcases a collection of property listings (such as apartments, villas, and beach houses) displayed through reusable UI components like Card and Button.

This project focuses on:

Building clean and maintainable frontend architecture.

Demonstrating component reusability and modular design.

Laying the foundation for integrating real property data or APIs in future iterations.

Project Structure Overview

The project follows a modular structure to keep the code organized, reusable, and easy to maintain:

components/ – Contains all the reusable UI elements used across the application.

common/ – Stores shared components like Card and Button, which can be used in multiple pages.

interfaces/ – Defines all TypeScript interfaces and types, ensuring consistent data structures and better type safety throughout the project (e.g., CardProps, ButtonProps).

constants/ – Holds reusable configuration values, static text, or API URLs used across the app to maintain cleaner code and easier updates.

public/assets/ – Stores all static files such as images, icons, and SVGs.
These assets can be referenced directly in your components (e.g., /assets/placeholder.jpg).

How to Run the Project Locally

Follow these steps to set up and run the project on your local machine:

1️⃣ Clone the Repository
git clone https://github.com/<your-username>/alx-listing-app.git

2️⃣ Navigate into the Project Directory
cd alx-listing-app

3️⃣ Install Dependencies

Make sure you have Node.js and npm installed, then run:

npm install

4️⃣ Run the Development Server

Start the local server with:

npm run dev

5️⃣ Open the App in Your Browser

Visit:
👉 http://localhost:3000

You should see the ALX Listing App homepage displaying sample property cards styled with Tailwind CSS.