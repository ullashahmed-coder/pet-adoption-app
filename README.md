# 🐾 PetAdopt - Serverless Real-time Pet Adoption Platform

A modern, responsive, and serverless web application designed to connect pet lovers with adorable pets looking for a forever home. Built with a focus on real-time data syncing, secure authentication, and a seamless user experience.

## 🚀 Live Demo
[Live Preview Link](https://pet-adoption-app-11812.web.app)

## ✨ Key Features

### For Adopters (Users)
* **Secure Authentication:** User signup, login, and password reset functionality using Firebase Auth.
* **Pet Exploration:** Browse available pets with detailed information (breed, age, vaccination status, behavior, etc.).
* **Adoption System:** Apply for pet adoption with real-time status tracking (Pending, Approved, Rejected).
* **Wishlist:** Save favorite pets to a personal wishlist for future reference.
* **Profile Management:** Update personal details, contact info, and track adoption history.

### For Shelters & Rescuers
* **Shelter Verification:** Apply to become an authorized shelter by submitting necessary details and uploading verification documents (NID/Trade License).
* **Pet Listing:** Authorized shelters can upload and manage new pet profiles.

### For Administrators
* **Centralized Dashboard:** A comprehensive admin panel to manage users, shelters, and adoption requests.
* **Request Verification:** Review and approve/reject shelter applications by verifying uploaded documents.
* **Adoption Management:** Oversee all adoption requests and maintain platform integrity.

## 🛠️ Tech Stack

**Frontend:**
* HTML5
* CSS3 (Custom responsive design)
* JavaScript (ES6 Modules)
* Google Fonts (Poppins, Hind Siliguri)

**Backend (Firebase Ecosystem):**
* **Firebase Authentication:** For secure user management.
* **Cloud Firestore:** NoSQL database for real-time data syncing (Pets, Requests, Users).
* **Firebase Storage:** For secure storage of pet images and shelter verification documents.
* **Firebase Hosting:** For fast and secure global deployment.

## ⚙️ How to Run Locally

Since this is a serverless application, running it locally is very straightforward:

1. Clone the repository:
   ```bash
git clone https://github.com/ullashahmed-coder/pet-adoption-app.git

2. Navigate to the project directory:
cd pet-adoption-app

3. Open `index.html` in your browser or use a local development server (like VS Code Live Server).

*(Note: Ensure your Firebase configuration object in the JavaScript files is correctly set up with your own Firebase project credentials if you wish to connect it to your own database).*

## 👨‍💻 Author
**Ullash Ahmed**
* GitHub: [@ullashahmed-coder](https://github.com/ullashahmed-coder)
