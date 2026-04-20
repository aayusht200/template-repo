# ⚙️ Webpack + Biome + Jest Template

A modern, reusable **frontend starter template** for JavaScript projects using **Webpack 5**, **Biome**, **Jest**, and **Babel**.

Built for fast project setup, clean code standards, test-driven development, and GitHub Pages deployment.

---

## 🧱 Folder Structure

```txt
project/
├── src/
│   ├── index.js
│   ├── style.css
│   └── template.html
├── dist/
├── tests/
├── webpack.dev.js
├── webpack.prod.js
├── babel.config.cjs
├── package.json
├── biome.json
└── .gitignore
```

---

## ⚙️ Setup Instructions

### 1️⃣ Initialize Project
```bash
npm run setup
```

### 2️⃣ Start Development Server
```bash
npm start
```

### 3️⃣ Build for Production
```bash
npm run build
```

### 4️⃣ Lint & Format Code
```bash
npm run lint-format
```

Optional:
```bash
npm run lint
npm run format
```

### 5️⃣ Run Tests
```bash
npm run test
npm run test:watch
```

---

## 🚀 GitHub Pages Deployment

### Deploy
```bash
npm run deploy
```

### Reset Deployment Branch
```bash
npm run reset
```

---

## 🧩 Tech Stack

- Webpack 5
- Biome
- Jest
- Babel
- HTML Webpack Plugin
- CSS + Style Loaders
- ES Modules

---

## 🗂️ .gitignore

```txt
node_modules/
dist/
.DS_Store
._*
```

---

## 🧰 Notes

- supports development + production
- test-ready from day one
- deploy workflow automated
