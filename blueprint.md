# Blueprint: Interactive Dashboard

## Overview

This document outlines the structure and functionality of an interactive dashboard application. The application is a single-page interface built with HTML, CSS, and JavaScript, featuring data visualization, customer management, and other business-related modules.

## Project Structure & Design

*   **`index.html`**: The main file containing the entire application's HTML structure, including all tabs, modals, and content sections. It also contains the application's JavaScript logic within a `<script>` tag.
*   **`style.css`**: The stylesheet for the application.
*   **`main.js`**: A JavaScript file (currently empty).
*   **Web Components**: The application will be refactored to use Web Components for modular and reusable UI elements.
*   **Modern CSS**: The application will use modern CSS features like Container Queries, Cascade Layers, and CSS Variables for a more robust and maintainable styling system.
*   **Modern JavaScript**: The application will use ES Modules and other modern JavaScript features for better code organization and readability.

## Current State & Implemented Features

*   A single-page dashboard with multiple tabs: Dashboard, Customers, Offers, Sales Funnel, KPIs, and Management.
*   The "Management" tab has sub-tabs for Data, Users, and Products.
*   Modals for adding and editing users and products.
*   Various buttons and forms for user interaction.
*   The application's JavaScript is currently embedded within the `index.html` file.

## Plan for Current Request: Fix Buttons and Tabs

The user has reported that buttons and tabs are not working correctly. The following steps will be taken to address this:

1.  **Move JavaScript to `main.js`**: To improve code organization and maintainability, all JavaScript code will be moved from `index.html` to `main.js`.
2.  **Implement Tab Switching Logic**: Add event listeners to all main tabs and management sub-tabs to ensure they correctly show and hide the corresponding content.
3.  **Implement Modal Logic**: Ensure that all modals (e.g., for adding/editing users and products) open and close correctly when their corresponding buttons are clicked.
4.  **Review and Fix Event Listeners**: Review all other event listeners for buttons and forms to ensure they are correctly attached and functioning.
5.  **Ensure DOM is Ready**: Wrap all JavaScript code that interacts with the DOM in a `DOMContentLoaded` event listener to prevent errors from trying to access elements that have not yet been rendered.
