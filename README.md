# FINAL MODIFICATION PROPOSAL

## 🧠 Purpose and Narrative of Full CRUD System

This final modification upgrades the website into a **Full CRUD (Create, Read, Update, Delete)** system using browser `localStorage`. The goal is to allow users not only to create and view their account data, but also to edit and remove their information, making the website more interactive and user-controlled.

---

## 🔄 How CRUD is Implemented

### ✅ CREATE
Users create an account through the Sign-Up page, where their information (username, password, favorite player, etc.) is stored in `localStorage` as a JSON object.

### 📖 READ
The Profile page retrieves and displays the stored user data using JavaScript, allowing users to view their saved information after logging in.

### ✏️ UPDATE
An "Edit Profile" button is added to the Profile page. When clicked, the user is redirected to an Edit Profile page where the input fields are pre-filled with existing user data. After making changes, clicking "Save Changes" updates the data in `localStorage`, and the updated information is reflected on the Profile page.

### ❌ DELETE
A "Delete Account" button is added to the Profile page. When clicked, a confirmation prompt appears to prevent accidental deletion. Once confirmed, the user’s data is removed from `localStorage`, and the user is redirected to the Home or Sign-Up page.

---

## 🧭 How It Will Be Used

Users can fully manage their accounts without needing a backend server. They can update personal preferences such as their favorite football player and delete their account if they no longer want their data stored. This system simulates a real-world account management experience while remaining fully client-side and compatible with GitHub Pages.

---

## 🧩 Updated Wireframes (CRUD Integration)

The Profile page will include Edit Profile and Delete Account buttons to allow modification and removal of user data. A new Edit Profile page will contain a form with pre-filled user information for updating details. A confirmation prompt will be used before account deletion to ensure that the action is intentional.

---

## ✅ Summary of Improvements

- Added Update functionality through editable forms  
- Added Delete functionality with confirmation system  
- Improved user control over stored data  
- Maintained compatibility with GitHub Pages (no backend required)  
- Completed full CRUD cycle using localStorage  
