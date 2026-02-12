# 🚗 Car Rental - Vehicle Discovery Platform

A modern, high-performance web application designed for browsing and filtering an extensive database of vehicle models. This project focuses on delivering a seamless user experience with fluid animations, robust type safety, and a responsive interface.

## 🚀 Key Features

* **Advanced Filtering:** Filter vehicles by make, year, and fuel type using dynamic search criteria.
* **Fluid Motion:** Enhanced UI/UX with smooth transitions and interactive elements powered by **Framer Motion**.
* **Efficient Pagination:** Seamless navigation through large datasets using **React Paginate**.
* **Dynamic Data Fetching:** Real-time data integration with external APIs via **Axios**.
* **Fully Responsive:** Optimized for a flawless experience across mobile, tablet, and desktop devices.
* **Type Safe:** Built with **TypeScript** to ensure code reliability and maintainability.

---

## 🛠️ Tech Stack

| Technology | Purpose |
| :--- | :--- |
| **React** | UI Library |
| **TypeScript** | Static Typing & Code Quality |
| **Tailwind CSS** | Utility-first Styling |
| **Framer Motion** | Production-ready Animations |
| **Axios** | API Requests |
| **React Router** | Client-side Routing |
| **React Select** | Accessible Select Inputs |

---

## 📊 Data Source

The application utilizes the **OpenDataSoft** public database to provide comprehensive vehicle information:
🔗 [All Vehicles Model API](https://public.opendatasoft.com/explore/dataset/all-vehicles-model/information/?sort=year)

##📁 Project Architecture
Plaintext
src/
├── components/     # Reusable UI elements (Cards, Navbar, Filters)
├── hooks/          # Custom React hooks
├── services/       # API configuration and service layers
├── types/          # TypeScript interfaces and global types
├── pages/          # Main application views
└── utils/          # Utility functions and constants
