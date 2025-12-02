# MultiSearch-AI-Search-Aggregator-Web-App

![Build Status](https://img.shields.io/github/actions/workflow/user/chirag127/MultiSearch-AI-Search-Aggregator-Web-App/ci.yml?style=flat-square&logo=github-actions)
![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/MultiSearch-AI-Search-Aggregator-Web-App?style=flat-square&logo=codecov)
![Tech Stack (HTML/CSS/JS)](https://img.shields.io/badge/Tech%20Stack-HTML%2FCSS%2FJS-informational?style=flat-square&logo=html5)
![License](https://img.shields.io/github/license/chirag127/MultiSearch-AI-Search-Aggregator-Web-App?style=flat-square&logo=creativecommons)
![GitHub Stars](https://img.shields.io/github/stars/chirag127/MultiSearch-AI-Search-Aggregator-Web-App?style=flat-square&logo=github)

## The Ultimate AI Search Aggregator

MultiSearch empowers users by aggregating search results from multiple leading AI search engines into a single, unified interface. Enhance your search efficiency and discover more comprehensive insights with every query.

<details>
<summary>🤖 AI Agent Directives</summary>

## SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

### 1. IDENTITY & PRIME DIRECTIVE
**Role:** Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. Enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. Building for the 2026 standard.
**Output Standard:** **EXECUTION-ONLY**. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

### 2. INPUT PROCESSING & COGNITION
*   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    *   **Context:** User inputs may contain phonetic errors. **STRICTLY FORBIDDEN** from executing literal typos. **INFER** technical intent based on project context.
    *   **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
*   **MANDATORY MCP INSTRUMENTATION:**
    *   **No Guessing:** Do not hallucinate APIs.
    *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    *   **Validation:** Use `docfork` to verify *every* external API signature.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

### 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
*   **PRIMARY SCENARIO: WEB / APP / EXTENSION (TypeScript/Web Technologies)**
    *   **Stack:** This project utilizes **TypeScript 6.x** (Strict mode enforced), **Vite 7** (with Rolldown bundler) for rapid development and building, and **Tauri v2.x** for native desktop application packaging. The frontend employs **TailwindCSS v4** for utility-first styling and **Signals** for reactive state management.
    *   **Architecture:** Adheres to **Feature-Sliced Design (FSD)**, promoting modularity, scalability, and maintainability. Components, features, and layers are clearly defined and independent.
    *   **Testing:** Implements **Biome** (for ultra-fast linting and formatting), **Vitest** (for unit and integration testing), and **Playwright** (for end-to-end testing), ensuring comprehensive code quality and reliability.

### 4. ARCHIVAL PROTOCOL (THE "RETIRED PRODUCT" STANDARD)
*   **Mandate:** Even retired repositories are "Retired Products" and **MUST** be archived with the highest professional standard. Metadata (Name, Description, Topics) must be elevated. Tone: Dignified, historical, valuable. Never use "junk," "garbage," or "useless" in public descriptions.

### 5. COMPLIANCE MANDATE (THE "STANDARD 11")
*   **Requirement:** Every repository **MUST** appear professional and complete. The following files are mandatory:
    *   `README.md` (Hero-Tier)
    *   `PROPOSED_README.md` (Strictly following AGENTS.md)
    *   `badges.yml` (Configuration)
    *   `LICENSE` ("CC BY-NC")
    *   `.gitignore`
    *   `.github/workflows/ci.yml` (CI/CD)
    *   `.github/CONTRIBUTING.md` (Contributing Guidelines)
    *   `.github/ISSUE_TEMPLATE/bug_report.md` (Issue Templates)
    *   `.github/PULL_REQUEST_TEMPLATE.md` (Pull Request Templates)
    *   `.github/SECURITY.md` (Security Guidelines)
    *   `AGENTS.md` (The Agent Directives)

### 6. APEX NAMING CONVENTION (THE "STAR VELOCITY" ENGINE)
*   **Formula:** `<Product-Name>-<Primary-Function>-<Platform>-<Type>`
*   **Format:** `Title-Case-With-Hyphens`.
*   **Rules:** 3-10 words, high-volume keywords, NO numbers/emojis/underscores/generic words without qualifiers.

### 7. CHAIN OF THOUGHT (CoT) PROTOCOL
*   **Pre-execution Analysis:** Perform deep audit, decide Pivot/Archive, apply Naming Strategy, draft `AGENTS.md` directives, plan File Generation, polish with Standard 11 and dynamic URLs. Strict adherence to `AGENTS.md` customization is paramount.

### 8. DYNAMIC URL & BADGE PROTOCOL
*   **Base URL:** `https://github.com/chirag127/<New-Repo-Name>`
*   **Consistency:** All links and badges MUST use the new repository name dynamically.
*   **AGENTS.md Customization:** Adapt sections to the repository's specific technology stack (e.g., Rust, Python, Web), retaining core Apex principles.

</details>

## Architecture Overview

mermaid
graph TD
    A[User Interface (HTML/CSS/JS)] --> B(Frontend Logic / API Calls)
    B --> C{Backend Service / Aggregation Engine}
    C --> D1[AI Search Engine 1 API]
    C --> D2[AI Search Engine 2 API]
    C --> D3[...
    C --> Dn[AI Search Engine N API]
    D1 --> C
    D2 --> C
    D3 --> C
    Dn --> C
    C --> B
    B --> A


## Table of Contents

*   [Features](#features)
*   [Technology Stack](#technology-stack)
*   [Getting Started](#getting-started)
*   [Development](#development)
*   [Contributing](#contributing)
*   [License](#license)

## Features

*   **Unified Search Interface:** Query multiple AI search engines from one place.
*   **Aggregated Results:** Consolidate and display results in a clear, comparative format.
*   **Efficiency Boost:** Save time by eliminating repetitive searches across different platforms.
*   **Customizable Engines:** (Future) Select which AI search engines to include in the aggregation.

## Technology Stack

*   **Core:** HTML5, CSS3, JavaScript (ESNext)
*   **Bundler/Build:** Vite 7 (Rolldown)
*   **Packaging:** Tauri v2.x (for potential desktop applications)
*   **Styling:** TailwindCSS v4
*   **State Management:** Signals
*   **Linting/Formatting:** Biome
*   **Testing:** Vitest (Unit/Integration), Playwright (E2E)

## Getting Started

### Prerequisites

*   Node.js (v18.x or higher recommended)
*   npm or yarn

### Installation

1.  **Clone the repository:**
    bash
    git clone https://github.com/chirag127/MultiSearch-AI-Search-Aggregator-Web-App.git
    cd MultiSearch-AI-Search-Aggregator-Web-App
    

2.  **Install dependencies:**
    bash
    npm install
    

## Development

### Running the Development Server

bash
npm run dev


This command starts the Vite development server, allowing you to see changes in real-time.

### Build for Production

bash
npm run build


This command creates an optimized build of your application in the `dist` folder.

### Scripts

| Script      | Description                                  |
| :---------- | :------------------------------------------- |
| `dev`       | Run the development server.                  |
| `build`     | Build the application for production.        |
| `lint`      | Run Biome linter and formatter.              |
| `test`      | Run Vitest unit and integration tests.       |
| `e2e`       | Run Playwright end-to-end tests.             |

## Contributing

We welcome contributions! Please see the [CONTRIBUTING.md](.github/CONTRIBUTING.md) file for detailed guidelines on how to submit pull requests and report issues.

## License

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0). See the [LICENSE](LICENSE) file for more details.

--- 

Star ⭐ this Repo