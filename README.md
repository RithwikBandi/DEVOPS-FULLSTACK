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
├── Feb_09 - Personal Finance/
│   ├── backend/
│   │   ├── server.js
│   │   ├── package.json
│   │   └── package-lock.json
│   │
│   └── frontend/
│       ├── src/
│       │   ├── App.js
│       │   ├── App.css
│       │   ├── App.test.js
│       │   ├── Expenses.js
│       │   ├── index.js
│       │   ├── index.css
│       │   ├── logo.svg
│       │   ├── reportWebVitals.js
│       │   └── setupTests.js
│       │
│       ├── package.json
│       └── package-lock.json
│
├── Feb_12 - Personal Finance Tracker/
│   ├── .github/
│   │   └── workflows/
│   │       └── ci.yml
│   │
│   ├── dashboard/
│   │   ├── index.js
│   │   ├── index.test.js
│   │   ├── build.js
│   │   ├── package.json
│   │   └── package-lock.json
│   │
│   ├── expenses/
│   │   ├── index.js
│   │   ├── index.test.js
│   │   ├── build.js
│   │   ├── package.json
│   │   └── package-lock.json
│   │
│   ├── income/
│   │   ├── index.js
│   │   ├── index.test.js
│   │   ├── build.js
│   │   ├── package.json
│   │   └── package-lock.json
│   │
│   ├── build-all.js
│   └── package.json
│ 
├── Feb_16 - Personal Finance Tracker Full Stack/
│   ├── .github/
│   │   └── workflows/
│   │       └── ci.yml
│   │
│   ├── backend/
│   │   ├── app.js
│   │   ├── server.js
│   │   ├── tests/
│   │   │   └── integration.test.js
│   │   ├── package.json
│   │   └── package-lock.json
│   │
│   ├── frontend/
│   │   ├── index.html
│   │   ├── app.js
│   │   ├── package.json
│   │   └── package-lock.json
│   │
│   ├── cypress/
│   │   └── e2e/
│   │       └── finance.cy.js
│   │
│   ├── cypress.config.js
│   ├── package.json
│   └── package-lock.json
│
│
├── Feb_19 - Personal Finance Tracker Docker/
│   ├── Dockerfile
│   ├── .dockerignore
│   ├── server.js
│   ├── package.json
│   ├── package-lock.json
│   ├── .env (ignored in Git)
│   └── .env.production (ignored in Git)
│
├── Feb_23 - Finance Tracker Docker Compose/
│   ├── backend/
│   │   ├── server.js
│   │   ├── Dockerfile
│   │   ├── package.json
│   │   └── package-lock.json
│   │
│   ├── frontend/
│   │   ├── src/
│   │   ├── Dockerfile
│   │   ├── package.json
│   │   └── package-lock.json
│   │
│   └── docker-compose.yml
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

### February 09 — Personal Finance Tracker (Frontend + Backend Integration)

This module demonstrates full stack integration by connecting a React-based frontend with a Node.js and Express backend using RESTful APIs. The application focuses on managing personal expense records and highlights real-world frontend–backend communication patterns.

The backend exposes REST endpoints to fetch and add expense data, while the frontend dynamically renders this data and updates the UI without page reloads.

This lab also involved practical debugging of port conflicts on macOS and reinforced the importance of correct environment setup and service separation.

#### Learning Objectives

- Integrate React frontend with Express backend APIs
- Use RESTful GET and POST requests for data exchange
- Manage application state using React hooks
- Dynamically update UI based on backend responses
- Handle API errors and connectivity issues gracefully
- Understand port conflicts and service isolation on macOS

#### Application Architecture

```text
Browser
   |
React Frontend (Port 3000)
   |
Fetch / Axios API Calls
   |
Express Backend (Port 5001)
   |
In-memory Expense Data Store
```

#### Backend Features

- Express server with CORS and JSON middleware
- REST API endpoints:
  - `GET /api/expenses` – Fetch all expenses
  - `POST /api/expenses` – Add a new expense
- In-memory data storage for simplicity
- Port reconfiguration to avoid macOS system conflicts

#### Frontend Features

