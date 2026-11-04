# invoicing-payment-ui

Front end of a small invoicing app: enter the customer's details, add line items, generate an invoice, and send it to the customer by email or SMS. Pairs with [invoicing-payment-be](https://github.com/thienba/invoicing-payment-be).

## Stack

React, Redux with Redux-Saga for the API calls, Formik and Yup for form validation, Ant Design and Tailwind CSS, Axios, SweetAlert2.

## Features

- Customer information form with validation
- Add items in a popup; the invoice totals update as you go
- Invoice preview, then send it by email or SMS through the backend
- Loading state and alerts for every request

## Run

```bash
npm install
npm start          # http://localhost:3000
```

The API address is in `src/utils/configs.js` (default `http://localhost:4000/api/v1`). Start the backend first.
