# Health Pal

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Available-brightgreen)](https://health-pal-b2f63.web.app/)

**Health Pal** is a modern, user-friendly React web application built with Vite, Tailwind CSS, DaisyUI, and Firebase. It offers a centralized platform for users to manage their health and wellness, including emergency SOS services, medicine reminders, health tips, doctor consultations, and personalized user profiles.

---

## 📋 Table of Contents

- [Project Overview](#project-overview)  
- [Features](#features)  
- [Technologies Used](#technologies-used)  
- [Setup & Installation](#setup--installation)  
- [Usage](#usage)  
- [Project Structure](#project-structure)  
- [Design & HCI Principles](#design--hci-principles)  
- [Live Demo](#live-demo)  
- [Contributing](#contributing)  
- [License](#license)

---

## 🚀 Project Overview

Health Pal aims to centralize various health-related services into a single platform with an intuitive interface. Users can quickly call emergency services, keep track of medications, receive health tips, book consultations with doctors, and manage their personal health profiles. The app integrates Firebase for authentication and real-time data handling.

---

## ✨ Features

- **User Authentication:** Registration, login, and logout via Firebase Authentication  
- **SOS Emergency Service:** One-click ambulance call with confirmation and history tracking  
- **Medicine Management:** Add, track, and view medicines with reminders and expiry status  
- **Health Tips:** Daily health tips sourced from authentic content  
- **Doctor Consultations:** Schedule virtual or in-person doctor appointments  
- **User Profile:** Manage personal details with image upload and local persistence  
- **Responsive UI:** Fully responsive design optimized for desktop and mobile  
- **Interactive Navigation:** Dynamic navbar and sidebar menus with user state awareness  
- **User Feedback:** Testimonials and statistics to build trust and community  

---

## 🛠 Technologies Used

- **Frontend:** React 19, Vite, React Router DOM 7.2  
- **Styling:** Tailwind CSS 3.4, DaisyUI  
- **Icons:** React Icons  
- **Authentication:** Firebase Authentication  
- **Build Tools:** Vite, PostCSS, Autoprefixer  
- **Linting:** ESLint with React Hooks and React Refresh plugins  

---

## ⚙️ Setup & Installation

1. **Clone the repo**  
   ```bash
   git clone https://github.com/yourusername/health-pal.git
   cd health-pal

2. **Install dependencies**  
   ```bash
   npm install
   ```

3. **Configure Firebase**  
   Replace Firebase config in `firebase.config.js` with your project details.

4. **Run the development server**  
   ```bash
   npm run dev
   ```

5. **Build for production**  
   ```bash
   npm run build
   ```

6. **Preview production build**  
   ```bash
   npm run preview
   ```

---

## 🎮 Usage

- Visit the app on `http://localhost:5173` (or the URL provided by Vite)  
- Register a new user account or login with an existing account  
- Navigate through the app using the sidebar or navbar  
- Use SOS for emergency ambulance requests  
- Add and track medicines with reminder functionality  
- Schedule doctor consultations and manage your profile  

---

## 🗂 Project Structure

```
src/
├── assets/            # Static images and logos (react.svg, vite.svg)
├── components/        # React components (Navbar, Sidebar, Root, etc.)
├── firebase.config.js # Firebase config and initialization
├── main.jsx           # App entry point and router setup
├── App.jsx            # Starter Vite React component (optional)
├── index.css          # Tailwind and custom styles
```

**Key components:**

- `Root.jsx` — Main landing page with welcome, services, feedback, stats, and footer  
- `Login.jsx` & `Register.jsx` — User authentication forms  
- `Home.jsx` — User dashboard after login  
- `Medicine.jsx` — Medicine management interface  
- `Consultation.jsx` — Appointment booking  
- `Sos.jsx` — Emergency SOS interface  
- `Profile.jsx` — User profile management  
- `Sidebar.jsx` & `Navbar.jsx` — Navigation components  

---

## 🧠 Design & HCI Principles

The project follows Human-Computer Interaction (HCI) principles to ensure usability and accessibility:

- **Error Prevention & User Feedback:** Real-time validation and error messages  
- **Consistency & Standards:** Uniform design language and navigation patterns  
- **Cognitive Load Reduction:** Simple workflows and clear affordances  
- **Visibility of System Status:** Loading states, confirmations, and notifications  
- **User Control & Freedom:** Editable profiles, easy navigation, and cancellation options  
- **Responsive Design:** Layouts adapt to various screen sizes and devices  

For detailed development progress and applied theories, see the included [development diary](diary.md).

---

## 🌐 Live Demo

Explore the live application at: [https://health-pal-b2f63.web.app/](https://health-pal-b2f63.web.app/)
