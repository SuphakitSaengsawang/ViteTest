# 🚀 Vite Experiment

A simple project where I explore **Vite**, modern frontend tooling, and deployment using GitHub Pages.

---

## 📌 Overview

This project started as a basic **Hello World** app but evolved into a small experiment to understand:

- how Vite works compared to older tools like Webpack  
- how modern frontend projects are structured  
- how to deploy a real project to production  

The goal was not just to make something look good, but to understand the **full workflow from development → build → deployment**.

---

## ⚙️ Tech Stack

- **Vite** – fast frontend tooling  
- **Vanilla JavaScript**  
- **CSS (custom styling)**  
- **Git & GitHub**  
- **GitHub Pages (with GitHub Actions)**  

---

## 🧠 What I Learned

### 1. Vite vs Traditional Setup
- Vite uses **native ES modules** instead of heavy bundling during development  
- `index.html` is part of the app, not just a template  
- much faster dev experience  

---

### 2. Dev vs Production
- `npm run dev` → development server  
- `npm run build` → generates `/dist`  
- `dist` = what actually gets deployed  

---

### 3. Deployment (Real World Workflow)

Instead of manually uploading files:

```bash
git add .
git commit -m "update"
git push
