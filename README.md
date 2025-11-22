# Ecommerce Frontend Design

This repository contains the solution for the **DevelopersHub Corporation Internship Frontend Development Task**. The project focuses on designing and implementing a pixel-perfect, desktop-first eCommerce website based on the provided Figma design.
This project was built using **ReactJS** and **TailwindCSS**, featuring a modular component structure and client-side routing.

## 🚀 Tech Stack

* **Framework:** [ReactJS](https://reactjs.org/)
* **Styling:** [TailwindCSS](https://tailwindcss.com/)
* **Routing:** [React Router DOM](https://reactrouter.com/)
* **Version Control:** Git & GitHub

## 📅 Project Scope & Timeline

This project covers the 3-week internship curriculum culminating in a final submission on **November 28, 2025**.

### **Week 1: Layout & Structure**
* Set up the project environment.
* Implemented the global **Header** (Logo, Search, Menu) and **Footer**.
* Established the directory structure for assets and components.

### **Week 2: Home & Product Listing**
* **Home Page:** Developed the Hero section with banners and Call-to-Action buttons.
* **Product Listing:** Created a grid-based layout for product cards.
* **Advanced Feature:** Implemented a toggle to switch between **Grid View** and **List View** for products.

### **Week 3: Details & Interactivity**
* **Product Details:** Built the individual product view with images, descriptions, and "Add to Cart" functionality.
* **Interactivity:** Added hover effects, navigation logic, and state management.

## ✨ Key Features

* **Desktop-First Design:** Optimized for desktop layouts as per the Figma requirements.
* **Dynamic Navigation:** specific "All Category" button routes users to the Product List.
* **View Toggling:** Users can switch between **Grid** and **List** views on the product listing page.
* **Cart Functionality:** A dedicated Cart page with navigation options to return to Home.
* **Routing:** Seamless transitions between Home, Shop, Product Details, and Cart pages using `react-router-dom`.
* **Clean UI:** Proper use of semantic HTML tags and Tailwind utility classes for spacing and typography.


## 🔗 Navigation Flow

Home Page <br/>
   ↓<br/>
All Categories (Products Page)<br/>
   ↓<br/>
Cart<br/>
   ↑<br/>
Back to Home<br/>
<br/>

## 🛠️ Installation & Setup

To run this project locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/AbubakarAfzal643/ecommerce-frontend-design.git
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd ecommerce-frontend-design
    ```

3.  **Install dependencies:**
    ```bash
    npm install
    ```

4.  **Start the development server:**
    ```bash
    npm run dev
    ```

5.  **Open your browser:**
    The app should run automatically at `http://localhost:3000`.

## 📂 Folder Structure

```text
src/
├── assets/         # Images and static files
├── components/     # Reusable components (Header, Footer, ProductCard)
├── pages/          # Page components (Home, ProductList, ProductDetail, Cart)
├── App.jsx          # Main application component with Routes
└── index.jsx       # Entry point
