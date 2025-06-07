# CWA – Compare It! (Comparison Web Application)

## 🔍 Overview

**CWA** is a user-friendly comparison web application built to help users make smarter purchase decisions. It allows real-time price comparisons (simulated) across **medicines, cosmetics, food, and travel expenses** using a clean frontend interface built with **vanilla JavaScript, HTML, and CSS**.

Data is served via a **static JSON server** and **Google Apps Script**, simulating live API functionality. The project includes visual insights through **Chart.js**, making it both informative and interactive.

🔗 [Live Project Demo](https://eternalshub.wixstudio.com/cwa-project)

---

## ✨ Key Features

### 1. Real-Time Price Comparison
- Compare structured price data across categories (medicines, food, cosmetics, travel).
- Uses simulated APIs via JSON Server + Google Apps Script.

### 2. Interactive Search, Sort & Filter
- Search by product or brand name.
- Sort results by price (ascending/descending).
- Filter products by exact price.

### 3. Data Visualization
- Uses **Chart.js** to display average prices across platforms via pie charts.

### 4. Category-Based Comparison
- **Medicines**: dosage, quantity, delivery info.
- **Cosmetics**: product grade, brand, pricing.
- **Food**: aggregated pricing from services like Zomato and Swiggy.
- **Travel**: fare simulation from Uber, Ola, Rapido.

### 5. Product Modal View
- Clicking on a row opens a detailed modal view with:
  - Images
  - Delivery time
  - Additional charges

### 6. Pagination & Loading Animations
- Paginated results for usability.
- Smooth transitions with loader animations.

---

## 🛠 Technical Stack

- **Frontend**: HTML, CSS, JavaScript
- **Data Simulation**: Google Apps Script (JSON API), JSON Server
- **Visualization**: Chart.js
- **Hosting**: Static frontend with mock API support

---

## 🔧 Architecture & Workflow

1. **Data Fetch** → Simulated JSON response (Apps Script or JSON Server)
2. **Render** → Table with sort, search, and filter
3. **Enhance** → Charts (Chart.js), modal details, and pagination
4. **User Interaction** → Dynamic updates using vanilla JS (no reload)

---

## 💡 Use Cases

- Compare medicine prices across online pharmacies.
- Simulate and compare ride fares across services.
- Choose budget-friendly cosmetics or food options.
- Visualize cost differences to support better financial decisions.

---

## 🚀 Development Highlights

- 100% frontend implementation — no frameworks used.
- Realistic data handling with filtering, searching, and sorting.
- Modal and chart integration with no external UI libraries.
- Mock API simulation for real-time interactivity.

---

## 📈 Future Scope

- Integrate with real APIs (Zomato, Uber, Practo, etc.).
- Add more categories (electronics, fashion, etc.).
- Implement user login, wishlist, and notification systems.
- Price alert and tracking features.

---

## 📌 Summary

**CWA – Compare It!** is a smart, extensible comparison tool that highlights strong frontend development skills. Despite the absence of real-time APIs, it offers a convincing simulation of a live shopping assistant, showcasing:

- Clean UX/UI
- Effective data manipulation
- Realistic visualization
- Modular and scalable design

---

_This project is ideal for demonstrating frontend capabilities, simulated backend integration, and UX-centric thinking in real-world applications._