- React functional components
- `useEffect` for fetching backend data on load
- Controlled form inputs for adding expenses
- Real-time UI updates without page refresh
- Clean and minimal Apple-inspired UI styling

#### Path

```text
Feb_09 - Personal Finance/
├── backend
│   ├── server.js
│   ├── package.json
│   └── package-lock.json
└── frontend
    ├── src
    │   ├── App.js
    │   ├── Expenses.js
    │   └── App.css
    ├── package.json
    └── package-lock.json
```

#### Expected Output

✓ Default expenses loaded from backend on page load  
✓ New expenses added dynamically  
✓ No page reload during data updates  
✓ Clear separation between frontend and backend  
✓ Proper handling of port conflicts on macOS

---

### February 12 — CI Pipeline for Modular Personal Finance Tracker

This module demonstrates the implementation of a Continuous Integration (CI) pipeline using GitHub Actions for a modular Node.js-based Personal Finance Tracker application. The project is structured into independent modules and tested using a matrix-based CI strategy.

The primary objective of this lab is to simulate a real-world DevOps workflow by validating multiple application modules independently while ensuring automated build execution only after successful test completion.

#### Overview

The February 12 lab focuses on CI pipeline design using GitHub Actions. The application is divided into three isolated modules — Dashboard, Expenses, and Income — each containing its own logic, test cases, and build process.

A matrix strategy is implemented to run module tests across multiple Node.js versions in parallel. The pipeline ensures:

- Independent module testing
- Parallel execution for faster validation
- Controlled build sequencing using job dependencies

#### Learning Objectives

- Understand modular application architecture
- Configure GitHub Actions workflows
- Implement matrix-based CI strategies
- Run parallel jobs for different modules
- Use working-directory within CI steps
- Enforce job dependencies using `needs`
- Automate multi-module build execution
- Ensure build runs only after successful test completion

#### Application Architecture

```text
GitHub Push / Pull Request
        |
GitHub Actions Workflow (ci.yml)
        |
Matrix Strategy
(Node 18 & 20) × (dashboard, expenses, income)
        |
Parallel Test Execution
        |
Build Job (runs only if all tests pass)
```

#### CI Workflow Details

**Trigger Events**

- Push to repository
- Pull requests

**Matrix Configuration**

- Node.js versions: 18 and 20
- Modules tested: dashboard, expenses, income
- Total parallel executions: 6

**Test Phase**

Each module:

- Installs dependencies
- Executes Jest test suite
- Reports independent results

**Build Phase**

- Executes `build-all.js`
- Runs only if all test jobs succeed
- Sequentially builds all modules
- Outputs confirmation logs

#### Expected Output

✓ Independent module test validation  
✓ Parallel execution across Node versions  
✓ Automatic workflow trigger on push  
✓ Build job executed only after successful tests  
✓ Full application build confirmation

#### Path

```text
Feb_12 - Personal Finance Tracker
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

### February 16 — Complete Full Stack Application with CI & E2E Automation

This module represents a complete full stack implementation of the Personal Finance Tracker application, enhanced with automated integration testing, end-to-end (E2E) testing, and CI orchestration.

Unlike previous labs that focused on isolated backend, frontend, or CI modules, this implementation consolidates all layers into a production-style workflow.

#### Overview

The February 16 lab integrates:

- Express.js backend with REST APIs
- Integration testing using Jest & Supertest
- Static frontend consuming backend APIs
- Cypress end-to-end testing
- GitHub Actions CI pipeline
- Automated multi-service startup using concurrently and wait-on

This module simulates a real-world DevOps pipeline where application services are validated across multiple testing layers before completion.

#### Application Architecture

```text
Browser (Port 3000)
        |
Static Frontend (Serve)
        |
Fetch API Calls
        |
Express Backend (Port 5001)
        |
