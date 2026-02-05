# DevOps & Full Stack Engineering Portfolio

A professionally structured repository showcasing hands-on implementations in full stack development and DevOps engineering, organized chronologically and maintained with production-grade version control practices.

---

## Overview

This repository consolidates multiple full stack and backend engineering modules developed across different sessions. Each module represents a self-contained application, preserved with its complete execution environment to ensure reproducibility, transparency, and ease of review.

The structure reflects a real-world engineering workflow, emphasizing clarity, modularity, and maintainability.

---

## Key Features

- Date-wise modular organization
- Backend and frontend application development
- Node.js and Express-based services
- Database integration using SQLite and MongoDB
- Complete dependency inclusion for reproducible execution
- Clean folder hierarchy with separation of concerns
- Version-controlled development lifecycle

---

## Repository Structure

```text
DEVOPS-FULLSTACK/
│
├── Jan_12/
│   └── ecommerce/
│       ├── src/
│       ├── node_modules/
│       ├── package.json
│       └── package-lock.json
│
├── Jan_19/
│   ├── DEVOPS-JAN-19/
│   │   ├── src/
│   │   ├── public/
│   │   ├── node_modules/
│   │   ├── database.sqlite
│   │   ├── package.json
│   │   └── package-lock.json
│   │
│   └── DEVOPS-UI-JAN-19/
│       ├── src/
│       ├── public/
│       ├── node_modules/
│       ├── database.sqlite
│       ├── package.json
│       └── package-lock.json
│
├── Jan_22/
│   ├── src/
│   ├── node_modules/
│   ├── package.json
│   └── package-lock.json
│
├── Jan_29/
│   ├── public/
│   │   └── index.html
│   ├── src/
│   │   ├── index.js
│   │   ├── App.js
│   │   └── components/
│   │       ├── ProductList.js
│   │       └── ProductCard.js
│   ├── package.json
│   ├── package-lock.json
│   └── README.md
│
├── Feb_02/
│   └── student-marks-card/
│       ├── public/
│       │   └── index.html
│       ├── src/
│       │   ├── App.js
│       │   ├── App.css
│       │   ├── index.js
│       │   └── components/
│       │       ├── StudentCard.jsx
│       │       └── StudentCard.css
│       ├── package.json
│       ├── package-lock.json
│       └── README.md
│
├── Feb_05/
│   └── online_shop/
│       ├── public/
│       │   ├── index.html
│       │   ├── manifest.json
│       │   └── robots.txt
│       ├── src/
│       │   ├── App.js
│       │   ├── App.css
│       │   ├── index.js
│       │   ├── context/
│       │   │   └── CartContext.jsx
│       │   ├── components/
│       │   │   ├── Home.jsx
│       │   │   ├── Home.css
│       │   │   ├── Products.jsx
│       │   │   ├── Products.css
│       │   │   ├── ProductDetail.jsx
│       │   │   ├── ProductDetail.css
│       │   │   ├── Cart.jsx
│       │   │   ├── Cart.css
│       │   │   ├── NavBar.jsx
│       │   │   ├── NavBar.css
│       │   │   ├── Layout.jsx
│       │   │   ├── NotFound.jsx
│       │   │   └── NotFound.css
│       │   └── data/
│       │       └── products.js
│       ├── package.json
│       ├── package-lock.json
│       └── README.md
│
└── README.md

```

---

## Module Details

### January 12 — Application Initialization

This module focuses on initializing a Node.js application with a structured folder layout and managed dependencies. It demonstrates project bootstrapping, dependency resolution, and execution readiness.

**Path**

```text
Jan_12/ecommerce
```

---

### January 19 — Full Stack Application

This module consists of two coordinated applications demonstrating a complete full stack workflow.

The backend application implements routing, controllers, middleware, database interaction, and server configuration.

The UI module integrates with the backend layer, showcasing client-side interaction and presentation logic.

**Paths**

```text
Jan_19/DEVOPS-JAN-19
Jan_19/DEVOPS-UI-JAN-19
```

---

### January 22 — Backend Service with Database Integration

This module implements a backend service with structured routing and database connectivity. It focuses on modular design, data handling, and service initialization.

**Path**

```text
Jan_22
```

---

### January 29 — React Props and State Demonstration

This module demonstrates the fundamental concepts of props and state in React through a simple component-based frontend application. The implementation focuses on understanding parent–child relationships, unidirectional data flow, and dynamic UI updates using state.

#### Overview

The January 29 lab introduces React’s core data-handling mechanisms by building a minimal online shopping interface. The application is designed to clearly separate responsibilities between components, making it easier to understand how data is passed and managed within a React application.

The project strictly follows frontend-only architecture and avoids backend integration to maintain conceptual clarity.

#### Learning Objectives

- Understand React component-based architecture
- Learn the difference between props and state
- Implement parent–child component communication
- Observe dynamic UI updates without page reload
- Understand React’s re-rendering mechanism

#### Application Architecture

```text
Browser
   |
index.js
   |
App.js
   |
ProductList.js (Parent Component – State Holder)
   |
ProductCard.js (Child Component – Props Receiver)
```

