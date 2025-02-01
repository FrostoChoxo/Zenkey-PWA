# 🛍️ Zenkey – Offline-First E-Commerce Web App

Zenkey is a cutting-edge **offline-first e-commerce application** that provides a seamless shopping experience both **online and offline**. By leveraging **service workers, IndexedDB, and background sync**, Zenkey ensures users can browse products, manage their cart, and even sign up without an internet connection. The app updates and syncs automatically when back online, offering a truly uninterrupted shopping experience.

---

## 🚀 Features

### **🛒 Offline-First Shopping Experience**
- Full access to **products, cart, and user account** even when offline.
  
- Smart caching strategies ensure **smooth page loading**.

### **🔄 Advanced Caching Strategies**
- **Cache First** – Landing & home pages are prioritized for caching.
  
- **Network First** – Profile and order details load from the network but fall back to cache when offline.
  
- **Fallback Pages** – Checkout page displays an **offline-friendly version** to ensure security.

### **🗄️ IndexedDB for Persistent Storage**
- **Cart & Orders** stored locally so users never lose their data.
  
- **Signup Sync Queue** ensures offline sign-ups are processed when back online.

### **🔔 Push Notifications**
- **Offline Checkout Warning** – Notifies users when attempting checkout offline.
  
- **Order Confirmation** – Confirms successful checkout.
  
- **Signup Success** – Alerts users when their offline signup is successfully synced.

### **📶 Background Sync**
- **Syncs offline user sign-ups automatically** when the internet is restored.
  
- Ensures no data loss during network interruptions.

---

## 🏗️ Technologies Used
- **Service Workers** – Offline caching & network fallback strategies.
  
- **IndexedDB** – Persistent browser-based database for cart and order management.
  
- **Background Sync API** – Enables delayed sync for offline actions.
  
- **Push API** – Provides real-time notifications for key actions.

---

## 🔧 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/Zenkey.git

2. **Install Dependencies:**
   ```bash
   npm install

3. **Run the development server:**
   ```bash
   npm start

4. Open in browser
   
   Look up your router's IPv4 address and visit "yourip:8000" (example: 192.168.0.124:8000).

## 🤝 Contributors
- Harsh Goreja
  
- Hiba Gohar
  
- Ashna Nizar
  
- Hana Sherif
