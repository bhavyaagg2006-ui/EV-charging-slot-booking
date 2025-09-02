# ⚡ EV Slot Booking System

A modern web application to book Electric Vehicle (EV) charging slots with real-time availability and a sleek user interface.This project allows users to book EV charging slots easily with a modern UI and firebase integration.

---

## 🔗 Overview
This project is a simple, responsive UI that connects to Firebase to:
- show EV bunks/stations,
- display slot availability,
- allow users to book slots,
- provide an Admin area to add/edit bunks and slots.

---

## 🌟 Features

- 🔐 **User Authentication** – Sign up & log in securely using Firebase.
- 🗺️ **Search Nearby Stations** – Find EV charging bunks with live data.
- 📊 **View Station Details** – Slots, availability & bookings in real-time.
- ⏱️ **Book Charging Slots** – Quick & hassle-free booking process.
- 🛠️ **Admin Panel** – Manage bunks, slots, and bookings.
- 📱 **Responsive UI** – Optimized for both desktop & mobile.

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript, Tailwind CSS
- **Backend/Database:** Firebase Firestore
- **Hosting:** GitHub Pages / Firebase Hosting


## 📂 Folder structure
/css/js/pages|--index.html|--register.html|--login.html|--search_bunk.html|--slot_vacancy.html/dashboards|--admin_dashboard.html|--create_bunk.html|--edit_bunk.html|--manage_bunks.html|--manage_slots.html|--user_dashboard.html/screenshots/README.md/LICENSE

---

## 🚀 Installation & Usage

1. **Clone the repository:**  
```bash
git clone <https://github.com/bhavyaagg2006-ui/EV-charging-slot-booking.git>
```

2. **Open the project folder in VS Code (or any code editor).**

3. **Create a Firebase project:**
-Go to Firebase Console
-Click Add Project → Follow steps to create a new project

4. **Enable Authentication:**
-Navigate to Authentication → Sign-in method
-Enable Email/Password sign-in

5. **Create Firestore Database:**
-Go to Firestore Database → Create Database
-Start in Test Mode
-Create collections

6. **Add Firebase config in your HTML files:**

**// Firebase configuration**
```bash
const firebaseConfig = {
      apiKey: "AIzaSyCZHsXUzuyolRZMzmu9v6tdzuxqe-3tI8U",
      authDomain: "ev-slot-booking-system.firebaseapp.com",
      projectId: "ev-slot-booking-system",
      storageBucket: "ev-slot-booking-system.firebasestorage.app",
      messagingSenderId: "151538578561",
      appId: "1:151538578561:web:d85940a9567f2bc6220980",
      measurementId: "G-FMMD5N6BVE"
    };
```
**// Initialize Firebase**
```bash
firebase.initializeApp(firebaseConfig);
```
7. **Open index.html or login.html in your browser to test the application.

---
## 📸 Screenshots

### 1. Index Page
![Index page](screenshots/index_page.png)

### 2. Register Page
![Register page](screenshots/register_page.png)

### 3. Login Page
![Login page](screenshots/login_page.png)

### 4. User Dashboard
![ User Dashboard](screenshots/ user_dashboard.png)

### 5. Search Bunk
![Search Bunk](screenshots/search_bunk.png)

### 6. Slot Vacancy
![Slot Vacancy](screenshots/slot_vacancy.png)

### 7. Admin Dashboard
![Admin Dashboard](screenshots/admin_dashboard.png)

### 8. Create Bunk
![Create Bunk](screenshots/create_bunk.png)

### 9. Manage Bunk
![Managee Bunk](screenshots/manage_bunk.png)

### 10. Edit Bunk
![Edit Bunk](screenshots/edit_bunk.png)

### 11. Manage Slot
![Manage Slot](screenshots/manage_slots.png)









---

