<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=220&section=header&text=CANNOIL%20E-COMMERCE%20FRONTEND&fontSize=44&fontColor=FFD700&fontAlignY=42&desc=🌿%20Health%20Products%20Storefront%20%C2%B7%20React%20%2B%20Vite%20%C2%B7%20Tailwind&descAlignY=62&descColor=DCDCDC&animation=fadeIn" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&weight=700&size=20&duration=2800&pause=900&color=FFD700&center=true&vCenter=true&width=760&lines=%F0%9F%9B%92+Product+Catalog+%2B+Shopping+Cart;%E2%9A%9B%EF%B8%8F+Modular+React+Component+Architecture;%F0%9F%94%8C+Built+to+Connect+with+a+Backend+API;%F0%9F%93%B1+Fully+Responsive+%C2%B7+Desktop+%2B+Mobile;%F0%9F%8F%86+%231+GitHub+Committer+in+Colombia)](https://git.io/typing-svg)

<br/>

<p align="center">
  <a href="https://github.com/NietoDeveloper">
    <img src="https://img.shields.io/badge/Engineer-Manuel%20Nieto-blue?style=for-the-badge&logo=github"/>
  </a>
  <a href="https://committers.top/colombia#NietoDeveloper">
    <img src="https://img.shields.io/badge/Committers.top-%231%20Colombia-gold?style=for-the-badge"/>
  </a>
  <a href="https://react.dev/">
    <img src="https://img.shields.io/badge/React-Frontend-61DAFB?style=for-the-badge&logo=react&logoColor=000"/>
  </a>
  <a href="https://vitejs.dev/">
    <img src="https://img.shields.io/badge/Vite-Build_Tool-646CFF?style=for-the-badge&logo=vite&logoColor=white"/>
  </a>
  <a href="https://tailwindcss.com/">
    <img src="https://img.shields.io/badge/Tailwind_CSS-Styling-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>
  </a>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge"/>
  </a>
</p>

<p align="center">
  <a href="https://github.com/NietoDeveloper/Client-CannOil_1.1">
    <img src="https://img.shields.io/badge/📂_Source-NietoDeveloper%2FClient--CannOil__1.1-000000?style=for-the-badge&logo=github&logoColor=FFD700"/>
  </a>
</p>

</div>

---

## 📋 Overview

The frontend for **Cannoil E-Commerce** — a model online store for health products. Built by **Manuel Nieto**, Software Developer, in 2024, this client-side application showcases a modern, responsive UI. This build was selected by the client as the base to develop, and is designed to connect to an independent backend API repository.

---

## 🗂️ Project Structure

```text
Client-CannOil_1.1/
├── public/
└── src/
    ├── assets/
    │   ├── banner/
    │   ├── hero/
    │   ├── top/
    │   ├── website/
    │   └── women/
    ├── components/
    │   ├── Blogs/
    │   ├── Cart/
    │   ├── Layouts/
    │   ├── Member/
    │   └── Products/
    └── reducers/
```

---

## 🔄 Storefront Data Flow

```mermaid
flowchart LR
    A([👤 Shopper]) -->|Browses| B[Products Component]
    B -->|Add to Cart| C[Cart Reducer]
    C -->|State Update| D[Cart Component]
    D -->|Checkout Ready| E([🔗 Backend API])
    B -->|Reads Content| F[Blogs Component]
    B -->|Auth State| G[Member Component]

    style A fill:#FFD700,color:#000,stroke:#FFD700
    style C fill:#06B6D4,color:#000,stroke:#06B6D4
    style E fill:#000,color:#FFD700,stroke:#FFD700
```

---

## 🛠️ Technologies

<div align="center">

| Category | Technologies |
|:---------|:-------------|
| 🏃 **Runtime** | Node.js (runtime for development tools) |
| 🎨 **Frontend Library** | React (dynamic UI) |
| 💅 **Styling Framework** | Tailwind CSS (utility-first CSS) |
| ⚡ **Build Tooling** | Vite (fast frontend build tool) |

</div>

---

## ✨ Features

- **Responsive and Modern UI:** Clean, mobile-first interface across all viewports.
- **Product Catalog Display:** Structured product browsing experience.
- **Shopping Cart Integration:** State-managed cart via reducers.
- **Smooth User Interactions:** Fluid navigation between catalog, blog, and member sections.

---

## 🚀 Installation

**Step 1 — Clone the repository**

```bash
git clone https://github.com/NietoDeveloper/Client-CannOil_1.1
```

**Step 2 — Navigate to the client directory**

```bash
cd Cannoil-Ejemplo1/client
```

**Step 3 — Install dependencies**

```bash
npm install
```

**Step 4 — Start the development server**

```bash
npm run dev
```

---

## 📖 Usage

- Visit `http://localhost:5173` in your browser.
- Browse products and test the cart functionality.

---

## 🤝 Contributing

Fork the repo and submit pull requests for contributions.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

Developed by **Manuel Nieto (NietoDeveloper)**. Connect via [GitHub](https://github.com/NietoDeveloper).

<div align="center">

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=120&section=footer&animation=fadeIn" width="100%"/>

</div>
