FINAL MODIFICATION PROPOSAL
🧠 Purpose and Narrative of Full CRUD System

This final modification upgrades the website into a Full CRUD (Create, Read, Update, Delete) system using browser localStorage. The goal is to allow users not only to create and view their account data, but also to edit and remove their information, making the website more interactive and user-controlled.

🔄 How CRUD is Implemented

1. CREATE 
Users create an account through the Sign-Up page, where their information (username, password, favorite player, etc.) is stored in localStorage as a JSON object.

2. READ 
The Profile page retrieves and displays the stored user data using JavaScript. This allows users to view their saved information anytime they log in.

3. UPDATE 

An “Edit Profile” button will be added to the Profile page.

When clicked, the user is redirected to an Edit Profile page (or editable form section).

The form fields are pre-filled with the user’s current data.

After editing, clicking “Save Changes” updates the data in localStorage.

The Profile page will automatically reflect the updated information.

4. DELETE (New Feature)

A “Delete Account” button will be added to the Profile page.

When clicked, a confirmation prompt appears to prevent accidental deletion.

Once confirmed, the user’s data is removed from localStorage.

The user is redirected to the Home or Sign-Up page after deletion.

🧭 How It Will Be Used

Users can manage their own accounts fully without needing a server.

They can update personal preferences (e.g., favorite player).

They can delete their account if they no longer want their data stored.

This simulates a real-world account system while staying client-side only.

🧩 Updated Wireframes (CRUD Integration)
📄 Profile Page (Updated)
-----------------------------------
|        NAVIGATION BAR           |
-----------------------------------
|         USER PROFILE           |
| Username: [JohnDoe]            |
| Favorite Player: [Messi]       |
|                               |
| [ Edit Profile ]               |
| [ Delete Account ]             |
-----------------------------------
📄 Edit Profile Page (New)
-----------------------------------
|        NAVIGATION BAR           |
-----------------------------------
|        EDIT PROFILE            |
| Username:        [__________]  |
| Password:        [__________]  |
| Favorite Player: [__________]  |
|                               |
| [ Save Changes ]               |
| [ Cancel ]                     |
-----------------------------------
📄 Delete Confirmation (Popup)
-------------------------------
|   Confirm Deletion          |
| Are you sure you want       |
| to delete your account?     |
|                             |
| [ Yes, Delete ]  [ Cancel ] |
-------------------------------
✅ Summary of Improvements

Added Update functionality through editable forms

Added Delete functionality with confirmation system

Improved user control over data

Maintained compatibility with GitHub Pages (no backend required)

Completed full CRUD cycle using localStorage
