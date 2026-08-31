# 📱 Product Catalog Web Application (Nice Gadgets)

> **Full-stack styled, pixel-perfect e-commerce application** built with React 18, TypeScript, and SCSS (BEM architecture). It features dynamic product filtering, shopping cart management, favorites tracking, state persistence, and URL query synchronization based on the original Figma Dark Design.

[![Live Demo](https://img.shields.io/badge/Live_Demo-🚀_View_Project-brightgreen?style=for-the-badge)](https://skoulskiy.github.io/ts_react_phone_catalog/)
[![Figma Design](https://img.shields.io/badge/Figma-Design_Reference-blueviolet?style=for-the-badge)](https://www.figma.com/design/WMdJ24eHk4EkSr25mrt7Y2/Phone-catalog--V2--Original-Dark)

---

## 📌 Project Overview
Nice Gadgets is an interactive e-commerce web platform designed for exploring, filtering, and ordering modern devices (smartphones, tablets, and accessories). The project mimics a real-world tech shop experience with immediate UI responses, full state synchronization, and complex routing.

Key engineering highlights include **strict TypeScript typing**, **modular SCSS architecture using BEM methodology**, **URL-driven state management with React Router v6**, and **persistent storage for cart and favorites**.

---

## 💡 Engineering & Architecture Highlights

* **Pure BEM & SCSS Modules**: Encapsulated component styles preventing class collision and style leaks.
* **URL Search Params Synchronization**: All filter parameters, search input queries, sort types, and pagination options stay synchronized with URL parameters for shareable links.
* **Context API & Storage Sync**: Global state handling for Cart and Favourites backed up by `localStorage` persistence.
* **Mobile-First Layout**: Fully fluid and adaptive design optimized for Mobile, Tablet, and Desktop displays.

---

## 🛠️ Tech Stack

| Category | Technology |
| :--- | :--- |
| **Frontend Framework** | React 18 (TypeScript) |
| **Routing & Navigation** | React Router DOM v6 |
| **Styling & Preprocessing** | SASS / SCSS Modules, BEM Methodology, CSS Grid & Flexbox |
| **State Management** | React Context API, Custom Hooks, LocalStorage API |
| **Build Tooling & Deploy** | Vite, Git, GitHub Pages (`gh-pages`) |

---

## 🚀 Key Features

* 🛒 **Cart & Favourites Management**: Add/remove items, update quantities, calculate cart totals, and view active counters in the navbar header.
* 📱 **Product Details Page**: Interactive gallery switcher, color & capacity selectors, dynamic specifications, and "You may also like" recommendation sliders.
* 🔍 **Real-time Search & Filter**: Dynamic search with debouncing, sorting by price/age/title, and custom pagination (4, 8, 16, or All).
* 📱 **Responsive Design**: Pixel-perfect implementation following Figma specs across mobile, tablet, and desktop viewports.

---

## 💻 Local Development Setup

Follow these steps to run the project locally on your machine:

### Prerequisites
* **Node.js**: `v18.x` or higher recommended
* **npm**: `v9.x` or higher

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Skoulskiy/landing_page
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Start the development server:**
  ```bash
   npm start
   ```
4. **Build for production:**
  ```bash
  npm run build
  ```

## 👤 Author & Contact

* **GitHub**: [@Skoulskiy](https://github.com/Skoulskiy)
* **LinkedIn**: [@Ilya-Yaskevych](https://www.linkedin.com/in/ilya-yaskevych-2819b6432/)
