# Kioko Enterprise - Alcohol Delivery Service

Kioko Enterprise is a web application for a 24/7 alcohol delivery service operating in Coastal Kenya. The platform allows users to browse a wide variety of local and imported beverages, manage their shopping cart, and complete orders through a streamlined checkout process. The project also includes a comprehensive, theme-based mock admin dashboard for managing business operations.

Built with a modern tech stack including React, TypeScript, and Vite, and styled with Tailwind CSS, the application is designed to be fast, responsive, and user-friendly.

## ✨ Features

-   **Dynamic Landing Page**: A visually appealing introduction to the service, featuring a hero slideshow, featured categories, and trending deals.
-   **Product Catalog & Shop**: Browse a comprehensive collection of beverages filtered by category (Whisky, Wine, Beer, Vodka, etc.) or search functionality.
-   **Shopping Cart**: Add products, update quantities, select different product sizes with corresponding prices, and remove items.
-   **Multi-Step Checkout**: A guided checkout process to collect delivery information, select delivery time (ASAP or scheduled), and choose a payment method (M-Pesa, Cash on Delivery, Card).
-   **Admin Dashboard**: A mock "AdminLTE" styled dashboard to visualize business metrics. Features include:
    -   Sales and enrollment overview charts.
    -   Quick access links and recent activity logs.
    -   A complete CRUD interface for managing "Students" (easily adaptable for customers or users).
-   **Authentication**: Mock user login and registration system with a stylish animated interface.
-   **Responsive Design**: Fully responsive layout built with Tailwind CSS, ensuring a seamless experience on desktop and mobile devices.

## 🛠️ Tech Stack

-   **Frontend**: React & TypeScript
-   **Build Tool**: Vite
-   **Styling**: Tailwind CSS
-   **Routing**: React Router DOM v7
-   **Icons**: Lucide React
-   **Charting**: Recharts (for the dashboard)
-   **Linting**: ESLint with TypeScript support

## 📂 Project Structure

The project is organized with a clear and scalable structure. Key directories inside `src/` include:

```
src/
├── components/     # Reusable UI components (Navbar, Footer, etc.)
├── contexts/       # React Context for global state (AuthContext)
├── pages/          # Top-level components for each route (Landing, Shop, Cart, Dashboard)
├── styles/         # Global styles, Tailwind imports, and CSS resets
├── App.tsx         # Main application component with routing and state management
└── main.tsx        # Application entry point
```

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

-   Node.js (v18 or later)
-   npm or a compatible package manager

### Installation

1.  Clone the repository to your local machine:
    ```sh
    git clone https://github.com/annnab-2222/kioko-.2.git
    ```
2.  Navigate to the project directory:
    ```sh
    cd kioko-.2
    ```
3.  Install the required dependencies:
    ```sh
    npm install
    ```

### Running the Application

To start the development server, run the following command. The application will be available at `http://localhost:5173` (or another port if 5173 is in use).

```sh
npm run dev
```

## 📜 Available Scripts

This project includes several scripts to help with development and deployment:

-   **`npm run dev`**: Starts the Vite development server with Hot Module Replacement (HMR).
-   **`npm run build`**: Compiles the TypeScript code and bundles the application for production into the `dist` folder.
-   **`npm run lint`**: Lints the project files using ESLint to check for code quality and errors.
-   **`npm run preview`**: Starts a local server to preview the production build from the `dist` folder.
