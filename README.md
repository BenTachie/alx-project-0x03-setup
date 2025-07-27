# 🚀Reactify TS: Mastering Advanced TypeScript in React

This project is a foundational setup for building scalable React applications using **Next.js** and **TypeScript**. It focuses on implementing a **shared layout system**, **imperative routing**, **custom 404 page**, **centralised interfaces**, and **global Google Fonts styling**- all while adhering to the DRY principle and clean code architecture.

---

## 📌 Project Objectives

- Implement a **shared layout structure** using reusable components.
- Set up **imperative routing** using Next.js `useRouter`.
- Integrate **Google Fonts (Montserrat)** globally with TailwindCSS.
- Centralize all TypeScript **interfaces** for improved code maintainability.
- Customize the **404 Not Found page** for better UX.
- Use modern design practices with **Tailwind CSS** and **React Icons**.

---

## 📂 Folder Structure
```
alx-project-0x03/
├── components/
│ ├── common/
│ │ └── Button.tsx
│ └── layouts/
│ ├── Footer.tsx
│ ├── Header.tsx
│ └── Layout.tsx
├── interface/
│ └── index.ts
├── pages/
│ ├── index.tsx
│ └── 404.tsx
├── public/
├── styles/
│ └── globals.css
├── tsconfig.json
├── package.json
└── README.md
```
---

## 🧰 Tech Stack

- **Framework:** [Next.js](https://nextjs.org/) with TypeScript
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Icons:** [React Icons](https://react-icons.github.io/react-icons)
- **Fonts:** [Google Fonts - Montserrat](https://fonts.google.com/specimen/Montserrat)

---

## ✅ Features

### 1. Shared Layout System
- Centralised layout using `Header`, `Footer`, and `Layout` components.
- DRY approach: layouts defined once and used globally via `_app.tsx`.

### 2. Imperative Routing
- Navigation powered by `useRouter` instead of static `<Link />`.
- Buttons trigger navigation to dynamic pages (e.g., `/generate-text-ai`, `/text-to-image`, etc.).

### 3. Reusable UI Components
- A configurable and reusable `Button` component accepting:
  - `label`, `size`, `backgroundColor`, `onClick` handler.

### 4. Google Fonts Integration
- `Montserrat` font applied globally through `global.css`.

### 5. Interface Organization
- All TypeScript interfaces moved to `/interface/index.ts` for better maintainability and scalability.

### 6. Custom 404 Page
- Fun and modern 404 design using Tailwind CSS and React Icons.
- Enhanced user experience when accessing unknown routes.

---

## 🧪 Getting Started

### 🔄 Prerequisites

- Node.js v16 or later
- Git

### 🚀 Installation

```
# Clone the repository
git clone https://github.com/your-username/alx-project-0x03-setup.git
cd alx-project-0x03-setup

# Install dependencies
npm install
💻 Run the Application
bash
Copy
Edit
npm run dev
Visit http://localhost:3000 to view the app.
```

## 🧩 Available Routes
Path	Description
/	Landing page
/generate-text-ai	Placeholder for AI app
/text-to-image	Placeholder for image generator
/counter-app	Placeholder for contact/info
/404	Custom Not Found page

You will see 404 pages for subpages unless they're created.

### 🗂 Interfaces Reference
All interfaces are managed centrally in /interface/index.ts, improving code readability and simplifying future updates.

## 📸 UI Snapshot
Coming soon...

## 🙌 Acknowledgements
ALX SE Program

Next.js Documentation

TailwindCSS Team

Google Fonts

React Icons Community

## 📬 Contact
Developed by Benedict Tachie
📧 Email: tachiebenedict@gmail.com
🔗 GitHub: @BenTachie

>“Clean architecture is not just about structure—it’s about setting your future self up for speed.” 🛠️
