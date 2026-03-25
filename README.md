# 🔐 Professional Password Generator

A sleek, fast, and highly customizable password generator built with **React**, **Tailwind CSS**, and **Vite**. This project focuses on efficient state management and optimized performance using modern React hooks.

[**🌐 View Live Demo**](https://password-generator-react-by-zestymec.netlify.app/)

---

## 🚀 Overview

In today's digital world, security is paramount. I built this tool to help users generate strong, randomized passwords on the fly. Whether you need a simple 8-character string or a complex 100-character key with numbers and symbols, this app handles it with ease.

This project was a great way for me to deep-dive into **React's performance hooks** like `useCallback` and `useRef` to ensure the UI remains snappy and responsive.

## ✨ Key Features

* **Dynamic Length Control:** Adjust password length from 6 to 100 characters using an interactive slider.
* **Customizable Complexity:** Toggle inclusion of Numbers and Special Characters (`!@#$%^&*`).
* **One-Click Copy:** Instant "Copy to Clipboard" functionality for a seamless user experience.
* **Real-time Updates:** The password regenerates instantly as you tweak the settings.
* **Responsive Design:** Fully styled with Tailwind CSS to look great on mobile, tablet, and desktop.

## 🛠️ Tech Stack & Concepts Used

* **Framework:** React.js (Vite)
* **Styling:** Tailwind CSS
* **State Management:** `useState`
* **Memoization:** `useCallback` (Optimizing the generation logic)
* **Side Effects:** `useEffect` (Handling auto-generation on dependency change)
* **DOM Manipulation:** `useRef` (Managing the input selection for clipboard actions)

## ⚙️ Local Installation

To get this project running on your local machine, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/zestymec/Password-generator-React.git](https://github.com/zestymec/Password-generator-React.git)
    ```
2.  **Navigate into the directory:**
    ```bash
    cd Password-generator-React
    ```
3.  **Install dependencies:**
    ```bash
    npm install
    ```
4.  **Run the development server:**
    ```bash
    npm run dev
    ```

## 🧠 Lessons Learned

While building this, I faced and resolved specific challenges regarding **NPM dependency conflicts** and **build environment differences** during Netlify deployment. Debugging these issues taught me a lot about `package-lock.json` stability and cross-platform terminal execution policies.

---

### 👨‍💻 About Me
I'm **Muhammad Umer Aziz**, a Frontend Developer Intern and an FSc Pre-Engineering student based in Lahore. I'm passionate about building clean, human-centric web applications and constantly expanding my skill set in the React ecosystem.

* **GitHub:** [@zestymec](https://github.com/zestymec)
* **Linkedin:** [@zestymec](https://www.linkedin.com/in/zestymec/)
* **Current Goal:** Mastering Full-Stack Development and German Language (A2/B1).