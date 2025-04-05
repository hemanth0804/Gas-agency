# 🔥 Gas Agency Website

## Overview
This is a responsive web application for a gas agency, built using HTML, CSS, and JavaScript. It allows users to book gas online, view services, and access dashboards based on their roles (User/Admin). Firebase handles authentication and data storage.

---

## Features

- User Registration and Login via Firebase Authentication  
- Role-based dashboards (Admin / User)  
- Pop-up forms with input validation  
- Firestore integration to store user metadata  
- Services and About section  
- Responsive and mobile-friendly UI  
- Logout functionality  
- Session-based role checking  

---

## Technologies Used

- HTML  
- CSS  
- JavaScript  
- Firebase Authentication  
- Firebase Firestore  
- Firebase Realtime Database *(optional/future)*

---

## File Structure

```
gas-agency/
│── index.html # Home page with login/register
│── dashboard.html # User dashboard
│── admin.html # Admin dashboard
│── about.html # About us section
│── service.html # Services offered
│── index.css # Stylesheet for UI design
│── firebase-config.js # Firebase configuration file
│── image/ # Folder for media assets
│── README.md # Documentation file
```

---

## How to Use

1. Clone or download the repository.  
2. Add your Firebase config to `firebase-config.js`.  
3. Open `index.html` in any modern web browser.  
4. Register or login as a user or admin.  
5. Navigate through the pages using the navigation bar.  
6. Admins will be redirected to `admin.html` and users to `dashboard.html`.

---

## Functionality

**JavaScript Functions:**

- `firebase.auth().onAuthStateChanged()` – Handles user session  
- `loginUser()` – Logs in an existing user  
- `registerUser()` – Registers a new user  
- `checkUserRole()` – Checks if the logged-in user is Admin or User  
- `logout()` – Logs the user out  
- Form validation and error handling built-in  

---

## Browser Compatibility

- Chrome  
- Firefox  
- Edge  
- Safari  

---


