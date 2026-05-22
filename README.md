# React Paginated Image Gallery

A responsive React image gallery that fetches and displays paginated photos from the Picsum API. Built with React Hooks and Tailwind CSS, featuring custom loading states, reusable components, and Next/Prev navigation.

## 🚀 Features

- **API Integration:** Fetches dynamic image data (images, authors, URLs) using Axios.
- **Pagination Navigation:** Simple and intuitive "Previous" and "Next" buttons to browse through pages.
- **Dynamic Loading State:** Gives immediate visual feedback while waiting for API responses.
- **Component-Based Architecture:** Uses a reusable `<Card />` component to keep code modular and clean.
- **Tailwind CSS Styling:** Fully responsive layout with a sleek dark mode design and hover effects.

## 🛠️ Tech Stack

- **Frontend:** React (useState, useEffect)
- **Styling:** Tailwind CSS
- **HTTP Client:** Axios
- **API:** [Picsum Photos API](https://picsum.photos/)

## 📂 Project Structure

```text
src/
├── components/
│   └── Card.jsx    # Reusable component for individual image cards
├── App.jsx         # Main application logic and pagination state
└── index.css       # Tailwind imports and global styles