---

### February 02 — Student Marks Card (Using Props)

This module demonstrates a React-based Student Marks Card application that clearly illustrates parent–child communication using props.

#### Overview

The February 02 lab focuses on demonstrating unidirectional data flow in React by passing structured student data from a parent component to a reusable child component. The application visually represents student academic details and processes received data inside the child component.

The project follows a frontend-only architecture to ensure conceptual clarity and ease of demonstration during academic evaluation.

#### Learning Objectives

- Understand props-based data transfer in React
- Implement reusable child components
- Demonstrate parent–child communication
- Process and display received props
- Calculate derived values inside child components

#### Application Architecture

```text
Browser
   |
index.js
   |
App.js (Parent Component – Data Holder)
   |
StudentCard.jsx (Child Component – Props Receiver)
```

---

### February 05 — Online Shop with Routing and Nested Components

This module demonstrates a complete single-page application (SPA) implementation using React Router, featuring advanced routing concepts including nested routes, URL parameters, and context-based state management.

#### Overview

The February 05 lab builds a functional online shopping application that showcases modern routing patterns and component composition. The application implements a multi-page experience without page refreshes, demonstrating the power of React Router for creating seamless client-side navigation.

The project implements nested routes for product details, allowing dynamic content rendering based on URL parameters using the `useParams()` hook. A context-based Cart system manages global shopping cart state across multiple components.

#### Learning Objectives

- Master React Router for SPA navigation
- Implement nested routes for hierarchical navigation
- Extract and use URL parameters with `useParams()` hook
- Display product details dynamically based on route parameters
- Manage global state using Context API and useReducer
- Implement cart functionality with state persistence
- Handle 404 error routes with wildcard routing
- Design responsive layouts with navigation components

#### Application Architecture

```text
Browser
   |
index.js
   |
App.js (Router Setup – Route Definitions)
   |
   ├── NavBar (Navigation Component)
   ├── Layout (Page Wrapper)
   └── Routes
       ├── Home (Landing Page)
       ├── Products (Product Listing)
       │   └── ProductDetail (Nested Route – useParams() for :id)
       ├── Cart (Shopping Cart)
       └── NotFound (Wildcard Route – 404 Handler)
```

#### Key Features Implemented

**Routing Configuration**

- Main route definitions for Home, Products, and Cart pages
- Nested route for product details under `/products/:id`
- Wildcard route for handling 404 errors
- Dynamic routing with URL parameters

**Component Structure**

- **Home**: Landing page with welcome content and navigation
- **Products**: Product listing with nested route outlet
- **ProductDetail**: Dynamic component using `useParams()` to fetch product ID from URL
- **Cart**: Shopping cart display with item management
- **NavBar**: Navigation component with active route highlighting
- **Layout**: Wrapper component for consistent page layout
- **NotFound**: 404 error page for undefined routes

**State Management**

- CartContext using createContext and useReducer for global cart state
- Cart actions: ADD, REMOVE, UPDATE_QTY, CLEAR
- Centralized product data in products.js with lookup utility

**Route Hierarchy**

```javascript
<Route path="/" element={<Home />} />
<Route path="/products" element={<Products />}>
  <Route path=":id" element={<ProductDetail />} />
</Route>
<Route path="/cart" element={<Cart />} />
<Route path="*" element={<NotFound />} />
```

#### Technical Implementation

**React Router v7 Dependencies**

- BrowserRouter for client-side routing
- Routes and Route for route definitions
- Link and NavLink for navigation
- Outlet for rendering nested routes
- useParams for extracting URL parameters
- useLocation for detecting current route

**Context-Based Cart Management**

- useReducer for complex state logic
- Dispatch actions for cart modifications
- Context Provider wrapping entire application
- useCart custom hook for consuming cart context

**Dynamic Product Details**

- useParams() hook extracts product ID from URL
- getProductById() utility function for product lookup
- Fallback UI for non-existent products
- Price formatting using Intl API

#### Expected Output

✓ Multi-page SPA with seamless navigation  
✓ Nested route functionality with dynamic product details  
✓ URL parameters correctly parsed and displayed  
✓ Global cart state accessible across all components  
✓ Responsive design with navigation feedback  
✓ 404 error handling for undefined routes

**Path**

```text
Feb_05/online_shop
```

---

## Execution Instructions

```bash
cd <module-path>
npm install
npm start
```

All required dependencies are included within each module to ensure consistent execution across environments.

---

## Technology Stack

- Node.js
- Express.js
- React.js
- JavaScript (ES6+)
- SQLite
- MongoDB
- npm
- Git & GitHub

---

## Engineering Practices

- Modular architecture
- Separation of application layers
- Explicit dependency management
- Reproducible environments
- Clean commit history
- Scalable folder design

---

## Maintainer

Rithwik Bandi  
Hall Ticket No: **2303A52330**

---

## Notes

This repository serves as a comprehensive engineering portfolio, reflecting iterative development, structured problem-solving, and practical implementation of modern full stack and DevOps concepts.

**DevOps & Full Stack Lab Work**
