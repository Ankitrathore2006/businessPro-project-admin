# PocketVenders Admin Panel

PocketVenders Admin Panel is a modern, full-featured admin dashboard built with **React**, **TypeScript**, and **Tailwind CSS**. It provides a robust foundation for managing your PocketVenders platform, including user authentication, contact email management, and a responsive, customizable UI.

---

## Overview

This admin panel is designed for the PocketVenders project, offering:

- Secure authentication with protected routes
- Contact email management with data tables
- Responsive sidebar navigation
- Toast notifications for user feedback
- Modern UI with dark mode support

---

## Tech Stack

- **React 19**
- **TypeScript**
- **Tailwind CSS v4**
- **React Router v6**
- **Axios**
- **React Toastify**

---

## Features

- **Authentication:** Secure login system with protected and public routes.
- **Contact Emails:** View and manage contact form submissions in a sortable table.
- **Sidebar Navigation:** Collapsible, responsive sidebar with icons.
- **Notifications:** Toast notifications for actions like login, logout, and errors.
- **Dark Mode:** Seamless dark/light theme switching.
- **Reusable Components:** Tables, forms, modals, and more.

---

## Getting Started

### Prerequisites

- Node.js 18.x or later (Node.js 20.x recommended)
- npm or yarn

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Ankitrathore2006/businessPro-project-admin.git
   cd businessPro-project-admin
   ```

2. **Install dependencies:**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser:**
   Visit [http://localhost:5173](http://localhost:5173) to view the app.

---

## Project Structure

```
src/
  api/                # Axios instance and API helpers
  components/         # Reusable UI components (tables, forms, etc.)
  context/            # React context providers (e.g., SidebarContext)
  icons/              # SVG and icon components
  layout/             # Layout components (AppSidebar, AppLayout, etc.)
  middleware/         # Auth middleware and route guards
  pages/              # Page components (Home, SignIn, ContactEmails, NotFound)
  App.tsx             # Main app component with routing
  main.tsx            # Entry point
```

---

## Authentication

- Uses JWT or session-based authentication.
- Protected routes redirect unauthenticated users to `/signin`.
- Authenticated users cannot access the `/signin` page.

---

## Customization

- **Sidebar:** Easily add or remove navigation items in `AppSidebar.tsx`.
- **API:** Update API endpoints in `src/api/axios.ts` as needed.
- **Styling:** Modify Tailwind classes or extend the config for custom themes.

---

## License

This project is licensed under the MIT License.

---

## Support

If you find this project helpful, please consider giving it a star on GitHub.  
For issues or feature requests, open an issue in this repository.

---

**PocketVenders Admin Panel** — Built with ❤️ using React & Tailwind CSS.