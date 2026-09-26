# FocusFlow - Pomodoro & Task Tracker

## Overview
FocusFlow is a minimalist, modern web application designed to boost productivity. It combines a classic **Pomodoro Timer** (25-minute focus intervals) with a built-in **Task Tracker**. This project was built to demonstrate rapid prototyping and iterative development using AI-assisted coding tools.

## Why We Built This
The primary purpose of this application is to provide a distraction-free environment for users to manage their daily tasks and maintain deep focus using the proven Pomodoro technique. It serves as a functional MVP (Minimum Viable Product) showcasing clean UI design and client-side state management.

## Technologies Used & Their Applications

This project was developed as a single-page application prioritizing speed, simplicity, and a zero-build-step deployment.

*   **HTML5:** Used as the structural foundation of the application, providing the semantic layout for the timer display and task list elements.
*   **Tailwind CSS (via CDN):** Chosen for rapid UI styling. By utilizing utility classes directly in the HTML, we were able to quickly design a modern, responsive, and dark-mode themed interface without writing custom, bloated CSS files. 
*   **Vanilla JavaScript:** Used for all the core logic, including:
    *   Managing the countdown timer state (`setInterval`, `clearInterval`).
    *   Handling DOM manipulation for adding and deleting tasks dynamically.
    *   Event listening for user interactions (button clicks, Enter key presses).
    We opted for Vanilla JS over a heavy framework to keep the project lightweight, extremely fast, and easy to deploy instantly.
*   **AI-Assisted Development:** Utilized for rapid prototyping, generating boilerplate code, and iterative debugging to ensure a clean final product.

## How to Use
1. Enter your tasks in the input field and click the **+** button (or press Enter).
2. Click **Start** on the timer to begin a 25-minute focus session.
3. Once the timer completes, take a short break!
4. Remove tasks as you complete them by clicking the **✕** button.
