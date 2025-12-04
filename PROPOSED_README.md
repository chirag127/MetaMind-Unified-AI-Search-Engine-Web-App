# <div align="center">🧠 MetaMind: Unified AI Search Engine</div>

<div align="center">
    <img src="https://raw.githubusercontent.com/chirag127/MetaMind-Unified-AI-Search-Engine-Web-App/main/.github/assets/hero_banner.png" alt="MetaMind Hero Banner"/>
</div>

<div align="center">

[
![Build Status](https://github.com/chirag127/MetaMind-Unified-AI-Search-Engine-Web-App/actions/workflows/ci.yml/badge.svg?style=flat-square)
](https://github.com/chirag127/MetaMind-Unified-AI-Search-Engine-Web-App/actions/workflows/ci.yml)
[
![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/MetaMind-Unified-AI-Search-Engine-Web-App?style=flat-square&token=G1H2I3J4K5)
](https://codecov.io/gh/chirag127/MetaMind-Unified-AI-Search-Engine-Web-App)
[
![Formatted with Biome](https://img.shields.io/badge/Formatted_with-Biome-60A5FA?style=flat-square&logo=biome)
](https://biomejs.dev/)
[
![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC_BY--NC_4.0-blue.svg?style=flat-square)
](https://creativecommons.org/licenses/by-nc/4.0/)
[
![GitHub Stars](https://img.shields.io/github/stars/chirag127/MetaMind-Unified-AI-Search-Engine-Web-App?style=flat-square&logo=github)
](https://github.com/chirag127/MetaMind-Unified-AI-Search-Engine-Web-App/stargazers)

</div>

<div align="center">


![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)


![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)


![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)


![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)


</div>

**MetaMind** is a unified AI search interface aggregating results from multiple engines. It delivers comprehensive, cross-platform insights from a single query, maximizing your search efficiency and discovery.

<div align="center">
<a href="https://github.com/chirag127/MetaMind-Unified-AI-Search-Engine-Web-App/stargazers">⭐ Star this repo on GitHub — it helps!</a>
</div>

---

## Table of Contents

- [✨ Key Features](#-key-features)
- [🏛️ Architecture](#️-architecture)
- [🤖 AI Agent Directives](#-ai-agent-directives)
- [🚀 Getting Started](#-getting-started)
- [⚙️ Available Scripts](#️-available-scripts)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)

---

## ✨ Key Features

- **Unified Search Bar**: Query multiple search engines (Google, Bing, DuckDuckGo) and AI models (Gemini, Claude) simultaneously.
- **Aggregated Results**: View a consolidated list of results in a clean, intuitive interface.
- **Side-by-Side Comparison**: Easily compare search results from different sources to gain diverse perspectives.
- **Customizable Engines**: Configure which search engines and AI models to include in your queries.
- **Blazing Fast UI**: Built with Vite and React for a highly responsive and performant user experience.
- **Modern Design**: A sleek, minimalist interface crafted with TailwindCSS.

---

## 🏛️ Architecture

This project follows the **Feature-Sliced Design (FSD)** methodology to ensure scalability, maintainability, and a clear separation of concerns. The structure promotes high cohesion and low coupling between different parts of the application.

sh
src/
├── app/                # App-wide setup (routing, providers, global styles)
│   ├── providers/
│   └── styles/
├── pages/              # Application pages (e.g., SearchPage)
│   └── search/
├── features/           # User-facing features (e.g., query submission, result filtering)
│   ├── aggregate-results/
│   └── multi-engine-query/
├── entities/           # Business entities (e.g., SearchResult, Engine)
│   └── search-result/
├── shared/             # Reusable, framework-agnostic modules
│   ├── ui/             # UI components (Button, Input, Card)
│   ├── lib/            # Helper functions and hooks
│   └── config/         # API endpoints, constants
└── main.tsx            # Application entry point


---

## 🤖 AI Agent Directives

<details>
<summary><strong>SYSTEM: APEX TECHNICAL AUTHORITY (DECEMBER 2025 EDITION)</strong></summary>

### 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards.
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

---

### 2. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
This repository, `MetaMind-Unified-AI-Search-Engine-Web-App`, is a modern frontend web application.

*   **PRIMARY SCENARIO: WEB / APP / EXTENSION (TypeScript)**
    *   **Stack:** This project leverages **TypeScript 5.x (Strict Mode)**, **Vite 5.x** for development and bundling, **React 18+** (with Hooks), and **TailwindCSS v4** for utility-first styling.
    *   **Architecture:** Strictly adheres to **Feature-Sliced Design (FSD)**. All new development must follow this pattern, organizing code into `pages`, `features`, `entities`, and `shared` layers. This is the **Single Source of Truth** for architectural decisions.
    *   **State Management:** Utilizes modern React state management patterns (Context API, `useState`, `useReducer`). For complex global state, a lightweight library like **Zustand** is preferred.
    *   **Linting & Formatting:** **Biome.js** is the single toolchain for linting, formatting, and import sorting. All code must be compliant with the rules defined in `biome.json` before merging. Execute `npm run format` and `npm run lint:check`.
    *   **Testing:** **Vitest** is used for unit and integration testing of components and logic. **Playwright** is used for end-to-end testing of user flows. All features must have corresponding tests to maintain high code coverage.

### 3. VERIFICATION & EXECUTION COMMANDS
*   **Install Dependencies:** `npm install`
*   **Run Development Server:** `npm run dev`
*   **Run All Checks (Format, Lint, Test):** `npm run test`
*   **Build for Production:** `npm run build`

</details>

---

## 🚀 Getting Started

Follow these steps to set up and run the project locally.

**Prerequisites:**

- Node.js (v18 or later)
- npm (v9 or later)

**Installation:**

1.  **Clone the repository:**
    bash
    git clone https://github.com/chirag127/MetaMind-Unified-AI-Search-Engine-Web-App.git
    

2.  **Navigate to the project directory:**
    bash
    cd MetaMind-Unified-AI-Search-Engine-Web-App
    

3.  **Install dependencies:**
    bash
    npm install
    

4.  **Create a local environment file:**
    Copy the example environment file and add your API keys.
    bash
    cp .env.example .env.local
    

5.  **Run the development server:**
    bash
    npm run dev
    

    The application will be available at `http://localhost:5173`.

---

## ⚙️ Available Scripts

| Script          | Description                                           |
| --------------- | ----------------------------------------------------- |
| `npm run dev`   | Starts the development server with Hot Module Reload. |
| `npm run build` | Builds the application for production.                |
| `npm run preview` | Serves the production build locally for preview.      |
| `npm run test`  | Runs all unit and integration tests with Vitest.      |
| `npm run format`| Formats all code using Biome.                         |
| `npm run lint`  | Lints all code using Biome.                           |
| `npm run lint:check`| Checks for linting and formatting errors.           |

---

## 🤝 Contributing

Contributions are welcome! Please read our [**Contributing Guidelines**](.github/CONTRIBUTING.md) to get started. We follow a standard code of conduct and expect all contributors to adhere to it.

If you find a bug or have a feature request, please open an issue using the [**Bug Report Template**](.github/ISSUE_TEMPLATE/bug_report.md).

---

## 📜 License

This project is licensed under the [**Creative Commons Attribution-NonCommercial 4.0 International License**](LICENSE).
