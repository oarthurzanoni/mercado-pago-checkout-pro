# Mercado Pago Checkout Pro

A full-stack integration example for Mercado Pago's hosted Checkout Pro flow.

## Project goal

Understand the lifecycle of a payment integration, from creating a checkout preference on the server to redirecting the user from the web client.

## Features

- Create a payment preference on the backend
- Initiate checkout from the frontend
- Keep payment credentials outside the browser
- Separate web and server responsibilities

## Technologies

- **JavaScript**
- **Node.js**
- **React**
- **Mercado Pago SDK**

## What I learned

- Integrating an external payment provider
- Keeping privileged API calls on the server
- Passing checkout identifiers between backend and frontend
- Understanding redirect-based payment flows

## Running locally

Install dependencies in `server` and `web`, configure the Mercado Pago credentials on the server, then start both applications.

## Project status

This is a learning project and is not presented as a production-ready application.
