# 🐶 Dogs | Social Media for Pets

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://doggoapp.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

**Dogs** is a high-end social networking application dedicated to pet enthusiasts. This platform allows users to create accounts, share their pets' daily lives through photo uploads, interact via comments, and monitor their profile engagement with real-time analytics.

Developed as a deep dive into the **React ecosystem**, this project emphasizes modular architecture, robust state management, and seamless REST API integration.

🔗 **Live Demo:** [doggoapp.vercel.app](https://doggoapp.vercel.app/)

---

## 📸 Interface Preview

<p align="center">
  <img src="https://github.com/user-attachments/assets/83594405-f31c-4256-b505-244e228ec7fc" width="65%" alt="Desktop View" />
  <img src="https://github.com/user-attachments/assets/74421907-ba55-4cdf-8b9f-43dc2ea1e57f" width="28%" alt="Mobile View" />
</p>

---

## 🚀 Technical Features

* **Secure Authentication:** Custom-built login and registration flow utilizing JWT storage and Protected Routes.
* **Dynamic Media Feed:** High-performance photo feed featuring Infinite Scroll and optimized image loading.
* **User Analytics:** Interactive dashboard visualizing post engagement and user stats through custom components.
* **Community Interaction:** Full CRUD capabilities for comments and instant feedback on user interactions.
* **Modern Styling:** Built with **CSS Modules** to ensure encapsulated, maintainable, and collision-free styles.
* **Accessibility & UX:** Mobile-first approach with semantic HTML, focus management, and smooth SVG animations.

## 🛠️ Tech Stack

- **Framework:** [React.js](https://reactjs.org/) (Hooks, Context API, Router)
- **Styling:** CSS Modules
- **API Communication:** Fetch API / REST Patterns
- **Build Tool:** Vite
- **Deployment:** Vercel

## 🧠 Technical Challenges & Learnings

The primary challenge was managing the **Global Authentication State** while ensuring a smooth user experience during asynchronous operations (like photo uploads and real-time comment updates). 

**Key Achievements:**
- Implemented persistent login sessions using browser storage and React Context.
- Optimized performance by handling complex UI states (Loading, Error, Success) across the entire application.
- Mastered the creation of reusable, decoupled components for a scalable codebase.

---

## 💻 Getting Started

### Prerequisites
- Node.js (v18.0.0 or higher)
- npm or yarn

### Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/itsgsantos/dogs.git](https://github.com/itsgsantos/dogs.git)
    ```

2.  **Install dependencies:**
    ```bash
    cd dogs
    npm install
    ```

3.  **Environment Variables:**
    Create a `.env` file in the root directory:
    ```env
    VITE_API_URL=[https://dogsapi.origamid.dev/json](https://dogsapi.origamid.dev/json)
    ```

4.  **Run the application:**
    ```bash
    npm run dev
    ```

---

## 📫 Connect with Me

- **GitHub:** [@itsgsantos](https://github.com/itsgsantos)

---

<p align="center">
  Developed with ⚡ by <strong>Guilherme Santos</strong>
</p>
