# 🚀 Placement Preparation Dashboard Portal

Welcome to the **Placement Preparation Dashboard Portal**! This repository is a centralized, high-fidelity portfolio dashboard built to review, launch, and inspect 8 front-end project milestones. 

The dashboard is designed with a premium, sleek **AMOLED Black theme**, featuring responsive sandboxed previews and an inline read-only code inspector.

---

## 🎨 Dashboard Features

* **Terminal-Style Preloader**: A retro typewriter loader typing `~/PrepHub` with a blinking underscore cursor before fading.
* **Unified Metrics Grid**: Displays the total count of milestones, React apps, static HTML apps, and Tailwind CSS layouts.
* **Live Sandbox Preview**: Launch compiled production builds directly inside the dashboard using a responsive iframe with viewport toggles (**Desktop**, **Tablet**, and **Mobile** sizes).
* **Source Code Inspector**: An asynchronous file reader with syntax highlighting, allowing you to inspect code files side-by-side directly from the dashboard.
* **Category Filtering**: Instantly search by name, description, or tags, and filter by Category (All, React, Static HTML, Tailwind).

---

## 📂 Project Organization 

All 8 placement milestone projects are organized cleanly within the `projects/` directory:

| Icon | Project Name | Category | Tech Stack & Focus Areas |
| :---: | :--- | :---: | :--- |
| 🔒 | **Modern Login Portal** | `Static` | HTML5, CSS3, Vanilla JS. Real-time validation, password toggle, credentials tip box. |
| 📋 | **Interactive To-Do App** | `Static` | HTML5, CSS3, JS, Local Storage. Dynamic DOM generation, clear/add tasks. |
| 📥 | **JSON API Fetcher** | `Static` | HTML5, CSS3, Async JS. Fetch API integration with async/await, user registry lists. |
| 🎓 | **React Student Dashboard** | `React` | Vite, React Router, JSX. Nested routing configurations, params mapping (`/students/:id`). |
| 🔍 | **Product Search & Debounce** | `React` | Vite, React. Custom hooks (`useDebounce`, `useLocalStorage`), local Rupee currency formatting. |
| 📝 | **Validated Signup Portal** | `React` | Vite, Tailwind CSS. Deep form validation state, custom validation regex. |
| 📐 | **Flexbox Layout Studio** | `Tailwind` | Vite, Tailwind CSS v4. Grow/shrink parameters, flex alignments, gap grids. |
| 👥 | **React API User Registry** | `React` | Vite, React. Asynchronous queries loader, dynamic list state mappings. |

---

## 🛠️ Technical Stack

* **Build Tooling & Bundling**: [Vite](https://vite.dev/)
* **Type Safety**: [TypeScript](https://www.typescriptlang.org/) (Strict Mode)
* **Styling**: [Tailwind CSS](https://tailwindcss.com/)
* **Icons**: [Lucide React](https://lucide.dev/)
* **Frame**: [React](https://react.dev/)

---

## 🚀 Getting Started

Follow these steps to run the dashboard portal and compile/install dependencies for all sub-projects.

### 1. Clone and Install Root Dependencies
Install dependencies for the main launcher dashboard:
```bash
git clone https://github.com/your-username/Placement_Preparation.git
cd Placement_Preparation
npm install
```

### 2. Install Sub-Project Dependencies
Run the batch workspace installation script to download `node_modules` for all 5 React sub-projects:
```bash
npm run install-all
```

### 3. Build Sub-Projects
Compile the production static assets for all sub-projects (generates the `dist/` folders needed for the live sandbox preview to load):
```bash
npm run build-all
```

### 4. Launch the Dashboard Dev Server
Run the Vite development server for the central launcher:
```bash
npm run dev
```
Open **[http://localhost:5174/](http://localhost:5174/)** in your browser to view the portal.

---

## 💻 Development Commands Reference

| Command | Action |
| :--- | :--- |
| `npm run dev` | Starts the launcher dev server on port `5174` |
| `npm run build` | Compiles the main launcher React + TS app into `dist/` |
| `npm run install-all` | Recursively installs packages for all sub-projects |
| `npm run build-all` | Recursively builds production artifacts for all sub-projects |
| `npm run preview` | Previews the local build of the main dashboard |
