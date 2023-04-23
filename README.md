# React Responsive, Fullstack, Ecommerce App

This is a full-stack ecommerce app built from scratch using React, Material UI, Stripe, Formik, Yup, Strapi, and Redux Toolkit.

## Front-end

The front-end of the application is built using React and Material UI. The following packages are used in the front-end:

- `@emotion/react` and `@emotion/styled`: These packages are used for styling components with CSS-in-JS.
- `@mui/icons-material` and `@mui/material`: These packages are used to implement Material Design components and icons.
- `@reduxjs/toolkit`: This package is used to manage the global state of the application using the Redux store.
- `@stripe/stripe-js`: This package is used to interact with Stripe API for payment processing.
- `formik`: This package is used for form handling.
- `react-redux`: This package is used to connect the React components with the Redux store.
- `react-responsive-carousel`: This package is used for the image carousel on the product page.
- `react-router-dom`: This package is used for client-side routing.
- `yup`: This package is used for data validation.

## Back-end

The back-end of the application is built using Strapi. The following packages are used in the back-end:

- `@strapi/plugin-i18n` and `@strapi/plugin-users-permissions`: These plugins are used to add internationalization and user permission features to the Strapi backend.
- `better-sqlite3`: This package is used as the database for the Strapi backend.
- `stripe`: This package is used to interact with Stripe API for payment processing.

## Installation and Usage

To install and use the application:

1. Clone the repository
2. Install the dependencies for the front-end by navigating to the `client` directory and running `npm install`
3. Install the dependencies for the back-end by navigating to the `server` directory and running `npm install`
4. Start the Strapi backend by running `npm run develop` in the `server` directory
5. Start the React front-end by running `npm start` in the `client` directory

The application should now be accessible at http://localhost:3000.

## Features

The completed ecommerce app allows users to:

- Browse products on the homepage
- View individual product pages with images, descriptions, and pricing information
- Add products to a cart
- Fill out checkout information through a form
- Process payments using Stripe API

## License

This project is licensed under the MIT License.
