## ✅ TodoList App using React + Vite + TailwindCSS v4 + React Icons

This is a simple and responsive Todo List App built using **React 19**, **Vite**, **TailwindCSS v4**, and **React Icons**.

---

## 📦 Project Setup

### 1️⃣ Clone this repository

```bash
git clone https://github.com/ChiragVasava/TodoList-App-using-React-Tailwind-React-Icons.git
```
```bash
cd TodoList-App-using-React-Tailwind-React-Icons
```
### 2️⃣ React + Vite  & Node.js Setup
```bash
npm create vite@latest Project_Name -- --template vue
```
```bash
cd Project_Name
```
### Install Node Modules
#### Make sure Node.js is installed on your system. Then install dependencies:
```bash 
npm install
```
### Run localhost Server
```bash
npm run dev
```


###  3️⃣ Install **UUID** Package
#### 1. Install
```bash
npm install uuid
```

#### 2. Create UUID
##### ESM-syntax (must use named exports):
```bash
import { v4 as uuidv4 } from 'uuid';
uuidv4(); // ⇨ '9b1deb4d-3b7d-4bad-9bdd-2b0d7b3dcb6d'
```
### 4️⃣ Install React icons
```bash
    npm install react-icons --save
``` 
### 5️⃣ TailwindCSS v4 Setup
#### TailwindCSS is configured using the new Vite Plugin for Tailwind: @tailwindcss/vite

### 1. Install Tailwind via Vite plugin:
```bash
npm install -D @tailwindcss/vite autoprefixer
```

### 2. Create postcss.config.js and add:
```js
// postcss.config.js
import tailwindcss from '@tailwindcss/postcss';
import autoprefixer from 'autoprefixer';

export default {
  plugins: [tailwindcss(), autoprefixer()],
}

```
### 3. Create or update index.css in src/ folder:
```css
/* src/index.css */
@import "tailwindcss";
```
### 4. Import index.css in main.jsx:
```js
import './index.css';
```

### ⚙️ Tech Stack
| Tech        | Version                         |
| ----------- | ------------------------------- |
| React       | ^19.1.0                         |
| Vite        | latest                          |
| TailwindCSS | ^4.1.11 via `@tailwindcss/vite` |
| React Icons | ^5.5.0                          |
| UUID        | ^11.1.0                         |

### 🧠 Project Features
<ul>
<li>Add, delete, and toggle tasks</li>
<li>Checkbox to mark as completed</li>
<li>Stylish UI with TailwindCSS</li>
<li>UUID-based unique IDs</li>
<li>Uses React state and props</li>
<li>Responsive layout</li>
</ul>

### 💡 Folder Structure
```css
src/
│
├── components/
│   └── Navbar.jsx
│   └── TodoItem.jsx
│
├── App.jsx
├── main.jsx
└── index.css
```
🙌 Author
Made with 💻 by <a href="https://github.com/ChiragVasava">Chirag Vasava</a>

### 📷 Screenshot
