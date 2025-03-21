# 🌟 Cath Starter Kit

## 🚀 Introduction

Welcome to the **Cath Starter Kit**! This setup is designed for developers who want a **lightweight, modern, and efficient** foundation for building Laravel applications with a React frontend powered by **[Inertia.js](https://inertiajs.com)**.

This kit is **JavaScript-first**, using **JSX instead of TSX**, making it accessible to developers who prefer plain JavaScript over TypeScript. It includes **React 19, TailwindCSS 4**, and Breeze for simple authentication and scaffolding.

---

## 🎯 Why Choose This Kit?

✔️ **React 19 + JSX** – Simple, clean, and TypeScript-free  
✔️ **Laravel 12 + Breeze** – Lightweight authentication with Inertia.js  
✔️ **TailwindCSS 4** – Modern styling with utility-first CSS  
✔️ **Vite-Powered** – Lightning-fast HMR for smooth development  
✔️ **Pre-configured Testing** – Includes PHPUnit & Pest  
✔️ **Quick Setup** – Get started in minutes!

---

## 🛠 Getting Started

### 1️⃣ Install

```bash
laravel new --using=catherinetagao/cath-starter-kit
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Run Migrations

```bash
php artisan migrate --seed
```

### 4️⃣ Start Development

```bash
composer run dev
```

🎉 Your application is now up and running!

---

## ⚡ Create Inertia Components Easily

This starter kit includes a custom Artisan command to quickly generate Inertia.js React components:

### 🏗️ Generate a New Component

```bash
php artisan make:inertia Components/MyComponent
```

This will create a new file at `resources/js/Components/MyComponent.jsx` with a basic component template.

### 📂 File Structure

```
resources/js/Components/MyComponent.jsx
```

### ✨ Example Generated Component

```jsx
import React from "react";

const MyComponent = () => {
    return <div>{/* MyComponent component */}</div>;
};

export default MyComponent;
```

This command ensures that components are placed in the correct directory and prevents overwriting existing files. It also automatically opens the newly created file for editing.

---

## 📖 Documentation

For more details on Laravel Breeze, visit the official [Laravel Starter Kit docs](https://laravel.com/docs/master/starter-kits#laravel-breeze).

## 🤝 Contributing

We welcome contributions! Check out the [Laravel contribution guide](https://laravel.com/docs/contributions) to get involved.

## 📜 Code of Conduct

Be kind and respectful. Please follow Laravel's [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## ⚖️ License

This starter kit is **open-source** under the **MIT license**.

---