In-Memory Data Store
```

#### Testing Layers Implemented

**1. Integration Testing (Backend)**

- Jest test runner
- Supertest for HTTP endpoint validation
- API verification for:
  - GET /api/dashboard
  - GET /api/expenses
  - POST /api/expenses
  - GET /api/income
  - POST /api/income

**2. End-to-End Testing (Full Stack)**

- Cypress E2E test suite
- Automated validation of:
  - Dashboard loading
  - Adding new expense
  - Adding new income
  - Real-time UI updates
- Headless execution using Electron in CI

**3. CI Automation**

- GitHub Actions workflow
- Automated test execution on push
- Backend integration tests
- Cypress E2E tests
- Parallel service startup using:
  - concurrently
  - wait-on

#### Automation Script

Root-level script enabling one-command execution:

```bash
npm run test:e2e
```

This command:

1. Starts backend server
2. Starts frontend server
3. Waits for frontend availability
4. Executes Cypress headless tests
5. Gracefully shuts down services

#### Expected Output

✓ Fully functional full stack application  
✓ Integration tests passing  
✓ Cypress E2E tests passing  
✓ CI pipeline executing successfully  
✓ Automated multi-service orchestration  

#### Path

```text
Feb_16 - Personal Finance Tracker Full Stack
```

---

### February 19 — Dockerized Personal Finance Tracker

This module demonstrates containerization of a Node.js-based backend application using Docker. The primary objective of this lab is to understand Docker image creation, container lifecycle management, environment-based configuration, and local MongoDB service integration.

Unlike previous labs that focused on CI pipelines and full stack orchestration, this implementation emphasizes application containerization and environment isolation using Docker.

#### Overview

The February 19 lab includes:

- Express.js backend service
- Environment variable management using dotenv
- Separate development and production configurations
- Dockerfile for image creation
- .dockerignore for optimized image builds
- Local MongoDB service integration
- Port mapping and container networking concepts

This module reinforces how applications are packaged into portable containers and executed consistently across environments.

#### Application Architecture

```text
Browser (Port 3000 or 8080)
        |
Docker Container (Node.js App)
        |
Environment Variables (.env / .env.production)
        |
Local MongoDB Service (Port 27017)
```

#### Key Docker Concepts Implemented

- Docker image build using `docker build`
- Container execution using `docker run`
- Port mapping using `-p`
- Environment injection using `--env-file`
- Container inspection using `docker ps`
- Graceful shutdown using `docker stop`
- Service lifecycle control using Homebrew

#### Expected Output

✓ Successfully built Docker image  
✓ Running container accessible via browser  
✓ Environment-based configuration separation  
✓ MongoDB service successfully started and connected via Compass  
✓ Clean container start and shutdown process  

#### Path

```text
Feb_19 - Personal Finance Tracker Docker
```

---

### February 23 — Full Stack Docker Compose Orchestration

This module demonstrates complete full stack container orchestration using Docker Compose. Unlike the previous Docker lab which focused on containerizing a single backend service, this implementation integrates both frontend and backend services into a unified multi-container architecture.

#### Overview

The February 23 lab includes:

- Express.js backend service running in a container
- React frontend application built using a multi-stage Docker build
- Nginx-based production serving of static frontend assets
- Docker Compose orchestration for multi-container networking
- Internal container-to-container communication using service names
- Build-time environment variable injection using ARG
- Resolution of macOS port conflicts through configurable ports

This module simulates a real-world microservice architecture where independent services communicate over an internal Docker network.

#### Application Architecture

```text
Browser (Port 3000)
        |
Nginx Container (Frontend)
        |
Internal Docker Network
        |
Express Container (Backend - Port 5050)
```

#### Key Concepts Implemented

- Multi-stage Docker builds for optimized frontend images
- Container-to-container networking using Docker DNS
- Port mapping between host and container
- Environment-based configuration using build arguments
- Docker Compose service orchestration
- Proper container lifecycle management

#### Expected Output

✓ Backend container successfully running  
✓ Frontend container served via Nginx  
✓ React frontend communicating with backend using service name  
✓ Transactions rendered dynamically on UI  
✓ Clean multi-container orchestration using a single command  

#### Path

```text
Feb_23 - Finance Tracker Docker Compose
```

---

## DevOps Highlights

- Multi-layer testing strategy (Unit + Integration + E2E)
- CI automation using GitHub Actions
- Matrix-based testing strategy
- Service orchestration using concurrently & wait-on
- Headless browser testing in CI
- Automated workflow on push and pull requests

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
