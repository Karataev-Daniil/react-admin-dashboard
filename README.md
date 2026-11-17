# ProductDash

Learning project: an admin panel for products, orders and users, built while studying React and TypeScript. There is no backend. The data lives in the browser (localforage), and the users are made-up examples.

## Features

- Dashboard: key numbers, order statuses, sales by category, stock levels and recent activity
- Products: filters by category, status and stock, editing and pagination
- Orders: filter by status, change the status, pagination
- Users: filters by role and status, sorting and profile editing
- Layout works on phones, with its own navigation

## Stack

React 19 · TypeScript · Vite · React Router 7 · CSS Modules · localforage · ESLint

## Run

```bash
npm install
npm run dev       # http://localhost:5173
npm run build
```

## How it is built

Products, orders and users are shared through React Context and saved with localforage. Each section (dashboard, products, orders, users) has its own folder with its pages and components. Types for the data are in `src/data`.

## What I practiced

Tables with filters and pagination, shared state without a library, typed data models, routing with a common layout, and forms for editing records.
