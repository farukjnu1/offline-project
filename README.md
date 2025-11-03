# 💾 Browser Storage Playground

A **frontend web application** built to **demonstrate and test data storage techniques in modern browsers**.  
This project explores multiple client-side storage options — from simple key-value storage to advanced IndexedDB — helping developers understand how to persist data efficiently without a backend.

---

## 🚀 Overview

This project showcases how to use:
- 🗝️ **localStorage** for persistent key-value data  
- ⏳ **sessionStorage** for temporary per-session data  
- 🧱 **IndexedDB** for structured database-like storage  
- 🧩 **Extension Storage (chrome.storage)** for browser extension environments  

Each storage type has been implemented with practical examples and an interactive UI that allows you to **add, view, update, and delete** stored data directly in the browser.

---

## 🧠 Features

- ✅ Store and retrieve key-value pairs from **localStorage** and **sessionStorage**  
- ✅ Manage complex JSON data with **IndexedDB**  
- ✅ Example integration with **browser extension storage API**  
- ✅ Clear data individually or all at once  
- ✅ Interactive interface to visualize stored data  
- ✅ Modular JavaScript structure for easy learning and extension  

---

🔍 Supported Storage APIs
| Storage Type          | Persistence            | Capacity        | Accessibility             | Use Case                           |
| --------------------- | ---------------------- | --------------- | ------------------------- | ---------------------------------- |
| **localStorage**      | Until cleared manually | ~5MB            | Same origin               | Save user settings or preferences  |
| **sessionStorage**    | Until tab closes       | ~5MB            | Same tab only             | Temporary session data             |
| **IndexedDB**         | Persistent             | Hundreds of MBs | Same origin               | Complex data or offline-first apps |
| **Extension Storage** | Persistent             | Browser-defined | Chrome/Firefox extensions | Data for browser extensions        |

----------------

🎯 Learning Objectives

Understand the differences between various browser storage APIs

Learn how to store, retrieve, update, and delete data from each type

Build a foundation for offline-first and stateful web applications

Explore how storage impacts security, performance, and data persistence

-------------------------

🛠️ Technologies Used

HTML5 for structure

CSS3 for layout and styling

Vanilla JavaScript (ES6+) for logic and storage APIs

IndexedDB API for database management

Browser Extension APIs (optional)
