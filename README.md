# Watch Department ⌚

Watch Department is a full-stack e-commerce application for browsing and managing a catalog of watches.  
It’s built on top of a custom React + Node.js starter (no CRA), using Webpack, Gulp, Babel, and a small Express server so you can see everything that’s happening “under the hood”.

---

## 🚀 Features

- **Product catalog**
  - Display a list/grid of watches
  - View detailed information for each watch (brand, model, price, description, etc.)
- **Shopping experience**
  - Add/remove items from a cart
  - Update quantities
  - Placeholder for checkout flow / order summary
- **Full-stack architecture**
  - React front-end backed by an Express server
  - Controllers / models / routes structure for a clean API layer
- **Developer-friendly tooling**
  - Webpack + Babel for modern JS/JSX
  - Gulp, Browsersync, and Nodemon for hot reload and a smooth DX
  - Prettier config for consistent code style
  - Tailwind / SCSS for styling

---

## 🧱 Tech Stack

**Frontend**

- React
- JavaScript (ES6+)
- JSX
- SCSS / CSS 

**Backend**

- Node.js
- Express
- Controllers / Models / Routes structure for RESTful APIs

**Tooling & Build**

- Webpack
- Babel
- Gulp
- Browsersync
- Nodemon
- Prettier
- PostCSS / Tailwind config

---

## 📁 Project Structure

> High-level overview — adjust as needed to match your exact files.

```bash
Watch-Department/
├─ config/              # Config files (db, environment, etc.)
├─ controllers/         # Express controllers (API logic)
│  └─ api/              # API-specific controllers
├─ models/              # Data models (e.g., Watch, User, etc.)
├─ routes/
│  └─ api/              # Express routes (e.g., /api/watches)
├─ public/              # Static assets served by the app
├─ src/
│  ├─ components/       # Reusable React components (Cards, Layout, etc.)
│  ├─ pages/            # Page-level components (Home, Catalog, Product detail)
│  ├─ styles/           # SCSS / CSS modules
│  ├─ App.js            # Root React component
│  └─ index.js          # React entry point
├─ app-server.js        # Dev server integration (Webpack/Browsersync)
├─ server.js            # Production server entry (Express)
├─ crud-helper.js       # Helper utilities for CRUD operations
├─ webpack.config.js    # Webpack config
├─ gulpfile.js          # Gulp tasks for build/dev
├─ tailwind.config.js   # Tailwind config (if used)
├─ postcss.config.js    # PostCSS config
├─ package.json
└─ README.md
