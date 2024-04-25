# Cricket E-Commerce Shopping App
---


## Introduction
---
Welcome to Cricket Weapon, an e-commerce shopping app built using the MERN (MongoDB, Express, React, Node.js) stack and Material-UI (MUI) for the user interface. This project provides both normal user and admin modes, offering a wide range of features to enhance the shopping experience.

![MongoDB](https://img.shields.io/badge/-MongoDB-green) ![Express](https://img.shields.io/badge/-Express-blue) ![React](https://img.shields.io/badge/-React-blue) ![Node.js](https://img.shields.io/badge/-Node.js-green) ![Material-UI](https://img.shields.io/badge/-Material--UI-blue) ![Stripe](https://img.shields.io/badge/-Stripe-blue) ![Mongoose](https://img.shields.io/badge/-Mongoose-green) ![Redux](https://img.shields.io/badge/-Redux-purple) ![Redux-thunk](https://img.shields.io/badge/-Redux--thunk-purple) ![CSS3](https://img.shields.io/badge/-CSS3-blue)
    ## Features

### Normal User Mode

| Feature             | Description                                                  |
| ------------------- | ------------------------------------------------------------ |
| User Authentication | OAuth with JWT for secure user login and registration        |
| Password Reset      | Reset password via email with reset link                     |
| Profile Management  | Update user profile details (email, name, password, picture) |
| Shopping Cart       | Add items to the cart and apply coupon codes                 |
| Product Review      | Logged-in users can review products                          |
| Shipping Options    | Specify shipping area for product delivery                   |
| Order Tracking      | Track the status of orders                                   |
| Payment Gateway     | Secure payment processing via Stripe                         |
| Contact Form        | Contact form for user assistance                             |
| Saved Addresses     | Save multiple shipping addresses                             |
| Advanced Search     | Filter products by price range, category, and rating         |
| State Management    | Global state management with Redux                           |
### Admin Mode

| Feature                 | Description                                        |
| ----------------------- | -------------------------------------------------- |
| Admin Dashboard         | Access to an admin-only dashboard                  |
| User Management         | View and manage users (delete, promote to admin)   |
| Product Management      | Edit and create products, manage stock levels      |
| Review Management       | View and delete product reviews                    |
| Order Management        | View all orders, and can manage them               |
| Role-Based Permissions  | Restrict admin features based on roles             |
| Order Approval Workflow | Set up approval process for Update status of order |

## Upcoming Features

### Normal User Mode

| Feature                 | Description                                 |
| ----------------------- | ------------------------------------------- |
| Wishlist                | Create and manage wishlists for products    |
| Product Recommendations | Receive suggestions for related products    |
| Product Comparisons     | Compare product specifications side by side |
| Social Sharing          | Share favorite products on social media     |

### Admin Mode

| Feature             | Description                                               |
| ------------------- | --------------------------------------------------------- |
| Sales Analytics     | Gain insights into sales trends and popular products      |
| Dynamic Coupons     | Create and manage targeted coupons                        |
| User Analytics      | Track user engagement and activity                        |
| Bulk Product Upload | Upload and update multiple products using CSV             |
| Automated Emails    | Send automated emails for order confirmation and updates  |
| Notification Center | Receive alerts for new orders, low stock, and more        |
| Data Export         | Export data sets (e.g., orders, products) to CSV or Excel |
| Product Bundles     | Create and manage product bundles                         |

## Dependencies and Libraries

### Backend

| Dependency                              | Description                                           |
| --------------------------------------- | ----------------------------------------------------- |
| @babel/plugin-proposal-class-properties | Babel plugin for class properties                     |
| @strapi/provider-upload-cloudinary      | Cloudinary provider for Strapi uploads                |
| bcryptjs                                | Hash passwords before storing                         |
| body-parser                             | Parse incoming request bodies                         |
| cloudinary                              | Cloud storage for images and videos                   |
| cookie-parser                           | Parse Cookie header and populate req.cookies          |
| cors                                    | Enable Cross-Origin Resource Sharing                  |
| crypto                                  | Cryptographic functions for Node.js                   |
| crypto-js                               | JavaScript library for cryptographic operations       |
| dotenv                                  | Load environment variables from a .env file           |
| express                                 | Web application framework for Node.js                 |
| express-fileupload                      | Middleware to handle file uploads in Express          |
| helmet                                  | Secure HTTP headers middleware                        |
| http-proxy-middleware                   | Proxy requests in development                         |
| jsonwebtoken                            | Generate and verify JSON Web Tokens                   |
| jwt-simple                              | Simple JWT encoding and decoding                      |
| mongoose                                | MongoDB object modeling tool                          |
| nodemailer                              | Send email using Node.js                              |
| nodemon                                 | Monitor for changes in source code and restart server |
| react-chartjs-2                         | React wrapper for Chart.js 2                          |
| stripe                                  | Payment processing library                            |
| validator                               | Validate and sanitize user input                      |

### Frontend

| Dependency                  | Description                                                  |
| --------------------------- | ------------------------------------------------------------ |
| @emotion/react              | Emotion library for writing CSS with JavaScript              |
| @emotion/styled             | Styled components using Emotion                              |
| @material-ui/core           | UI components library for Material Design                    |
| @material-ui/data-grid      | Data grid component for Material-UI                          |
| @material-ui/icons          | Material Design icons for React components                   |
| @material-ui/lab            | Additional components and utilities for Material-UI          |
| @mui/icons-material         | Material-UI icons for MUI components                         |
| @mui/material               | Material-UI components library                               |
| @mui/styles                 | Styling solution for Material-UI components                  |
| @stripe/react-stripe-js     | React components for Stripe's client-side JavaScript library |
| @stripe/stripe-js           | Stripe's client-side JavaScript library                      |
| @testing-library/user-event | Utilities for simulating events with Testing Library         |
| axios                       | Promise-based HTTP client for the browser and Node.js        |
| highcharts                  | Interactive JavaScript charting library                      |
| highcharts-react-official   | React wrapper for Highcharts library                         |
| node-sass                   | Sass compiler for Node.js                                    |
| react                       | JavaScript library for building user interfaces              |
| react-alert                 | React component for customizable alerts                      |
| react-alert-template-basic  | Basic template for react-alert                               |
| react-dom                   | Entry point to the React DOM library                         |
| react-helmet                | Manage document head in React                                |
| react-js-pagination         | Pagination component for React                               |
| react-material-ui-carousel  | Carousel component for Material-UI                           |
| react-redux                 | State management library for React                           |
| react-router-dom            | Routing library for React applications                       |
| react-scripts               | Create React apps with no build configuration                |
| redux                       | Predictable state container for JavaScript apps              |
| redux-devtools-extension    | Redux DevTools integration                                   |
| redux-thunk                 | Thunk middleware for Redux                                   |
| styled-components           | CSS-in-JS library for styling React components               |
| swiper                      | Mobile touch slider library                                  |
| web-vitals                  | Library for measuring web performance metrics                |




